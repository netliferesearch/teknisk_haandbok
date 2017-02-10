# Ny Mac :tada:

Gratulerer med ny mac!

Det første du må gjøre er å åpne **Terminal.app.**

## Installere Homebrew og Cask

[Homebrew](http://brew.sh/) gjør det enkelt å installere CLI-verktøy, Homebrew Cask gjør det mulig å innstallere GUI-apper uten å måtte laste ned en DMG-fil e.l.

### Installere Homebrew

Kjør denne linja i terminal:

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

### Installere Cask

Når du har installert Homebrew og alt har gått bra, kan du installere Cask.

```
brew tap caskroom/cask
```

## Installere ting man trenger til utviklermiljø

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



