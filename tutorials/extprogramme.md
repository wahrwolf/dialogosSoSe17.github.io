---
layout: page
---
# Externe Programme
---
[Einleitung](/tutorials.html) &nbsp;&nbsp; [Erste Schritte](ersteschritte.html) &nbsp;&nbsp; [Sprachsynthese](sprachsynthese.html) &nbsp;&nbsp; [Spracherkennung](spracherkennung.html) &nbsp;&nbsp; [Grammatiken](grammatiken.html) &nbsp;&nbsp; Externe Programme

---
&nbsp;

TODO

* DialogOS kann über "Nachrichten" mit in Java geschriebenen Programmen kommunizieren (Mitteilung oder Anfrage/Ergebnis). In jedem Fall muss der Dialog in DialogOS die Kommunikation initiieren
* Direkt zu Beginn eines Dialogs versucht DialogOS die Verbindung zum externen Programm herzustellen (deswegen muss das externe Programm zuerst gestartet werden), um im Dialogverlauf Nachrichten austauschen zu können. Die Verbindung wird mit Ende des Dialogs wieder getrennt.

## Externe Programme anbinden
* Unter *Dialog*, *Geräte* wird das Externe Programm hinzugefügt 

## Ausgabe-Knoten
* wird im Dialogablauf ein Ausgabe-Konten erreicht, schickt DialogOS die entsprechende Mitteilung als Skript-Ausdruck an das gewählte Programm

## Eingabe-Knoten
* wird ein Eingabe-Knoten erreicht, so wird zunächst eine Ausgabe von DialogOS an das gewählte Programm geschickt, welches das Ergebnis errechnet und zurückschickt, dass in DialogOS als Eingabe weiterverarbeitet werden kann

&nbsp;  
*Ein- und Ausgabe-Knoten können beliebig wiederholt werden, auch Verbindungen mit mehreren externen Programmen sind möglich*

## Nachrichten-Austausch
TODO 






