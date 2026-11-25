# Blindage Lab

Bac à sable balistique en **3D temps réel** : testez armes, blindages et explosifs sur des mannequins physiques, dans dix environnements.

**Jouer :** ouvrez la page GitHub Pages de ce dépôt (Settings → Pages affiche l'adresse).

## Installer sur iPhone ou Android

1. Ouvrez l'adresse du jeu dans **Safari** (iPhone) ou **Chrome** (Android).
2. iPhone : bouton **Partager** → **Sur l'écran d'accueil**. Android : menu ⋮ → **Installer l'application**.
3. Le jeu s'ouvre en plein écran avec son icône et fonctionne **hors connexion**. Tenez le téléphone à l'horizontale.

## Mode 3D (nouveau)

Dans le menu principal, choisissez **Mode 3D** : vous vous déplacez librement à la première personne dans un stand de tir couvert ou sur un terrain extérieur.

| Ordinateur | Action |
|---|---|
| Clic dans la scène | Prendre la souris |
| ZQSD / WASD | Se déplacer (Maj : courir, Espace : sauter, C : s'accroupir) |
| Souris · clic gauche | Viser · tirer ou utiliser l'objet en main |
| Clic droit ou V | Viser avec l'arme (zoom, lunette) |
| G · E | Lancer une grenade · placer le personnage choisi |
| 1 à 8 · molette · Q | Changer d'arme ou d'objet (inventaire) |
| L | Allumer / éteindre le laser de visée |
| M · R | Arsenal · recommencer la carte |

Chaque arme ou objet pris dans l'arsenal s'ajoute à l'**inventaire** (8 emplacements, en bas de l'écran) ; touchez une case pour changer, appui long pour la retirer.

Sur iPhone : joystick à gauche pour avancer, glissez à droite pour regarder, boutons **FEU**, **VISER**, **SAUT**, **GRENADE** et **+** (mannequin).

## Labo d'impact (dégâts simulés grain par grain)

Menu → **Labo d'impact**, ou le bouton « Coupe » en 3D. La cible est vue en coupe : chaque grain de matière a sa densité, sa rigidité, sa limite élastique et sa résistance. Les liaisons plient, chauffent puis cassent. On voit la pénétration, les ricochets, l'écaillage, les éclats, la céramique qui se brise, le métal qui s'ouvre en pétales, la chair déchirée, et les explosifs (charge creuse, blindage réactif).

## Commandes

| Touche | Action |
|---|---|
| M | Arsenal (armes, personnages, équipement, cartes) |
| Échap | Menu principal |
| Espace | Pause |
| S | Ralenti |
| H | Mode cinéma |
| 1 à 6 | Objets récents |

Sur téléphone, tout se fait au doigt : bouton **Catalogue** en bas, toucher pour tirer, glisser pour viser.

## Technique

- Un seul fichier `index.html` : physique 2D (Verlet) et rendu 3D Three.js r170 (licence MIT) intégré.
- Éclairage physique, ombres, halo, occlusion ambiante, brume ; qualité adaptée automatiquement à l'appareil, repli en 2D si besoin.
- `manifest.webmanifest` et `sw.js` rendent le jeu installable et utilisable hors connexion.
