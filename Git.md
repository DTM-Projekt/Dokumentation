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
git remote update origin --prune
```

Die Git-Konfiguration wird so geändert,
dass zukünftig `git fetch` und `git pull` immer mit der Option `--prune` ausgeführt werden:
```
git config remote.origin.prune true
```
