# Git

Eine kleine Einführung in Git.

---

Setze einen Namen sowie eine Emailadresse,
die ab sofort jeden Commit personalisieren:
```
git config --global user.name "Your Name"
git config --global user.email "youremail@yourdomain.com"
```

---

Commits, Dateien und Verweise werden aus einem Remote-Repository in dein lokales Repository heruntergeladen:
```
git fetch
```

---

Commits, Dateien und Verweise werden aus einem Remote-Repository in dein lokales Repository heruntergeladen.
Ausserdem wird ein Merge-Commit ausgeführt, der die heruntergeladenen Commits mit dem lokalen HEAD-Branch vereint:
```
git pull
```

---

Gelöschte Remote-Branches werden auch lokal gelöscht:
```
git fetch --prune
git pull --prune
git remote update origin --prune
```

---

Ändere die Git-Konfiguration dahingehend,
dass zukünftig bei sämtlichen Git-Befehlen,
die diese Option bieten,
der Schalter `--prune` automatisch gesetzt ist.
`--prune` bewirkt, dass gelöschte Remote-Branche auch lokal gelöscht werden.
```
git config remote.origin.prune true
```
