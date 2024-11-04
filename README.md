# rekrutteringsbistand-stilling-kafkabro
Kopiering av stillingsdata fra Arbeidsplassens Kafka-topic med kort retention til team Inkludering sin Kafka-topic med lang retention

# Lese meldinger på nytt til en "ren" topic
* Lag en ny topic som vi kan skrive til. Den har samme navn som forrige topic, men inkrementert med 1
* Eksisterende topic er referert i configmap.yaml, denne endrer vi til å referere til nytt topic navn.
* For å tilbakerulle offset, setter vi nytt navn i miljøvariabelen NAIS_CLIENT_ID i nais.yaml. Navnet kan inkrementeres med 1.

## Henvendelser

### For Nav-ansatte
* Dette Git-repositoriet eies av [team Toi](https://teamkatalog.nav.no/team/76f378c5-eb35-42db-9f4d-0e8197be0131).
* Slack: [#arbeidsgiver-toi-dev](https://nav-it.slack.com/archives/C02HTU8DBSR)

### For folk utenfor Nav
* IT-avdelingen i [Arbeids- og velferdsdirektoratet](https://www.nav.no/no/NAV+og+samfunn/Kontakt+NAV/Relatert+informasjon/arbeids-og-velferdsdirektoratet-kontorinformasjon)

