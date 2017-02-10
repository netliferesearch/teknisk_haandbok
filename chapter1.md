# Ny Mac :tada:

Gratulerer med ny mac!

Det første du må gjøre er å åpne **Terminal.app. **Uansett om du føler deg, eller ikke føler deg som en teknolog eller utvikler er det veldig greit å sette dette opp en gang for alle. Om du plutselig er nødt til å kjøre en nettside lokalt, eller trenger å ta noe ned eller dytte noe opp til GitHub er greit å ha dette minimale på plass. Det blir også enklere for andre å hjelpe deg med problemer som eventuelt måtte oppstå.

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

## Programmer du antagelivis trenger

Med denne linja kan vi installere en del programmer du antagelivis trenger. Fjern fra lista det du ikke ønsker å ha med

```
brew cask install chrome opera firefox harvest backblaze google-drive slack
```

Fjern de kode-editorene du ikke vil ha

```
brew cask install atom sublime-text visual-studio-code
```

Vil du ha utvikler-versjon av nettleserne?

```
brew cask install google-chrome-canary opera-developer firefoxdeveloperedition safari-technology-preview
```

Har du en designer i magen? Obs: for noen av disse appene må du ha lisens

```
brew cask install sketch adobe-creative-cloud
```



