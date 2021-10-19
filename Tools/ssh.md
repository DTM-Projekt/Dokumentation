# SSH (Secure Shell)
Die Secure Shell wird für den sicheren Zugang auf `GitHub` mittels `git` benötigt.

## Sicheren Zugang (SSH-PSK) einrichten

(1) Schlüsselpaar erzeugen:

- `ssh-keygen -t rsa`
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

- `Title:` beliebigen Namen vergeben (Bsp.: "MacZuHause")
- `Key`: den Inhalt der Zwischenablage einfügen
- dann klicke `Add SSH key`

(5) SSH-Zugang testen:

- Repo mit git klonen
- Repo pushen
