# Installatie

```git clone git@github.com:Amsterdam/openstad-component-forms.git```

of

```npm i git+ssh://git@github.com:Amsterdam/openstad-component-forms.git```

## Build

'npm run build' herschrijft de files in /dist

### Auto build

Maak een file `.git/hooks/pre-commit` met als inhoud

```
#!/bin/sh

npm run build
```

## Gebruik

Deze module is nog helemaal niet bruikbaar. Het idee is om er een groot deel van de form functionaliteiten in te stoppen.

Op dit moment zitten er alleen een paar input types in.

Die worden al wel gebruikt, door de Keuzewijzer.