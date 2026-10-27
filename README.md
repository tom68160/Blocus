# Blocus

Jeu de société de placement de pièces pour 4 joueurs, jouable dans le navigateur.

## Jouer

Ouvre `index.html` dans ton navigateur. Aucune installation n'est nécessaire.

Pour le publier en ligne avec GitHub Pages, va dans **Settings → Pages**, choisis la branche `main` puis le dossier `/ (root)`.

## Règles

- Le plateau fait 20×20 cases. Il y a 4 couleurs (Bleu, Jaune, Rouge, Vert) et 21 pièces par joueur.
- La première pièce doit couvrir ton coin de départ.
- Chaque pièce suivante doit toucher une de tes pièces **par un coin**, et **jamais par un côté**. Les couleurs différentes peuvent se toucher librement.
- Quand tu ne peux plus poser de pièce, tu es bloqué.
- Score final : −1 par case restante, +15 si toutes tes pièces sont posées, +20 si la dernière pièce posée est le carré seul.

## Commandes

- Clique sur une pièce de ta réserve, survole le plateau pour la placer, puis clique pour la poser.
- **R** fait tourner la pièce, **F** la retourne, **Échap** annule la visée.
- Sur téléphone : touche une case pour viser, puis touche à nouveau pour poser.
- Le bouton « IA » / « Humain » à côté de chaque couleur permet de jouer à plusieurs sur le même écran. Le changement s'applique à la partie suivante.
