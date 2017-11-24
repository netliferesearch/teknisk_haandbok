# Drift i Netlife



## Feilsøking

### Treg database
Hvordan feilsøke at databasen er treg.
Om databasen er treg kan du vurdere å oppgradere databasen (link til tiltak)


## Tiltak

### Oppgradere database

For å oppgradere Jaws databasen på Heroku fra en shared til en private database så må du først laste ned en kopi av databasen og så laste opp kopien til den nye databasen.
det gjør du på følgende måte:

```
mysqldump -h oldhostname -u oldusername olddb-name > dump.sql
mysql -h newhostname -u newusername newdb-name < dump.sql
```
