# Software

Beschreibung der für mein Projekt verwendeten Software.

## Kurzübersicht

- Das Betriebssystem Rasperry Pi OS (Linux)
- Python3 als Programmiersprache
- VSCode als Programm- und Dokumentationseditor
- GitHub als zentrale Projektverwaltung
- Tools zur Pflege der Projektdaten

## Installation

Es folgen detaillierte Installationsanweisungen.

### Das Betriebssystem Rasperry Pi OS (Linux)

(1) Vorbereitung:

- Mini-SD-Karte // 32GB // Speed Class C10 oder U1
- Mit dem `Rasperry Pi Imager` `Raspberry Pi OS` auf SD-Karte schreiben
- RPi starten und Willkommen-Dialog abarbeiten

(2) Betriebssystem auf den neuesten Stand bringen:

```
sudo apt update
sudo apt upgrade
sudo apt autoremove
```

(3) Tools für tägliche Arbeit installieren:

```
sudo apt install mc
sudo apt install firefox-esr
sudo apt install xclip
```

### Python3 als Programmiersprache

Python3 ist im Betriebssystem Rasperry Pi OS integriert
und muss deshalb nicht installiert werden.

### VSCode als Programm- und Dokumentationseditor

```
sudo apt install code
code --install-extension alefragnani.project-manager
code --install-extension mhutchie.git-graph
code --install-extension ms-python.python
code --install-extension ms-python.vscode-pylance
code --install-extension ms-toolsai.jupyter
code --install-extension svipas.prettier-plus
pip3 install autopep8
```

### GitHub als zentrale Projektverwaltung

- Auf GitHub können Programmierer den Quellcode ihrer Softwares speichern.
- Andere Programmierer und Tester können leicht an den Projekten mitwirken.

### _Account erstellen_

- suche einen eingängigen Nutzernamen
- nutze einen eingängigen Email-Account

### _Zwischenschritt: Git lokal einrichten_

```
git config --global user.name "Your Name"
git config --global user.email "youremail@yourdomain.com"
```

### _Projekt erstellen_

- suche einen eingängigen Namen für dein erstes Projekt

### _Sicheren Zugang (SSH-PSK) einrichten_

(1) Schlüsselpaar erzeugen:

- `ssh-keygen -t rsa`
- alle Fragen mit `<Enter>` bestätigen

(2) öffentlichen Schlüssel in die Zwischenablage kopieren:

- `cat ~/.ssh/id_rsa.pub | xclip -i -selection clipboard`

(3) gehe auf deinen GitHub-Account und dort:

- `Menü rechts oben`
- `Settings`
- `SSH and GPG keys`
- `New SSH key`

(4) im sich öffnenden Dialog:

- `Title:` beliebigen Namen vergeben (Bsp.: "RaspberryPi")
- `Key`: den Inhalt der Zwischenablage einfügen
- dann klicke `Add SSH key`

(5) SSH-Zugang testen:

- Repo mit ssh klonen
- Repo pushen

### Tools zur Pflege der Projektdaten

Genutzt werden fünf Git-Client's:

- git
- git-gui
- gitui
- lazygit
- git-cola

Gründe:

- jeweils eigene Stärken
- schnelleres Erlernen des git-Befehls
- flexibles Arbeiten

Tools installieren:

```
# git
# Das Paket "git" ist im Betriebssystem Rasperry Pi OS integriert.

# git-gui
sudo apt install git-gui

# git-cola
sudo apt install git-cola

# lazygit
sudo apt install golang
git clone https://github.com/jesseduffield/lazygit.git
cd lazygit
go install
echo 'export PATH=$PATH:/home/pi/go/bin' >> ~/.bashrc
cd

# gitui
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
git clone https://github.com/extrawurst/gitui.git
cd gitui
cargo install gitui
cd
```
