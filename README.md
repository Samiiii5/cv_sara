# CV - Sara Gonzague Gnamien Elafissou

CV statique en HTML/CSS pur, en une page A4, prêt à exporter en PDF.

## Aperçu

Ouvrir `index.html` dans un navigateur (double-clic, ou `open index.html` / `xdg-open index.html`).

## Export en PDF

1. Ouvrir `index.html` dans Chrome/Edge.
2. `Ctrl+P` (ou `Cmd+P` sur Mac) → Imprimer.
3. Destination : "Enregistrer en PDF".
4. Format papier : A4, marges : Aucune.

Le CSS contient déjà les règles `@page` nécessaires pour que le rendu occupe exactement une page A4 sans marges.

## Photo de profil

Déposer la photo dans `assets/photo.jpg`. Si le fichier est absent, un avatar silhouette s'affiche automatiquement à sa place.

## Structure

- `index.html` — contenu du CV
- `style.css` — mise en page et style (2 colonnes : bandeau bleu marine à gauche, contenu à droite)
- `assets/` — emplacement de la photo de profil
