# Fallunterscheidungen (conditional statements)

Eine Fallunterscheidung ermöglicht die bedingte Ausführung von Code.

Es gibt:

- if-Anweisung
- else-Anweisung
- elif-Anweisung

## Die if-Anweisung

Die if-Anweisung führt
-wenn eine vorgegebene Bedingung zutrifft-
bestimmten Code aus.

### Merkmale einer if-Anweisung

Die if-Anweisung besteht aus:

- dem if
- der Bedingung
- Anweisungen die ausgeführt werden, wenn die Bedingung zutrifft

### Schreiben einer if-Anweisung (Definition)

- schreibe das Signalwort `if` am Anfang einer Zeile
- schreibe nach einem Leerzeichen die Bedingung
- schreibe nach der Bedingung ein `Doppelpunkt`
- gehe in die nächste Zeile und rücke ein
- setze `Anweisungen` untereinander, die ausgeführt werden sollen, wenn die Bedingung zutrifft.

```
if (Überprüfung):
    Anweisung 1
    Anweisung 2
    Anweisung N
```

### Beispiel für if-Anweisungen

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

## Die else-Anweisung

Die else-Anweisung führt
-wenn die im _if-Block_ vorgegebene Bedingung nicht zutrifft-
bestimmten Code aus.

### Merkmale einer else-Anweisung

Die else-Anweisung besteht aus:

- der if-Anweisung
- dem else:
- Anweisungen, die ausgeführt werden, wenn die if-Bedingung nicht zutrifft

### Schreiben einer else-Anweisung (Definition)

- gehe an den Anfang der Zeile nach einem if-Block
- schreibe das Signalwort `else`
- schreibe einen Doppelpunkt
- gehe in die nächste Zeile und rücke ein
- setze Anweisungen untereinander, die ausgeführt werden, wenn die if-Bedingung nicht zutrifft.

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

### Beispiel einer else-Anweisung

```
if (a == b):
    print("a ist gleich b")
else:
    print("a ist NICHT gleich b")
```

## Die elif-Anweisung

### Merkmale einer elif-Anweisung

Die else-Anweisung besteht aus:

- der if-Anweisung
- der elif-Anweisung
- der elif-Bedingung
- Anweisungen, die ausgeführt werden, wenn die if-Bedingung nicht, jedoch die elif-Bedingung zutrifft

### Schreiben einer elif-Anweisung (Definition)

- gehe an den Anfang der Zeile nach einem if-Block
- schreibe das Signalwort `elif`
- schreibe nach einem Leerzeichen die elif-Bedingung
- schreibe einen Doppelpunkt
- gehe in die nächste Zeile und rücke ein
- setze Anweisungen untereinander, die ausgeführt werden, wenn die if-Bedingung nicht, jedoch die elif-Bedingung zutrifft

```
if (if-Bedingung):
    Anweisung 1
    Anweisung 2
    Anweisung ..
elif (elif-Bedingung):
    Anweisung A
    Anweisung B
    Anweisung ..
else:
    Anweisung Z
    Anweisung Y
    Anweisung ..
```

### Beispiel einer elif-Anweisung

```
a = 1
b = 2
if (a == b):
    print("a ist gleich b")
elif (b == 2)
    print("a ist ungleich b und b ist gleich 2")
```
