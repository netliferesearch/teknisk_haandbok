# Installere ting man trenger til utviklermiljø

## Kjapp huskeliste

* [ ] Installert \`brew\`
* [ ] Har tilgang på organisasjonen Netlife Research på GitHub
* [ ] Har tilgang på Heroku
* [ ] Har installert git
* [ ] Har installert nvm
* [ ] Har installert heroku
* [ ] Har installert composer

## Grunnpakken

```
brew install git heroku composer nvm
```

Kan være lurt å restarte Terminal.app etter du er ferdig med å installere disse.

* **git**: versjonshistorikkhåndtering, eller, måten vi lagrer, versjonerer og deler kode på i Netlife Research.
* **nvm: n**ode **v**ersion **m**anager, eller, gjør det enkelt å holde node.js-oppdatert.
* **node: n**ode bruker vi for å kjøre javascript utenfor nettleseren. Med node kommer også **npm** \(**n**ode** p**ackage** m**anager\) som først og fremst bruker til å installere pakker og avhengigheter til frontend. [Les mer om npm her](https://www.impressivewebs.com/npm-for-beginners-a-guide-for-front-end-developers/?ref=webdesignernews.com).
* **heroku: **heroku er skyen hvor vi drifter, bygger og hoster det meste vi har på nettet.
* **composer:** er en _package manager_ for php, vi bruker det for eksempel i Craft-prosjekter.

### Du er ikke ferdig med nvm og node helt ennå

For at nvm skal virke må du sørge for å ha fulgt disse instruksjonene. Forutsetter at du kjører i Bash og ikke et annet shell, om du kjører i et annet shell virker det som du vet hva du holder på med, og trenger ikke så mye mer forklaring. Eller hva?

```bash
echo "export NVM_DIR=~/.nvm\nsource $(brew --prefix nvm)/nvm.sh" >> ~/.bash_profile
```

### Installere ting man trenger for [Craft-prosjekt](https://github.com/netliferesearch/craft-starter#global-dependencies-for-the-starter-pack). Ta en linje av gangen.

```
brew tap homebrew/dupes
brew tap homebrew/versions
brew tap homebrew/homebrew-php
brew install php70 php70-mcrypt php70-imagick composer
brew link php70
```

Noen har fått litt problemer med en bildebehandlingsutvidelse som Craft bruker, det kan antagelivis fikses med denne linja.

```
brew uninstall imagemagick && brew install imagemagick@6 && brew link imagemagick@6 --force
```

### Installere node

Nå som du har nvm kan du installere og bytte mellom node-versjoner lett som en plett.

```
nvm install v6
```

For å bruke en versjon av node du har installert

```
nvm use v6
```

Om du vi sette en versjon som standard 

```
nvm use default v6
```

## Koble deg til GitHub via SSH

kommer

## Koble deg til Heroku

kommer

## Installere docker

kommer

