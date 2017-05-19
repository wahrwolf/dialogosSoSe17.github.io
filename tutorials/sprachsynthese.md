---
layout: page
---
# Sprachsynthese
---
[Einleitung](/tutorials.html) &nbsp;&nbsp; [Erste Schritte](ersteschritte.html) &nbsp;&nbsp; Sprachsynthese &nbsp;&nbsp; [Spracherkennung](spracherkennung.html) &nbsp;&nbsp; [Grammatiken](grammatiken.html) &nbsp;&nbsp; [Externe Programme](extprogramme.html)

---
&nbsp;

DialogOS enthält ein eingebautes Text-to-Speech-System, das es erlaubt, beliebige Texte vorzulesen. Der zu sprechende Text muss also -- in der Theorie -- nur eingetippt werden. Keine Sprachsynthese funktioniert jedoch jemals perfekt, jedenfalls nicht immer im ersten Anlauf. In diesem Tutorial soll darauf eingegangen werden, wie die Sprachsynthese beeinflusst werden kann.

Mit einem Doppelklick auf den zu ändernden Sprachausgabe-Knoten können die Eigenschaften desselben bearbeitet werden. Um die Eigenschaften der Sprachsynthese zu konfigurieren, wähle den Reiter *Sprachausgabe*... [TODO?]

## Unterschiedliche Stimmen
An jedem Sprachausgabe-Knoten kann gesondert ausgewählt werden, mit welcher Stimme der angegebene Text gesprochen werden soll. Dafür ... [TODO]

Um die Stimme nicht für jeden Sprachausgabe-Knoten einzeln einstellen zu müssen, kann eine Standardstimme für den gesamten Dialog gesetzt werden. Wähle hierzu im Menü *Dialog* (oberhalb der Symbolleiste)  *Sprachausgabe* aus. Dann öffnet sich ein Fenster, in welchem die Standardstimme festgelegt werden kann. [Abbildung zu Dialogeinstellungen für die Sprachausgabe?] [TODO Beschreibung?] Alle nachfolgend erstellten Sprachausgabe-Knoten haben nun als Stimme die *Standardstimme*. Diese Einstellung kann natürlich an ausgewählten Knoten verändert werden.

<!--
Auf die gleiche Art und Weise lässt sich eine Standardstimme für die Spracheingabe-Knoten bestimmen. Im Menü *Dialog* muss hierfür der Befehl *Spracherkennung* ausgewählt werden. [TODO]
-->

## (korrekte) Aussprache
TODO

### Sprache
TODO

### Abkürzungen
TODO

### Zahlen
TODO

## Sprechmelodie
TODO

## Laufzeitverhalten
Standartmäßig wartet DialogOS, bis die aktuelle Sprachausgabe abgeschlossen ist, bevor der Dialog im nächsten Knoten fortgesetzt wird. Wird diese Option deaktiviert (*Warten bis die Ausgabe abgeschlossen ist*), wird der Dialog fortgesetzt, während das System noch spricht. So kann z.B. die Spracherkennung aktiviert werden (o.A.), während gleichzeitig noch die Sprachausgabe läuft.


