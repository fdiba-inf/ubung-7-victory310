# Übung 7
Quellcode der Vorlesung: https://github.com/fdiba-inf/vorlesung
## Repl.it öffnen
Bevor Sie die Taste _"Work in Repl.it"_ klicken, öffnen Sie https://repl.it/auth/github/get, um sicherzustellen, dass Sie in repl.it angemeldet sind.
## Aufgabe 1. Stunden und Minuten
Ändern Sie die Klasse _TimeValidation_ im Paket _exercise7_. 
Der Benutzer soll eine Zahl für Stunden und eine Zahl für Minuten eingeben.
Die Applikation soll überprüfen, ob die eingegebenen Werte korrekt sind.
* Stunden _[0, 24)_
* Minuten _[0, 60)_

Ausgabe:
``` 
Time valid: <true/false>
``` 
## Aufgabe 2. Dreieck
Ändern Sie die Klasse _Triangle_ im Paket _exercise7_. 
Der Benutzer soll eine Zahl _n_ eingeben.
Die Applikation soll ein Dreieck in der Konsole ausgeben. <br>
Ausgabe für _n = 3_:
``` 
1
1 2
1 2 3
1 2
1
``` 
Ausgabe für _n = 4_:
``` 
1
1 2
1 2 3
1 2 3 4
1 2 3
1 2
1
``` 
## Aufgabe 3. Auftreten einer Zahl
Ändern Sie die Klasse _NumberCounter_ im Paket _exercise7_. 
Beim Starten soll der Benutzer die Größe eines Feldes, seine Elemente and ein gesuchtes Element in der Konsole eingeben.
Die Applikation soll berechnen, wie oft das gesuchte Element im Feld auftritt. <br>
Ausgabe für Größe _4_, Elemente _8, 9, 3, 9_ und gesuchtes Element _9_:
```
Number occurrences: 2
```
Ausgabe für Größe _3_, Elemente _8, 9, 3_ und gesuchtes Element _6_:
```
Number occurrences: 0
```
## Aufgabe 4. Rekursive Ausgabe von Primzahlen
Ändern Sie die Klasse _RecursivePrimePrinter_ im Paket _exercise7_. 
Der Benutzer soll eine Zahl _n_ eingeben.
Die Applikation soll alle Primzahlen zwischen _n_ und _0_ ausgeben.
Erstellen Sie eine rekursive Lösung. <br>
Ausgabe für _n = 10_:
``` 
7
5
3
2
1
``` 
Ausgabe für _n = 15_:
``` 
13
11
7
5
3
2
1
``` 
## Achtung! Achtung! Achtung!
Wenn Sie alle Aufgaben gemacht haben, sollen Sie die Lösungen in _GitHub_ hochladen. 
Wenn "Version Control" nicht verfügbar ist, geben Sie die folgenden Befehle in die Konsole ein:
``` 
git pull
git add .
git commit -m "Some message"
git push
``` 
