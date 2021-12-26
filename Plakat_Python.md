# Python
Python ist eine leicht zu erlernende Programmiersprache.
Sie ist in Wissenschaft und Technik weit verbreitet.
Der Name entstand nicht wie viele denken,
durch die gleichnamige Schlange,
sondern durch die Komikergruppe 'Monty Python',
von denen der Python Entwickler Guido van Rossum ein großer Fan war.

Programme bestehen aus Anweisungen.
Die wichtigsten Python-Anweisungen möchte ich euch anhand eines kleinen Programms vorstellen.

## Das Programm "Zahlenraten"
```
 1  geheimnis = 1337
 2  versuch = −1
 3  zaehler = 0
 4  while versuch != geheimnis:
 5      versuch = int(input("Raten Sie: "))
 6      if versuch < geheimnis:
 7          print("Zu klein")
 8      if versuch > geheimnis:
 9          print("Zu groß")
10     zaehler = zaehler + 1
11  print("Super, Sie haben es in ", zaehler, "Versuchen geschafft!")
```

## Initialisierung von Variablen (Zeilen 1-3)
Bei der Initialisierung werden die für das Spiel benötigten Variablen angelegt.
Python unterscheidet zwischen verschiedenen Datentypen, wie etwa Zahlen und Zeichenketten.

## Schleifenkopf (Zeile 4)
Der unter dem Schleifenkopf notierte Schleifenkörper wird wiederholt,
solange die Variablen `versuch` und `geheimnis` nicht gleich (ungleich) sind.
Ein erneuter Durchlauf findet nicht statt,
wenn beide Variablen gleich sind.

## Schleifenkörper (Zeilen 5-10)
Der Schleifenkörper wird um mindestens ein Leerzeichen gegenüber dem Schleifenkopf nach rechts eingerückt.
- Zeile 5:
  - vom Spieler wird eine Zahl erfragt und in der Variable `versuch` gespeichert
- Zeile 6-7:
  - wenn die Variable `versuch` kleiner als die gesuchte Zahl ist, dann
  - gib den Text "Zu klein" aus
- Zeile 8-9:
  - wenn die Variable `versuch` größer als die gesuchte Zahl ist, dann
  - gib den Text "Zu groß" aus
- Zeile 10:
  - erhöhe den Wert der Variable `zaehler` um eins

## Bildschirmausgabe (Zeile 11)
Wenn die Schleife das letzte Mal durchlaufen wurde,
d.h. wenn der Spieler die richtige Zahl getippt hatte,
dann wird auf dem Bildschirm eine Erfolgsmeldung und die Anzahl der Versuche augegeben.
