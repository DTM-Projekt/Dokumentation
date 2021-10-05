# Numerische Datentypen

Der numerische Datentyp kennt nur reine Zahlenwerte.

## Ganzzahlen (Integer)

Die Menge der ganzen Zahlen umfasst die natürlichen Zahlen und ihre Gegenzahlen bis zum Speicherlimit. 

### Merkmale

* Ganzzahlen bestehen aus:
  * dem Zahlenwert
* Ganzzahlen werden integer genannt. Wird das Wort integer im Programm verwendet, wird _int_ geschrieben

### Benutzen einer Ganzzahl

In einer Variable:
```
x = 5

if(x == int):
    print("Ist richtig")
```
Im direkten vergleich:
```
if(5 == int):
    print("Ist richtig")
```

## Binärzahlen (Binary numbers)

Binärzahlen sind die Zahlen, die nur aus 0 und 1 bestehen.

### Merkmale

* Binärzahlen bestehen aus:
  * Nullen und Einsen
  * dem "0b" vor der eigentlichen Zahl

### Benutzen einer Binärzahl

In einer Variable:
```
x = 0b101

if(x == int):
    print("Ist richtig")
```
Im direkten vergleich:
```
if(0b101 == int):
    print("Ist richtig")
```

__Merke:__  
Auch wenn Binäre Zahlen zu dem Binärsystem gehören ist ihr typ immer noch integer, da sie in Zahlen umgerechnet nur Ganzzahlen ergeben können.

## Gleitkommazahlen (Float)

Eine Gleitkommazahl ist eine Darstellung einer Zahl mithilfe der Exponentialschreibweise.

### Merkmale

* Gleitkommazahlen bestehen aus:
  * dem Ganzzahlwert
  * dem Kommawert

### Benutzen einer Gleitkommazahl

In einer Variable:
```
x = 5.5

if(x == float):
    print("Ist richtig")
```
Im direkten vergleich:
```
if(x == float):
    print("Ist richtig")
```

## Boolsche Werte (Bool)

Ein boolescher Wert stellt einen Wahrheitswert dar.

### Merkmale

* Boolsche Werte bestehen aus:
  * die Aussage
  * dem True oder dem False in der Ausgabe

### Schreiben eines Boolschen wertes

schreibe am Anfang der Zeile die `Aussage` die auf `True` oder `False` überprüft werden soll.

__Beispiel:__  
```
Aussage
.
.
.
          AUSGABE: True / False
```

### Benutzen eines Boolschen Wertes

Generelles Beispiel:
```
a == a

          AUSGABE: True
```
```
a == b

          AUSGABE: False

