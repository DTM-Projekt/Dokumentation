# Python
Python ist eine leicht zu erlernende Programmiersprache.
Sie ist in Wissenschaft und Technik weit verbreitet.
Der Name entstand nicht wie viele denken,
durch die gleichnamige Schlange,
sondern durch die Komikergruppe 'Monty Python',
von denen der Python Entwickler Guido van Rossum ein großer Fan war.

## Variablen
Eine Variable gibt Daten einen Namen.

Dabei gilt:
```
Variablenname = Variableninhalt
```
Variablen können verschiedene Datentypen aufnehmen:
- Ganzzahlen (Integer)
- Gleitkommazahlen (Float)
- Listen (List)
- Zeichenketten (String)


## Ganzzahlen (Integer)
Eine Ganzzahl ist eine Zahl aus der Menge der Ganzen Zahlen (Q).

Beispiele:
```
>>> 15
15
>>> -72
-72
>>> 3*(-6)
-18
```

## Gleitkommazahlen (Float)
Eine Gleitkommazahl ist eine Zahl aus der Menge der Rationalen Zahlen (R).

Beispiele:
```
>>> 5.5
5.5
>>> -1/3
-0.3333333333333333
>>> 0.01*100
1.0
```

## Listen (List)
Eine Liste ist eine Verkettung von Elementen. Ein Element kann beliebigen Datentyps sein.

Beispiele:
```
>>> list = ['Tolle', 'Liste']
>>> [1, -1, 1+3, 'Drei', -0.88, list]
[1, -1, 4, 'Drei', -0.88, ['Tolle', 'Liste']]
```

## Zeichenketten (String)
Eine Zeichenkette ist eine Sonderform der Liste. Ihre Elemente bestehen aus Buchstaben, Zahlen oder Sonderzeichen.

Beispiele:
```
>>> string = 'Das ist 1 String!!!'
>>> string += ' Und Das wurde hinzugefügt!'
>>> string 
'Das ist 1 String!!! Und Das wurde hinzugefügt!' 


## If-Anweisung

Die if-Anweisung führt -wenn eine vorgegebene Bedingung zutrifft- bestimmten Code aus.


Dabei gilt:
```
if (Bedingungsüberprüfung):
    Ausführungsanweisung
```

Die if-Anweisung kann Werte jeden Datentyps überprüfen.


## Else-Anweisung

Die Else Anweisung führt, wenn die if-Bedingung und ggf. die elif-Bedingung(en) nicht zutrifft, bestimmten Code aus.

Dabei gilt:
```
if (Bedingungsüberprüfung):
    Ausführungsanweisung

else()
    Ausführungsanweisung
```


## Elif-Anweisung

Die Elif Aweisung führt, wenn die if-Bedingung nicht zutrifft und die elif-bedingung zutrifft, bestimmten Code aus.

Dabei gilt:
```
if (Bedingungsüberprüfung)
    Ausführungsanweisung

elif (Bedingungsüberprüfung)
    Ausführungsanweisung

else ()
    Ausführungsanweisung
```


## While-Schleife

Die while-Schleife führt, SOLANGE eine Bedingung zutrifft, bestimmten Code immer wieder aus.

Dabei gilt:
```
While(Parameter):
    Ausführungsanweisung
```
