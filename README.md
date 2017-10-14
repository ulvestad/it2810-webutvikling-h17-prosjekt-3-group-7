# it2810-webutvikling-h17-prosjekt-3-group-7
IT2810 Prosjekt 3

Prosjektet vårt er splittet i to ulike repoer. Du finner web-appen i [it2810-webutvikling-h17-prosjekt-3-group-7-web](https://github.com/IT2810/it2810-webutvikling-h17-prosjekt-3-group-7-web) og mobil-appen i [it2810-webutvikling-h17-prosjekt-3-group-7-native](https://github.com/IT2810/it2810-webutvikling-h17-prosjekt-3-group-7-native).

Dette repositoriet er kun en samleside for å samle de to repositoriene. Du finner dem som [submoduler]() her, men for nyeste versjon anbefaler vi å benytte lenkne over.

For å klone repoet med submodulene må man bruke `--recursive`-valget til `git clone`. Man kan også laste ned submodulene i paralell med `-j2`.

```
git clone --recursive -j2 git@github.com:IT2810/it2810-webutvikling-h17-prosjekt-3-group-7.git
```

Har man alt klonet repoet kan man oppdatere submodulene slik:

```
git submodule update --recursive --remote
```
