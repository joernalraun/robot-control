Diese Erweiterung erweitert die vorhandene [MotionKit V2](https://github.com/tinysuperlab/MotionKitV2) Erweiterung um neue Blöcke. Mit diesen neuen Blöcken soll die Steuerung vereinfacht werden. Es gibt Blöcke, um den Roboter zu drehen oder eine bestimmte Strecke fahren zu lassen.

## Als Erweiterung verwenden

Dieses Repository kann als **Erweiterung** in MakeCode hinzugefügt werden.

* öffne [https://makecode.calliope.cc/](https://makecode.calliope.cc/)
* klicke auf **Neues Projekt**
* klicke auf **Erweiterungen** unter dem Zahnrad-Menü
* nach **Roboter Steuerung** suchen und importieren

## Kalibrierung

`Roboter.set_velocity(0)` Gib hier die Strecke in Zentimetern an, die der Roboter in einer Sekunde zurücklegt.
`Roboter.set_angular_velocity(0)` Gib hier den Winkel in Grad an, um den sich der Roboter innerhalb von 500 Millisekunden dreht.

## Nicht blockierendes Fahren

Der Befehl `Roboter.drive_time_non_blocking` bzw. der Block `Für [ZEIT] ms [RICHTUNG] fahren, dabei das Programm weiterlaufen lassen` sorgt dafür, dass das Programm während der Fahrt nicht angehalten wird. Nachfolgende Befehle werden sofort weiter ausgeführt.

## Dieses Projekt bearbeiten

Um dieses Repository in MakeCode zu bearbeiten.

* öffne [https://makecode.calliope.cc/](https://makecode.calliope.cc/)
* klicke auf **Importieren** und dann auf **Importiere URL**
* füge **https://github.com/Zukunftswerkstatt-Buchholz/robot-control** ein und klicke auf Importieren

#### Metadata (used for search, rendering)

* for PXT/calliopemini
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>


> Diese Seite bei [https://zukunftswerkstatt-buchholz.github.io/roboter-steuerung/](https://zukunftswerkstatt-buchholz.github.io/roboter-steuerung/) öffnen
