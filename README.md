# it2810-webutvikling-h17-prosjekt-3-group-7

Prosjektet vårt er splittet i to ulike repoer. Du finner web-appen i [it2810-webutvikling-h17-prosjekt-3-group-7-web](https://github.com/IT2810/it2810-webutvikling-h17-prosjekt-3-group-7-web) og mobil-appen i [it2810-webutvikling-h17-prosjekt-3-group-7-native](https://github.com/IT2810/it2810-webutvikling-h17-prosjekt-3-group-7-native).

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

## /nateive 
