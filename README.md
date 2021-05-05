# rekrutteringsbistand-stilling-kafkabro
Kopiering av stillingsdata fra Arbeidsplassens Kafka-topic med kort retention til team Inkludering sin Kafka-topic med lang retention

# Lese meldinger på nytt til en "ren" topic
* Lag en ny topic som vi kan skrive til. Den har samme navn som forrige topic, men inkrementert med 1
* Eksisterende topic er referert i configmap.yaml, denne endrer vi til å referere til nytt topic navn.
* For å tilbakerulle offset, setter vi nytt navn i miljøvariabelen NAIS_CLIENT_ID i nais.yaml. Navnet kan inkrementeres med 1.

# Henvendelser

## For Nav-ansatte
* Dette Git-repositoriet eies av [Team inkludering i Produktområde arbeidsgiver](https://navno.sharepoint.com/sites/intranett-prosjekter-og-utvikling/SitePages/Produktomr%C3%A5de-arbeidsgiver.aspx).
* Slack-kanaler:
    * [#inkludering-utvikling](https://nav-it.slack.com/archives/CQZU35J6A)
    * [#arbeidsgiver-utvikling](https://nav-it.slack.com/archives/CD4MES6BB)
    * [#arbeidsgiver-general](https://nav-it.slack.com/archives/CCM649PDH)

## For folk utenfor Nav
* Opprett gjerne en issue i Github for alle typer spørsmål
* IT-utviklerne i Github-teamet https://github.com/orgs/navikt/teams/arbeidsgiver
* IT-avdelingen i [Arbeids- og velferdsdirektoratet](https://www.nav.no/no/NAV+og+samfunn/Kontakt+NAV/Relatert+informasjon/arbeids-og-velferdsdirektoratet-kontorinformasjon)
