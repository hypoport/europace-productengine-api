# europace-productengine-api

Diese API ist für Produktanbieter, die Angebote liefern wollen. Das bedeutet, eine Implementierung dieser API muss in der Lage sein, auf diese [beispiel Anfrage](beispiele/anfrage.json) eine [beispiel Antwort](beispiele/antwort.json) zu liefern.

## Arbeiten an der API

erfolgen nach dem [Fork/PR-Pattern von Github](https://guides.github.com/activities/forking/).

### Release (durch Maintainer)

1. neuen Tag passend zu der Version in `api.json` erstellen
   * über die Github-Web-Oberfläche
   * oder lokal, dann beim Push darauf achten, dass auch der Tag gepushed wird (z.B. `git push --follow-tags`)

## Arbeiten mit der API

### Generierung eines Servers aus der API

Die API ist im Swagger-Format 2.0 (direkter Vorläufer von [OpenAPI](https://www.openapis.org/)) beschrieben. Über den [Swagger-Code-Generator](https://github.com/swagger-api/swagger-codegen) kann in den unterschiedlichsten Programmiersprachen eine Server-Implementierung direkt aus der API generiert werden.

### Konzepte

#### Angebote auch zu minimalem Datenset (Vorbehaltsmeldungen)

#### Statuslosigkeit (mit Konditionsangeboten)

#### Anpassungen (mit Meldungen)

#### Showstopper vs Rotmeldungen

#### Bindefrist und Bestzins

#### Übersichten