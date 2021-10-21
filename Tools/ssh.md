# SSH (Secure Shell)
Die Secure Shell wird für den sicheren Zugang auf `GitHub` mittels `git` benötigt.

## Sicherer Zugang (SSH-PSK) zu GitHub

SSH-Sitzungen können mit Nutzer-Passwort-Kombinationen gestartet werden. 
Eine zweite Möglichkeit ist die Nutzung eines sogenannten __Secure Shell Pre-Shared-Key__ (SSH-PSK).
Dort erstellt der Nutzer zwei Schlüssel die zusammen den PSK ergeben.
Der sogenannte öffentliche Teil-Schlüssel wird beim Dienstanbieter, z.B GitHub,  hinterlegt.
Der private Teil-Schlüssel bleibt auf dem Rechner des Nutzers.
Mit ihm können dann SSH-Sitzungen gestartet werden, ohne jedesmal eine Nutzer-Passwort-Kombination eingeben zu müssen.

(1) Schlüsselpaar mit einer Schlüssellänge von 4096 Bit erzeugen:

- `ssh-keygen -t rsa -b 4096`
- alle Fragen mit `<Enter>` bestätigen

(2) öffentlichen Schlüssel in die Zwischenablage kopieren:

- `cat ~/.ssh/id_rsa.pub
- den ausgegebenen Text markieren und kopieren
- 
(3) gehe auf deinen GitHub-Account und dort:

- `Menü rechts oben`
- `Settings`
- `SSH and GPG keys`
- `New SSH key`

(4) im sich öffnenden Dialog:

- `Title:` beliebigen Namen vergeben (Bsp.: "Rechner Zu Hause")
- `Key`: den Inhalt der Zwischenablage einfügen
- dann klicke `Add SSH key`
