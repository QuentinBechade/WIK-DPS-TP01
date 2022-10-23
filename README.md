Pour installer le projet :

> cd DevOps
> npm install
> npx tsc
> node build/index.js

Le programme retourne :
    - les headers au format JSON quand il y a une requete HTTP GET sur /ping
    - 404 si autre chose que GET /ping
    -505 si erreur inconnue
