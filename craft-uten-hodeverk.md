# Craft uten hodeverk

## Kjapp huskeliste

* [ ] Har installert alle avhengigheter \(composer, npm\)
* [ ] Har laga en .env-fil med database-variabler
* [ ] Har laga en database i skyen, og gjerne en lokalt
* [ ] Har oppdatert herokuapp-urlen \(e.l\) i general.php og db.php

## Hvordan fungerer egentlig Craft?

* 📄 `general.php` 👈🏻 Her finner du de generelle innstillingene for Craft
* 📄 `db.php` 👈🏻  Her finner database-innstillingene for Craft, ofte lurt å la denne være \(om du ikke vet hva du gjør\)
* 📄 `.env-example` 👈🏻  Denne kopierer du i din lokale mappe til `.env`. Her henter db.php inn oppkoblingsinfo til databasen \(som er sensitiv informasjon\)
* 📁 `/templates`👈🏻 Her finner du sidemalene
* 📁 `/resources`👈🏻 Her finner du Sass og JavaScript filene som webpack bygger og legger i `/public`
* 📁 `/public`👈🏻 Stort sett kan du la denne være i fred, men av og til vil du fikse favicon e.l



