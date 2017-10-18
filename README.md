# it2810-webutvikling-h17-prosjekt-3-group-7

Prosjektet vårt er splittet i to ulike repoer. React og React Native er skilt i de to mappene "web" og "app" i hovedprosjektet siden de utnytter forskjellige importerte komponenter, testmiljø og er i bunn og runn to forskjellige prosjekter som deler mye lik funksjonalitet. Vi har og valgt å bruke mappene "web" og "app" som to forskjellige repoer i Github på disse lenkene, slik at vi kan utnytte en mer effektiv måte å bruke Github arbeidsflyten vår.

- Vi har brukt create-react-app for å sette opp rammene til prosjektet 
- Vi har brukt Redux til å håndtere states (data)
- For å sørge for konsekvent formattering, som navngivning og indentering, har vi brukt ESLint
- All koden er skrevet i ES6, en nyere javascripsyntaks, som transpileres v.h.a. Babel 
- Vi har brukt styled components for å enklere kunne style elementene 
- Til automatisert testing har vi brukt Enzyme, Ava til automatisering av tester, og Travis til å kjøre testene våre. Vi har også brukt Coveralls til å automatisk sjekke test coveragen vår. 

Du finner web-appen i [it2810-webutvikling-h17-prosjekt-3-group-7-web](https://github.com/IT2810/it2810-webutvikling-h17-prosjekt-3-group-7-web) og mobil-appen i [it2810-webutvikling-h17-prosjekt-3-group-7-native](https://github.com/IT2810/it2810-webutvikling-h17-prosjekt-3-group-7-native).

Dette repositoriet er kun en samleside for å samle de to repositoriene. Du finner dem som [submoduler](https://chrisjean.com/git-submodules-adding-using-removing-and-updating/) her, men for nyeste versjon anbefaler vi å benytte lenkene over.

For å klone repoet med submodulene må man bruke `--recursive`-valget til `git clone`. Man kan også laste ned submodulene i paralell med `-j2`.

```
git clone --recursive -j2 https://github.com/IT2810/it2810-webutvikling-h17-prosjekt-3-group-7.git
```

Har man alt klonet repoet kan man oppdatere submodulene slik:

```
git submodule update --recursive --remote
```

For å gjøre ting enklere kan man lage et alias som både puller og oppdaterer submodulene:

```
git config alias.update '!git pull && git submodule update --init --recursive'
```

Da kan du bare skrive `git update`, og så puller og oppdaterer den submoduelene. Hurra 🎉 Om man vil ha aliaset til å gjelde for alle git-repoer kan man legge til `--global` etter `git config`.


# Simple setup på egen maskin  

Klone hele prosjeketet 
```
git clone --recursive -j2 git@github.com:IT2810/it2810-webutvikling-h17-prosjekt-3-group-7.git
```

## /web 
Endre sti til /web
Installer alle nødvendige pakker og dependecies 
```
yarn install 
```
Kjør programmet lokalt 
```
yarn start
```

## /native 
