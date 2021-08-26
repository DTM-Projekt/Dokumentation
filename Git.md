# Git

Eine kleine Einführung in `Git`.

## Tägliche Arbeit mit Git

Commits, Dateien und Verweise werden aus einem Remote-Repository in dein lokales Repository heruntergeladen:
```
git fetch
```

Commits, Dateien und Verweise werden aus einem Remote-Repository in dein lokales Repository heruntergeladen.
Ausserdem wird ein Merge-Commit ausgeführt, der die heruntergeladenen Commits mit dem lokalen HEAD-Branch vereint:
```
git pull
```

Gelöschte Remote-Branches werden auch lokal gelöscht:
```
git fetch --prune
git pull --prune
git remote update origin --prune
```

Dieser Befehl ändert die Git-Konfiguration dahingehend,
dass zukünftig bei sämtlichen Git-Befehlen,
die diese Option bieten,
der Schalter `--prune` automatisch gesetzt ist:
```
git config remote.origin.prune true
```
