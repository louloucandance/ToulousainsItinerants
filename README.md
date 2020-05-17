# Toulousains Itinerants
Projet de web sémantique de GUIRAUDET Denis, ORRIERE Matthieu et GENTILLET Louise

## Lancer le serveur
- Nécessite un serveur Fuseki à lancer avec la commande `fuseki-server --update`
- Importer le fichier `ontoCorrectSyntax.owl` dans le dossier `/ontologie` depuis l'interface Fuseki
- Le nom de notre dataset est `Web`

## Fonctionnement front
- Ouvrir le fichier `index.html` dans le dossier `/site`
- Depuis cette interface il est possible de voir si la page reçoit des informations de Fuseki avec le loader bleu: s'il devient vert c'est que cela fonctionne, s'il est rouge c'est qu'un problème a eu lieu
- Une fois le loader devenu vert, cliquer sur la fusée pour lancer l'importation des données depuis les différentes api, attendre 30 secondes et relancer la page
- Si la carte de france est plus verte et moins orange qu'avant c'est que le processus a fonctionnné
