# Ny Mac 🎉

Gratulerer med ny mac!

Det første du må gjøre er å åpne **Terminal.app. **Uansett om du føler deg, eller ikke føler deg som en teknolog eller utvikler er det veldig greit å sette dette opp en gang for alle. Om du plutselig er nødt til å kjøre en nettside lokalt, eller trenger å ta noe ned eller dytte noe opp til GitHub er greit å ha dette minimale på plass. Det blir også enklere for andre å hjelpe deg med problemer som eventuelt måtte oppstå.

Les gjerne på intranett om hvordan du [skal sikre macen](https://intranett.netliferesearch.com/it/sikre-laptop) og [hvilke apper og verktøy vi bruker](https://intranett.netliferesearch.com/it/verktoy-og-apper-vi-bruker).

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

**Restart Terminal.app for sikkerhets skyld.**

## Programmer du trenger

Du kan søke etter hvilket som helst program med

```
brew cask search søkeord
```

Med disse linja kan vi installere en del programmer du trolig trenger. **Fjern fra lista apper du ikke ønsker å ha med.**

```
brew cask install chrome opera firefox harvest backblaze google-drive slack 1password
```

Fjern de kode-editorene du ikke vil ha

```
brew cask install atom sublime-text visual-studio-code
```

Vil du ha utvikler-versjon av nettleserne?

```
brew cask install google-chrome-canary opera-developer firefoxdeveloperedition safari-technology-preview
```

Vil du lage animert gif skjermdump?

```
brew cask install licecap
```

Har du en designer i magen? Obs: for noen av disse appene må du ha lisens

```
brew cask install sketch adobe-creative-cloud
```

Vil du gjøre git, men fra et GUI?

```
brew cask install github-desktop tower gitup
```

### Installere 1Password

Sjekk [intranettet.](https://intranett.netliferesearch.com/it/passord)

