# Installere ting man trenger til utviklermiljø

git: versjonshistorikkhåndtering, eller, måten vi lagrer, versjonerer og deler kode på i Netlife Research

```
brew install git nvm heroku composer
```

#### Installere ting man trenger for [Craft-prosjekt](https://github.com/netliferesearch/craft-starter#global-dependencies-for-the-starter-pack). Ta en linje av gangen.

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
nvm install v6 # eller v5, v4 osv.
```

For å bruke en versjon av node du har installert

```
nvm use v6
```

### Installere docker

Docker er hendig.

## Koble deg til GitHub via SSH

kommer

## Koble deg til Heroku

kommer

