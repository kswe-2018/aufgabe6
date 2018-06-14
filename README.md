# KSwe SoSe 2018 - Aufgabe 6

Erstelle die API für Messstationen mit Hilfe des Swagger Editors:

http://editor.swagger.io/

## Ziel

Die API soll die in den Vorlesungsfolien beschriebene Funktionalität
aufweisen:

* Endpunkt `/features`
* Endpunkt `/features/{identifer}`
* Endpunkt `/features/{identifer}/observations`

Auch die Filterung nach Start- und Endzeit der Messwerte soll mit Hilfe
von Parametern umgesetzt werden.

## Generierung eines Spring-Servers

Nach Fertigstellung der API soll mit Hilfe von Codegen ein `Spring`-Server
erstellt werden. Nutze hierzu die Funktionalität des Editors.

Nach Entpacken des Codes kann dieser in die IDE eingeladen werden. Der Code
sollte eine Klasse `Swagger2SpringBoot.java` enthalten. Diese verfügt über
eine `main`-Methode und kann aus der IDE gestartet werden.

## Test der API

Nachdem die Anwendung gestartet wurde, soll diese mit der Swagger UI getestet
werden. Die UI ist über den Browser aufrufbar, z.B.:

http://localhost:8080/sensor-api/swagger-ui.html

