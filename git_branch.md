### git branch
Una rama en Git es simplemente un apuntador móvil apuntando a una de los commits.

### git branch --no-merged
Nos muestra cuáles ramas no han sido fusionadas a la rama actual.

### git branch --merged
Nos muestra las ramas que han sido fusionadas a la rama actual.


Puedo crear todas las ramas que quiera y/o necesite.

Las ramas nuevas que se crean apuntan al commit actual.

* `gir branch -D [nom_rama]`
elimina la rama aunque no este fucionada con la rama master

* `git branch --no-merged`
lista las ramas que no fueron fucionadas a la rama actual

* `git branch --merged`
lista las ramas fucionadas a la rama actual
