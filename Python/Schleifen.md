# Schleifen (loops)

Schleifen sind Kontrollstrukturen, die Anweisungen wiederholen, solange eine Bedingung erfüllt ist.

Es gibt:

- while-Schleifen
- for-Schleifen

## Die while-Schleife

while-Schleifen wiederholen Anweisungen solange eine Bedingung erfüllt ist.
Sie ist der Prototyp einer allgemeinen Schleife.

### Merkmale einer while-Schleife

Die while-Schleife besteht mindestens aus:

- dem `while`
- der Überprüfung
- der/den Anweisung/Anweisungen der Schleife (Schleifenkörper)

Die while-Schleife kann zusätzlich besitzen:

- das continue im Schleifenkörper
- das break im Schleifenkörper

### Schreiben einer while-Schleife (Definition)

- Schreibe am Anfang der Zeile ein `while`
- danach schreibe eine `Klammer`, deren Inhalt (Bedingung) und einen `Doppelpunkt`.
- Schreibe darunter (eingerückt) den gewünschten `Codeblock`, der wiederholt wird, solange die Bedingung wahr ist.

```
while(Bedingung):
    Anweisung 1
    Anweisung 2
    Anweisung N
```

### Beispiel einer while-Schleife

Gib die Zahlen von 0 bis 49 auf den Bildschirm aus:

```
x = 0
while(x < 50):
    print(x)
    x += 1
```

## Die for-Schleife
