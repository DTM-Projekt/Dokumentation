# Funktionen

Eine Funktion ist ein benanntes Unterprogramm.

## Merkmale

* Funktionen bestehen mindestens aus:
  * dem Funktionsnamen
  * einem Codeblock
* Funktionen können zusätzlich besitzen:
  * eine Liste von Parametern
  * einen Rückgabewert

## Definition einer Funktion
```
def Funktionsname(Parameter_1,...,Parameter_N):
    erste Anweisung im Codeblock
    .
    .
    .
    letzte Anweisung im Codeblock
```
__Beispiel:__

* Definiere eine Funktion namens `quadrat`.
* Wenn keine Zahl übergeben wird, setze sie automatisch auf den Ganzzahlwert 2.
* Gib die Meldung `Ich rechne...` aus.
* Gib das Quadrat der übergebenen Zahl zurück:

```
def quadrat(zahl=2):
    print("Ich rechne...")
    ergebnis = zahl * zahl
    return ergebnis
```

## Benutzen einer Funktion

Ohne Rückgabewert, ohne Parameter:
```
quadrat()
```
Mit Rückgabewert, ohne Parameter:
```
y = quadrat()
```
Ohne Rückgabewert, mit Parameter:
```
quadrat(5)
```
Mit Rückgabewert, mit Parameter:
```
y = quadrat(5)
```

__Beachte:__

Funktionen ohne Rückgabewert werden im Allgemeinen _Prozeduren_ genannt.

## Prominente Funktionen

_print ist auch eine Funktion. Es bedeutet in Python "ausgeben"_
