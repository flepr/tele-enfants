# Télé Enfants

Petite web app familiale qui dit à qui c'est le tour d'avoir la télé : Gabriel, Clément ou Austin.

## La règle

On additionne le jour du mois et l'heure, puis on divise par 3 :

- reste 1 : Gabriel
- reste 2 : Clément
- reste 0 : Austin

Exemple : le 10 à 13h, 10 + 13 = 23, 23 = 7 × 3 + 2, donc c'est Clément.

## Ce que fait l'appli

- Affiche qui a la télé en ce moment, et combien de temps il reste.
- Donne le prochain créneau de chacun des deux autres frères.
- Permet de chercher n'importe quelle date et heure, avec la journée entière en un coup d'œil.
- S'installe sur l'écran d'accueil d'un téléphone et marche hors connexion.

## Installer sur un téléphone

- **iPhone (Safari)** : ouvrir le site, bouton Partager, puis « Sur l'écran d'accueil ».
- **Android (Chrome)** : ouvrir le site, menu ⋮, puis « Installer l'application » ou « Ajouter à l'écran d'accueil ».

## Technique

Un seul fichier `index.html`, sans dépendance, publié avec GitHub Pages. `sw.js` met le site en cache pour l'usage hors ligne ; changer la constante `CACHE` à chaque nouvelle version.
