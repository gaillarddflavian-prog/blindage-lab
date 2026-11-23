# Blindage Lab

Bac à sable balistique en **3D temps réel** : testez armes, blindages et explosifs sur des mannequins physiques, dans dix environnements.

**Jouer :** ouvrez la page GitHub Pages de ce dépôt (Settings → Pages affiche l'adresse).

## Installer sur iPhone ou Android

1. Ouvrez l'adresse du jeu dans **Safari** (iPhone) ou **Chrome** (Android).
2. iPhone : bouton **Partager** → **Sur l'écran d'accueil**. Android : menu ⋮ → **Installer l'application**.
3. Le jeu s'ouvre en plein écran avec son icône et fonctionne **hors connexion**. Tenez le téléphone à l'horizontale.

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
