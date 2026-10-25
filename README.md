# Piston Punch 🥊

**Un beat'em up arcade jouable directement dans le navigateur**, sans installation ni dépendance externe.

🎮 **Jouer en ligne :** https://optimum68.github.io/pistonpunchv2/

## Le jeu
Incarnez Piston, un combattant mécanique au gant surpuissant. Enchaînez les coups, esquivez les ennemis et survivez aux vagues dans une arène industrielle néon.

- Combat arcade avec coups rapides et uppercuts
- Ennemis, vagues, score, combo et barre de vie
- Effets visuels, particules et décor animé
- Commandes clavier et boutons tactiles pour mobile
- Graphismes dessinés en Canvas : aucun asset externe à télécharger

## Commandes
| Action | Commande |
| --- | --- |
| Déplacement | WASD ou flèches |
| Coup de poing | J ou Espace |
| Uppercut spécial | K |
| Pause | P |
| Recommencer après un KO | Entrée |

Sur mobile, utilisez le pavé directionnel et les boutons d'attaque à l'écran.

## Lancer en local
Ouvrez simplement `index.html` dans un navigateur moderne. Aucun build ni serveur n'est nécessaire.

## Publication GitHub Pages
Le workflow GitHub Actions `.github/workflows/pages.yml` publie le site automatiquement à chaque push sur `main`. Dans **Settings → Pages**, choisissez **GitHub Actions** comme source de déploiement si cela n'est pas déjà configuré.

Après le déploiement, le jeu sera disponible à : https://optimum68.github.io/pistonpunchv2/

## Assets et licences
Le personnage, l'arène et les effets sont dessinés en code dans Canvas. Aucun asset tiers ni police externe n'est utilisé dans cette version.

## Technologies
HTML5 · CSS · JavaScript · Canvas 2D · GitHub Pages
