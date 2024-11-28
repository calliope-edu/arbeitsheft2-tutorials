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
- 5.1.4 Haustier - Spielen
    - [ ] Bilder rein
- 5.1.6 Haustier - Hunger
    - Zustände mit Booleans: 2 Versionen


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