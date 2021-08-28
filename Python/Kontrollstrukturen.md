# Kontrollstrukturen 

Eine Kontrollstruktur dient der Steuerung des Programmablaufs. 

Es gibt:
* Fallunterscheidungen (if/else/elif)
* Schleifen (while/for)

## Fallunterscheidungen (conditional statements)

Eine Fallunterscheidung ermöglicht die bedingte Ausführung von Code.

### __if-Anweisung__

Die if-Anweisung führt
-wenn eine vorgegebene Bedingung zutrifft-
bestimmten Code aus.

### Merkmale einer if-Anweisung

Die if-Anweisung besteht aus:
* dem if
* der Überprüfung ob im Code vorgegebene Dinge zutreffen oder nicht zutreffen
* der/den Anweisung/Anweisungen daraufhin

### Schreiben einer if-Anweisung (Definition)

* Schreibe das `if` am Anfang der Zeile.
* Schreibe nach einem Leerzeichen eine `Klammer` und dann in die Klammer die `Überprüfung`.
* Nach der Klammer wird ein `Doppelpunkt` gesetzt, in die nächste Zeile gegangen und eingerückt.
* Jetzt werden die auszuführenden `Anweisungen` untereinander gesetzt, die ausgeführt werden sollen, wenn die `Überprüfung` WAHR ist.

__Ergebnis:__

```
if (Überprüfung):
    Anweisung 1
    Anweisung 2
    Anweisung N
```

__Beispiel:__

Gegeben sei:
```
a = 5
b = 9
```

Überprüfung auf gleichheit:
```
if(a == 5):
    print("a ist gleich fünf")
```
Überprüfung auf Ungleichheit:
```
if(b != 5):
    print("b ist ungleich 5")
```
Überprüfung ob ein Ausdruck größer als ein Anderer ist:
```
if(5 > 4):
    print("Entspricht der Wahrheit")
```
Überprüfung ob ein Ausdruck kleiner als ein Anderer ist:
```
if(5 < 6):
   print("Entspricht der Wahrheit")
``` 
__Beachte:__  
Vergleiche können auch mit Variablen durchgeführt werden.

### __else-Anweisung__

Die else-Anweisung führt im Code vorgegebene Dinge aus wenn die if-Bedingung nicht erfüllt wurde.

#### Merkmale

* Die else-Anweisung besteht aus:
  * der if-Anweisung davor
  * dem else
  * der Anweisung daraufhin

#### Schreiben einer else-Anweisung (Definition)

```
if-Anweisung(Überprüfung):
    die Anweisung daraufhin
else-Anweisung:
    die Anweisung daraufhin
```
__Beispiel:__  
Schreibe nach der `if-Anweisung` am Anfang einer neuen Zeile `else` und ein `Doppelpunkt`. Gehe in die nächste Zeile und rücke ein undd schreibe den `Befehl`, den die `else-Anweisung` ausführt, wenn die `if-Bedingung` nicht erfüllt wurde.
```
if(1 == 2):
    print("Ist richtig")
else:
    print("Ist nicht richtig")
```

#### Benutzen des elses

__Generell:__ Wenn die if-Bedingung nicht erfüllt wurde:
```
if(5 == 6):
    print("Ist richtig")
else:
    print("Ist nicht richtig")
```
oder:
```
if(5 != 5):
    print("Ist richtig")
else:
    print("Ist nicht richtig")
```
oder:
```
if(5 > 5):
    print("Ist richtig")
else:
    print("Ist nicht richtig")
```
oder:
```
if(5 < 5):
    print("Ist richtig")
else:
    print("Ist nicht richtig")
```



## Schleifen (loops)

### __while-Schleife__

Die while-Schleife wiederholt einen Codeblock solange eine im Code bestimmte Bedingung richtig ist.

#### Merkmale

* Die while-Schleife besteht mindestens aus:
  * dem While, der Klammer dannach und ggf. ihrem Inhalt und dem Doppelpunkt dannach
  * dem codeblock dannach
  * dem continue am ende des blocks
* Die while-Schleife kann zusätzlich besitzen:
  * das break

#### Schreiben einer while-Schleife (Definition)

```
while(True oder False):

codeblock
    continue
.
.
.
codeblock
    break
```
__Beispiel:__  
Schreibe am Anfang der Zeile ein `while`, eine `Klammer`, ggf. deren Inhalt und ein `Doppelpunkt`. Schreibe zwei Zeilen darunter den gewünschten `Codeblock` der solange wiederholt wird wie er wahr / falsch ist. Jetzt wird ein `continue` geschrieben das bewirkt, dass die Schleife wiederholt wird. 
```
while(True):

x = 1
if(x != 50):
    x + 1
    continue
if(X == 50):
    break
```

#### Benutzen einer while-Schleife

Wiederholung solange True:
```
x = 1

while(True):

if(x != 50):
    x + 1
    continue
if(x == 50):
    break
```
Wiederholung solange False:
```
x = 1

while(False):

if(x == 50):
    x + 1
    continue
if(x != 50):
    break
```

Endlosschleife:
```
x = 1

while(x == x):
    x+1
    continue
```

