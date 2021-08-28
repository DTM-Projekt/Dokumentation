# Kontrollstrukturen 

Eine Kontrollstruktur dient der Steuerung des Programmablaufs.

Es gibt:
* Fallunterscheidungen
* Schleifen

# Fallunterscheidungen (conditional statements)

Eine Fallunterscheidung ermöglicht die bedingte Ausführung von Code.

Es gibt:
* if-Anweisung
* else-Anweisung
* elif-Anweisung

# Die if-Anweisung
Die if-Anweisung führt
-wenn eine vorgegebene Bedingung zutrifft-
bestimmten Code aus.

## Merkmale einer if-Anweisung

Die if-Anweisung besteht aus:
* dem if
* der Überprüfung ob im Code vorgegebene Dinge zutreffen oder nicht zutreffen
* der/den Anweisung/Anweisungen daraufhin

## Schreiben einer if-Anweisung (Definition)

* Schreibe das `if` am Anfang der Zeile.
* Schreibe nach einem Leerzeichen eine `Klammer` und dann in die Klammer die `Überprüfung`.
* Nach der Klammer wird ein `Doppelpunkt` gesetzt, in die nächste Zeile gegangen und eingerückt.
* Jetzt werden die auszuführenden `Anweisungen` untereinander gesetzt, die ausgeführt werden sollen, wenn die `Überprüfung` WAHR ist.

```
if (Überprüfung):
    Anweisung 1
    Anweisung 2
    Anweisung N
```

## Beispiel einer if-Anweisung

Gegeben sei:
```
a = 5
b = 9
```
Überprüfung auf Gleichheit:
```
if (a == 5):
    print("a ist gleich fünf")
```
Überprüfung auf Ungleichheit:
```
if (b != 5):
    print("b ist ungleich 5")
```
Überprüfung ob ein Ausdruck größer als ein anderer Ausdruck ist:
```
if (b > a):
    print("b ist größer a")
```
Überprüfung ob ein Ausdruck kleiner als ein anderer Ausdruck ist:
```
if (b < a):
   print("b ist kleiner a")
``` 

# Die else-Anweisung

Die else-Anweisung führt
-wenn die im *if-Block* vorgegebene Bedingung nicht zutrifft-
bestimmten Code aus.

## Merkmale einer else-Anweisung

Die else-Anweisung besteht aus:
* der if-Anweisung davor
* dem else:    
* der/den Anweisung/Anweisungen daraufhin

## Schreiben einer else-Anweisung (Definition)

* Schreibe nach der `if-Anweisung` am Anfang einer neuen Zeile `else` und ein `Doppelpunkt`.
* Gehe in die nächste Zeile und rücke ein.
* Schreibe den `Befehl`, den die `else-Anweisung` ausführt, wenn die `if-Bedingung` nicht erfüllt wurde.

```
if (Überprüfung):
    Anweisung 1
    Anweisung 2
    Anweisung ..
else:
    Anweisung A
    Anweisung B
    Anweisung ..
```

## Beispiel einer else-Anweisung  
```
if (a == b):
    print("a ist gleich b")
else:
    print("a ist NICHT gleich b")
```

# Die elif-Anweisung

# Schleifen (loops)
Schleifen wiederholen Anweisungen solange eine Bedingung erfüllt ist.

Es gibt:
* while-Schleife
* for-Schleife

# Die while-Schleife
while-Schleifen wiederholen Anweisungen solange eine Bedingung erfüllt ist. Damit ist sie der Prototyp einer allgemeinen Schleife.

## Merkmale einer while-Schleife

Die while-Schleife besteht mindestens aus:
* dem `while`
* der Überprüfung
* der/den Anweisung/Anweisungen der Schleife (Schleifenkörper)

Die while-Schleife kann zusätzlich besitzen:
  * das continue im Schleifenkörper
  * das break im Schleifenkörper

## Schreiben einer while-Schleife (Definition)
* Schreibe am Anfang der Zeile ein `while`
* danach schreibe eine `Klammer`, deren Inhalt (Bedingung) und einen `Doppelpunkt`.
* Schreibe darunter (eingerückt) den gewünschten `Codeblock`, der wiederholt wird, solange die Bedingung wahr ist.

```
while(Bedingung):
    Anweisung 1
    Anweisung 2
    Anweisung N
```

## Beispiel einer while-Schleife
  
Gib die Zahlen von 0 bis 49 auf den Bildschirm aus:
```
x = 0
while(x < 50):
    print(x)
    x += 1
 ```
