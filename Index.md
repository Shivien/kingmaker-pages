---
layout: default
title: Home
---
Pages pour une campagne Kingmaker.
## Personnages joueurs
```dataviewjs
const pages = dv.pages('#Personnage/Joueur');

dv.table(['Nom'], pages.map(p => [p.file.link]));
```
