## Arbeitsheft 2 Tutorials


MakeCode Tutorials für das Calliope Arbeitsheft 2

**Tutorials im Tutroial-Tool testen:**

https://makecode.com/tutorial-tool

### Tutorial aufrufen:

Die Tutorials können direkt als Link wie gefolgt aufgerufen werden:

MakeCode-Editor/Github-Account/Repository/Tutorial(ohne Mardown-Endung .md)

**Beispiel:**

https://makecode.calliope.cc/#tutorial:https://github.com/calliope-edu/arbeitsheft2-tutorials/tutorials/4.1_schere-stein-papier

**Liste der Tutorials:**

- "tutorials/4.1_schere-stein-papier"
- "tutorials/4.2_reaktionsspiel"
- ...

<!-- 
https://makecode.calliope.cc/#tutorial:https://github.com/jasperp92/makecode_tutorials/tutorials/lichtsirene
https://github.com/jasperp92/makecode_tutorials/blob/master/pxt.json -->

### Tutorials erstellen:

-  [ ] Herausfinden wie Blöcke nur pro Schritt hinzugefügt werden

https://makecode.com/writing-docs/user-tutorials
https://makecode.com/writing-docs/snippets

Enable Block validation:

**Enable the `BlocksExistValidator` globally and ignore highlighted blocks**  
_Note: highlight is not specified in the markers property._
````
```validation.global
# BlocksExistValidator
* markers: validate-exists
```
````

Blockunterschiede anzeigen:

```### @diffs true```

```diffblocks
let x = 1
----------
let x = 1
let y = 1
```

Blöcke verstecken:

// @hide


## Programme Issues
- 5.1.2 Haustier - Streicheln:
    - Fehler AH: wenn kleiner als 0 im Text, Programm >= 200
- 5.1.3 Haustier - Bewegung
    - [ ] hier fehlen noch Schritte zur Erklärung
- 5.1.4 Haustier - Spielen
    - hinzugefügt: Pfeil nach oben anzeigen bei Start.
    - Treppe ausührlicher: 1 Balken bei einem Wurf usw.
- 5.1.5 Haustier - Schlafen
    - Mit Funktion oder ohne?
- 5.1.6 Haustier - Hunger
    - ! Fehler im Programm. Futter muss am Ende zurück gesetzt werden.
    - Frage: Warum 2 Variablen für 6 Zustände, statt einer?
- 5.1.7 Haustier - Soziale Kontakte
    - [ x ] PAP einfügen
- 5.1.8 Haustier - Stimmung
    - Hier ggf. noch zusätzliche Schritte?
- 5.2 Haustier - Eigenes Projekt
    - Fehler im Code: Temperatur nur 2 Stufen? Abfrage kann komprimiert werden.


## TODO

- [ ] digitales Haustier Stimmung
- [ ] digitales Haustier eigenes Projekt
- [x] 3 RGB-LEDs werden nicht gerendert und tauchen demnach nicht in den "Blöcken" auf
- [x] Pin - Touch Logo auf der Rückseite wird nicht gerendert
- [x] DC-Motorblöcke Package, nicht gefunden. Blöcke nicht gerendert
- [x] Servo-Library neue Pins (C8) nicht gefunden.

Library für V3 hinzufügen, um aktuelle Böcke für den mini V3 anzuzeigen:

```package
v3
```