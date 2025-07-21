Pages pour une campagne Kingmaker.
## Personnages joueurs (dataviewjs)
```dataviewjs
const pages = dv.pages('#Personnage/Joueur');

dv.table(['Nom'], pages.map(p => [p.file.link]));
```
## Personnages joueurs (dataview)
```dataview
TABLE WITHOUT ID file.link as "Nom"
FROM #Personnage/Joueur
```
