---
layout: page
---
# Tutorials
---
[Installation](/download.html) &nbsp;&nbsp; Erste Schritte &nbsp;&nbsp; [Sprachsynthese](sprachsynthese.html) &nbsp;&nbsp; [Spracherkennung](spracherkennung.html) &nbsp;&nbsp; [Grammatiken](grammatiken.html) &nbsp;&nbsp; [Externe Programme](extprogramme.html)

---
&nbsp;
## Erste Schritte mit DialogOS

### DialogOS starten
- Windows:  
über das DialogOS Icon [TODO Icon] auf dem Desktop, oder TODO
- Mac:  
TODO
- Linux:  
TODO

### Das Arbeitsfenster
Mit Klick auf *neuen Dialog erstellen* öffnet sich das Arbeitsfenster mit einem neuen, bis auf den Startknoten, noch leeren Dialog. Das Fenster besteht aus den folgenden vier Bereichen:
- **Arbeitsfläche**: befindet sich in der Mitte des Fensters. Diese dient der Beschreibung des Dialogs und ermöglicht das Verschieben, Verbinden und (durch ein Doppelklick auf eine Box) Konfigurieren von Dialogzuständen. 
- **Knotenleiste**: Menü am rechten Rand des Bildschirms mit allen verfügbaren Knotentypen / Boxen. Diese lassen sich per Drag&Drop in die Arbeitsfläche ziehen.
- **Symbolleiste**: befindlich am oberen Rand des Fensters. Bietet Zugriff auf häufig benötigte Funktionen in DialogOS (ermöglicht z.B. den Abbruch eines laufenden Dialogs).
- **Prozedurliste**: Menü am linken Rand mit einer Liste aller Untergraphen (Teildialoge) -- es können mehrere Knoten / Boxen zu einem eigenen (Teil-)Dialog zusammengefasst werden. 

### Speichern
Auch wenn es selbstverständlich sein sollte, möchten wir hier noch einmal auf die Wichtigkeit des häufigen Speicherns hinweisen. Wie immer beim programmieren solltet ihr möglichst häufig speichern, um euren Fortschritt nicht zu verlieren, falls das Programm abstürzen sollte. Das sollte nicht passieren, aber man weiß ja nie...

### Einen Dialog erstellen
Ein einfacher Dialog besteht erst einmal aus Spracheingabe und Sprachausgabe. Die Sprachausgabe-Box lässt den Computer etwas sagen, die Spracherkennungs-Box lässt ihn zuhören.

#### Sprachausgabe-Box
Um eine Sprachausgabe einzurichten, muss erst einmal per Drag&Drop eine Sprachausgabe-Box in den Dialog eingefügt werden. (Du findest diese im Menü unten rechts.) Mit Doppelklick auf die soeben erstellte Sprachausgabe-Box öffnet sich ein neues Fenster. Wähle dort *Sprachausgabe* und füge in dem Feld *Ausgabe* den Text ein, den der Computer ausgeben soll. Mit *Anhöhren* kannst du die erstellte Sprachausgabe testen. Zum Schluss mit *OK* bestätigen.

#### Spracherkennungs-Box
Um eine Spracherkennung einzurichten, muss auch erst einmal per Drag&Drop eine Spracherkennungs-Box in den Dialog eingefügt werden. (Auch diese findest du in der Knotenleiste.) Mit Doppelklick auf die soeben erstellte Spracherkennungs-Box öffnet sich ein neues Fenster. Wähle dort *Spracherkennung* und füge mit *Neu* in die Liste *Zu erkennende Wörter/Sätze* neue Wörter / Sätze ein, die dein Programm erkennen können soll.  Wie auch schon bei der Sprachausgabe kannst du deine Einstellungen austesten (mit *Ausprobieren*) und mit *OK* bestätigen. DialogOS hat nun an die bearbeitete Spracherkennungs-Box genau so viele Pfeile angefügt, wie du Möglichkeiten für die Erkennung vorgegeben habt.

Tipp: Keine ganzen Sätze vorgeben, denn diese müssen dann auch **exakt** wie vorgegeben gesagt werden, um erkannt zu werden. Besser sind ein oder zwei Wörter.

### Dialog Ausführen
Um aus den erstellten Spracherkennungs- und Sprachausgabe-Boxen einen Dialog zu formen, müssen diese in der richtigen Reihenfolge verbunden werden. Dies funktioniert durch Anklicken eines Ausgangspfeils einer Box und ziehen der entstehenden Kante auf eine beliebige andere Box. Füge nun noch ein *Ende* Symbol ein (wieder zu finden in der Knotenleiste). Achte darauf, alle Boxen, nach denen kein weiterer Dialog mehr folgt, mit dem *Ende* Symbol zu verbinden. Nun kannst du deinen Dialog mit einem Klick auf *Ausführen* ausprobieren (denk ans speichern!). 

Tipp: mit Headset klappt die Erkennung besser.

#### Dialog prüfen
Durch Auswählen des Menüpunktes *Graph* (oberhalb der Symbolleiste) und im folgenden Dropdown-Menü *Überprüfen*, kann der erstellte Dialog überprüft werden. Dadurch werden Fehler, welche zum Abbruch des Dialogs führen würden, gefunden und angezeigt (z.B. nicht verbundene Knoten / Boxen oder ein fehlendes *Ende* Symbol).





