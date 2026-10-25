# Piston Punch V2 — Scrap Arena 🦾

Un jeu d'action arcade de survie jouable dans le navigateur, sur ordinateur et mobile.

**Jouer en ligne :** https://optimum68.github.io/pistonpunchv2/

## Le combat
- Survis à des vagues de robots ennemis qui deviennent plus difficiles.
- Enchaîne les coups pour monter ton combo et augmenter ton score.
- Utilise le dash pour esquiver ou traverser les ennemis.
- Déclenche l'onde **Ion Pulse** pour toucher les adversaires proches.
- Récupère les modules entre les vagues : dégâts, vitesse, réparation, blindage ou recharge ionique.
- Ramasse les kits de réparation lâchés par certains ennemis.

## Commandes

| Action | Clavier |
| --- | --- |
| Déplacement | WASD ou flèches |
| Coup de poing | Espace ou J |
| Dash | Maj ou K |
| Ion Pulse | L |
| Pause | P ou Échap |

Sur mobile, utilise le pavé directionnel et les boutons **DASH**, **PUNCH** et **ION**.

## Robot et animations
Le jeu charge `assets/piston-punch-sprite-atlas.svg`, un atlas transparent 6×6 contenant les états visuels **idle, walk, run, attack, jump et hurt/KO**. Le moteur Canvas choisit une ligne et fait défiler les images selon l'action. Si le chargement échoue, un robot de secours dessiné en Canvas reste disponible.

L'atlas est une adaptation vectorielle légère des éléments visuels du concept fourni (armure sombre, plaques orange, yeux et réacteur cyan), pas une extraction pixel-perfect de la planche originale.

## Lancer en local
Ouvre `index.html` dans un navigateur moderne. Les assets sont chargés depuis le dossier `assets/`.

## Publication GitHub Pages
Le workflow GitHub Actions `.github/workflows/pages.yml` publie automatiquement le site lors des mises à jour de `main`. Dans **Settings → Pages**, sélectionne **GitHub Actions** comme source de déploiement.

## Technologies
HTML5 · CSS · JavaScript · Canvas 2D · SVG · GitHub Pages
