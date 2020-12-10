# europace-productengine-api

Über diese API fragt BaufiSmart FINMAS Immobiliendarlehen-Angebote an.

## Arbeiten an der API

müssen über temporäre Feature-Branches und Pull Requests integriert werden. 
Mergen ist erst möglich, wenn mindestens eine Review mit Status 'Approved' eines Codeowners vorliegt.

### Release (durch Maintainer)

* Aus dem draft-Release ein richtiges Release machen
* dabei einen neuen Tag erstellen. Die Version in `api.json` verbleibt bei <major>.<minor>-DUMMY (bspw. 1.3-DUMMY), 
um unnötige Kommentarzeilen-Änderungen in den generierten API-Klassen durch die OpenAPI-CodeGenerierung zu vermeiden.

## Arbeiten mit der API

### Generierung eines Servers aus der API

Die API ist im Swagger-Format 2.0 (direkter Vorläufer von [OpenAPI](https://www.openapis.org/)) beschrieben. Über den [Swagger-Code-Generator](https://github.com/swagger-api/swagger-codegen) kann in den unterschiedlichsten Programmiersprachen eine Server-Implementierung direkt aus der API generiert werden.

### Konzepte

#### Beispiele

* [Anfrage](beispiele/anfrage.json)
* [Antwort](beispiele/antwort.json)

#### Angebote auch zu minimalem Datenset (Vorbehaltsmeldungen)

#### Statuslosigkeit (mit Konditionsangeboten)

#### Anpassungen (mit Meldungen)

#### Showstopper vs Rotmeldungen

#### Bindefrist und Bestzins

#### Übersichten
