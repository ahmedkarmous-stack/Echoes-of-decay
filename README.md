# 🎮 ECHOES OF DECAY — Enhanced Survival Experience

![Cover](cover.png)

---

## 📖 Description

**Echoes of Decay** est un jeu de survie post-apocalyptique en vue de dessus, inspiré de l'univers de *The Last of Us*. Plongez dans un monde dévasté par une infection fongique, explorez des bâtiments abandonnés, collectez des ressources, fabriquez des objets de survie, et affrontez des hordes d'infectés de plus en plus dangereux.

Le jeu fonctionne directement dans votre navigateur — aucune installation requise.

---

## 🚀 Lancement

1. Placez les fichiers `echoes_of_decay_final.html` et `cover.png` dans le **même dossier**
2. Ouvrez `echoes_of_decay_final.html` dans votre navigateur (Chrome, Firefox, Edge recommandés)
3. Profitez de l'intro cinématique, puis cliquez pour commencer

> **Note** : L'image `cover.png` est utilisée pour l'écran d'ouverture cinématique et le menu principal. Sans elle, le jeu fonctionne mais sans l'arrière-plan visuel.

---

## 🎮 Contrôles

| Touche | Action |
|--------|--------|
| `Z Q S D` ou `W A S D` | Se déplacer |
| `SHIFT` | Courir (consomme la stamina) |
| `CTRL` | S'accroupir (mode furtif) |
| `ESPACE` ou `Clic gauche` | Attaquer au corps à corps |
| `E` | Interagir (ramasser, parler, se reposer) |
| `F` | Utiliser l'objet sélectionné |
| `G` | Lancer un Cocktail Molotov |
| `T` | Activer/Désactiver la torche |
| `C` | Ouvrir le menu de Fabrication |
| `K` | Ouvrir l'arbre de Compétences |
| `M` | Ouvrir la Carte complète |
| `1-9, 0` | Sélectionner un emplacement d'inventaire |
| `ESC` | Fermer les menus |

---

## 🎯 Fonctionnalités

### Survie complète
- **Santé** — Diminue quand vous subissez des dégâts. Soignable avec Medkits, Bandages, ou aux feux de camp
- **Stamina** — Se consomme en courant, se régénère au repos
- **Faim** — Diminue progressivement. Manger de la nourriture pour la restaurer. À zéro, vous perdez de la santé
- **Soif** — Diminue plus vite que la faim. Buvez de l'eau régulièrement

### Monde ouvert procédural
- Carte de **100×80 tiles** générée aléatoirement à chaque partie
- **6 types de bâtiments** : Maisons, Hôpitaux, Magasins, Entrepôts, Garages, Bunkers
- Routes, rivières, forêts, herbes hautes
- Arbres vivants et morts avec animations de balancement

### Cycle jour/nuit
- Horloge en temps réel (accéléré)
- La nuit, les ennemis sont plus agressifs et détectent plus loin
- Torche activable pour éclairer votre chemin
- Éclairage dynamique autour du joueur et des feux de camp

### 4 Types d'ennemis

| Type | PV | Vitesse | Dégâts | Particularité |
|------|-----|---------|--------|---------------|
| **Infecté** | 25 | Moyenne | 8 | Ennemi de base |
| **Runner** | 20 | Très rapide | 12 | Plus rapide la nuit |
| **Brute** | 80 | Lent | 25 | Tank résistant |
| **Bloater** | 150 | Très lent | 35 | Boss avec champignons |

Les ennemis deviennent **plus forts chaque jour** (PV, vitesse, dégâts augmentent).

### Système de furtivité
- **S'accroupir** (`CTRL`) réduit votre profil de détection de 40%
- **Herbes hautes** réduisent le bruit de 50%
- **Indicateur de furtivité** en temps réel : CACHÉ / DISCRET / REPÉRÉ
- **Cercle de bruit** visible autour du joueur
- **Éliminations furtives** infligent **×3 dégâts** + bonus XP

### Fabrication (Crafting)

| Recette | Ingrédients | Effet |
|---------|-------------|-------|
| Bandage | 2 Tissu + 1 Herbes | Soigne 25 PV |
| Medkit | 3 Tissu + 2 Herbes + 1 Pièces | Soigne 50 PV |
| Cocktail Molotov | 1 Tissu + 2 Pièces | Dégâts de zone + feu |
| Munitions ×5 | 3 Pièces | 5 balles |
| Réparer Couteau | 2 Pièces | Restaure la durabilité |
| Repas cuisiné | 2 Nourriture + 1 Herbes | Restaure faim + soigne |

### Arbre de compétences

| Compétence | Max | Effet par niveau |
|------------|-----|------------------|
| ❤️ Vitalité | 5 | +20 PV max |
| ⚡ Endurance | 5 | +20 Stamina max |
| 👁️ Furtivité | 5 | -15% détection ennemie |
| ⚔️ Combat | 5 | +20% dégâts |
| 🎒 Fouilleur | 3 | +25% chance de loot double |
| 🫀 Métabolisme | 3 | Faim/Soif -20% plus lente |
| 🔨 Artisanat | 3 | Recettes avancées |
| 🏕️ Survie | 3 | Régénération santé passive |

Gagnez 1 point de compétence à chaque montée de niveau.

### Système de quêtes

| Quête | Objectif | Récompense XP |
|-------|----------|---------------|
| Survivre 3 jours | Endurer 3 cycles | 50 XP |
| Éliminer 10 infectés | 10 kills | 80 XP |
| Collectionneur | 20 ressources | 60 XP |
| Artisan | 5 fabrications | 70 XP |
| Chasseur de brutes | 3 brutes/bloaters | 100 XP |
| Explorateur | 10 bâtiments visités | 90 XP |

### Météo dynamique
- ☀️ **Clair** — Conditions normales
- 🌧️ **Pluie** — Effet visuel de pluie
- ⛈️ **Tempête** — Pluie intense + éclairs
- 🌫️ **Brouillard** — Visibilité réduite

### PNJ Survivants
- **4 PNJ amicaux** disséminés sur la carte (Léa, Marc, Zoé, Omar)
- Système d'**échange de ressources** unique par PNJ
- Marqués en vert sur la minimap

### Autres mécaniques
- **Pièges à ours** cachés (visibles si proche ou compétence Furtivité)
- **Durabilité du couteau** — se dégrade à l'usage, réparable
- **Cocktails Molotov** — dégâts de zone persistants, enflamment les ennemis
- **Loot sur les ennemis** — chance de drop à la mort
- **Taches de sang** persistantes
- **Respawn de ressources** chaque nouveau jour
- **Minimap** circulaire en temps réel
- **Carte complète** (`M`) avec positions des ennemis, PNJ, feux de camp

---

## 🎚️ Modes de difficulté

| Mode | Ennemis | Dégâts reçus | Description |
|------|---------|--------------|-------------|
| **Normal** | 18 | ×1.0 | Pour découvrir le jeu |
| **Difficile** | 28 | ×1.5 | Pour les survivants expérimentés |
| **Cauchemar** | 40 | ×2.0 | Survie extrême — chaque erreur est fatale |

---

## 🏗️ Architecture technique

- **Moteur** : Canvas 2D natif (HTML5)
- **Rendu** : ~60 FPS avec culling par viewport
- **Carte** : Génération procédurale par bruit (pseudo-Perlin)
- **IA ennemis** : Machine à états (idle → chase) avec détection par bruit + distance
- **Éclairage** : Système jour/nuit avec composite operations
- **Météo** : Système de particules + overlays dynamiques
- **Sauvegarde** : Aucune (roguelike — chaque mort est définitive)
- **Dépendances** : Aucune — fichier HTML unique autonome
- **Compatibilité** : Chrome 80+, Firefox 75+, Edge 80+, Safari 14+

---

## 📂 Fichiers

```
📁 echoes_of_decay/
├── echoes_of_decay_final.html   ← Fichier principal du jeu
├── cover.png                     ← Image de couverture (intro + menu)
└── README.md                     ← Ce fichier
```

---

## 🎨 Crédits

- **Développement** : Généré avec Claude (Anthropic)
- **Design UI/UX** : Interface inspirée des jeux de survie AAA
- **Typographies** : Bebas Neue, Special Elite, Inter (Google Fonts)

---

## 📝 Notes de version

### V2.0 — Enhanced Edition
- Intro cinématique avec image de couverture
- Système de faim et soif
- Système de furtivité complet
- Système de crafting (6 recettes)
- Arbre de compétences (8 skills)
- 4 types d'ennemis (+ Runners et Bloaters)
- Météo dynamique (pluie, tempête, brouillard)
- PNJ avec système d'échange
- Pièges à ours
- Cocktails Molotov
- Système de quêtes
- Mode Cauchemar
- Carte élargie (100×80)

### V1.0 — Original
- Gameplay de base
- Cycle jour/nuit
- 2 types d'ennemis
- Inventaire simple
- Minimap

---

**Bonne survie, et souvenez-vous : dans ce monde, la confiance est un luxe.**
