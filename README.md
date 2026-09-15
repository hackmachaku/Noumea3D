# 🌴 Nouméa 3D · Stylized Low-Poly Island Environment

Environnement 3D procédural immersif de la presqu'île de Nouméa et de son lagon corallien (Nouvelle-Calédonie), inspiré de l'esthétique stylisée **Minipoly (Unreal Engine)**.

🚀 **Démo en ligne (GitHub Pages)** : [https://hackmachaku.github.io/Noumea3D/](https://hackmachaku.github.io/Noumea3D/)

---

## ✨ Points Forts & Fonctionnalités

* **100 % Autonome et Hors-ligne** : fichier HTML unique sans aucune dépendance externe (moteur Three.js r169 inliné, géométries procédurales, textures et shaders intégrés).
* **Îlots Coralliens 3D Stylisés Minipoly** :
  * Dunes de sable doré en relief 3D facetté entourées de platiers coralliens turquoise peu profonds.
  * **Îlot Canard** : ponton d'accostage, bateau-taxi amarré, 4 farés traditionnels, transats, barque en bois échouée et coffre aux trésors.
  * **Îlot Maître** : caye corallienne de 330 m avec alignement de **10 farés sur pilotis (overwater bungalows)** le long d'une passerelle sur l'eau.
  * **Îlot Amédée** : récif au large avec jetée en bois de 72 m et le mythique **Phare Amédée** (tour blanche de 42 m avec coupole rouge vermillon).
  * Nuages cumulus low-poly cotonneux flottant au-dessus des îles.
* **Physique Réaliste des Vagues (Ondes de Gerstner)** :
  * Modèle hydrodynamique trochoïdal à 4 trains d'ondes (alizés, houle croisée, clapot et vaguelettes).
  * Crêtes pincées à arêtes vives et **moutons d'écume blanche** générés dynamiquement en pleine mer sur les zones à forte cambrure.
* **Flottaison Hydrodynamique 6 Points & Sillages en V** :
  * Échantillonnage de surface en 6 points sous les coques (heave, pitch, roll en phase avec la houle).
  * Sillages en V blancs écume traînant derrière les navires en mouvement.
  * Trajectoires océaniques en eau profonde évitant plages et récifs.
* **Circulation Routière Bidirectionnelle Réaliste** :
  * Deux voies opposées avec croisement naturel des véhicules par la droite.
  * Diversité de véhicules calédoniens : pickups tout-terrain à benne ouverte, voitures de police (gyrophares bleus), camions de pompiers (échelles et gyrophares rouges), bus jaunes et berlines.
  * Système anti-collision (distance de sécurité) et **feux tricolores fonctionnels** avec arrêt réaliste au feu rouge.
* **Hippodrome Henry Milliard & Public Animé** :
  * Piste ovale avec lices blanches et chevaux pur-sangs montés par leurs jockeys au galop.
  * Grande tribune couverte à 5 gradins abritant **~60 spectateurs animés** qui se lèvent, sautent et font la ola lors du sprint final.
* **Dynamique Organique des Végétaux** :
  * Flexion élastique des troncs depuis le sol sous l'effet des alizés.
  * Couronnes de palmes 100 % solidaires du sommet fléchi avec bruissement haute fréquence des feuilles.

---

## 🎮 Contrôles & Navigation

| Action | Contrôle Souris / Touch |
| :--- | :--- |
| **Pivoter (Orbite)** | Clic gauche enfoncé + glisser / Glisser à 1 doigt |
| **Zoomer / Dézoomer** | Molette de la souris / Pincement à 2 doigts |
| **Déplacer la caméra (Pan)** | Clic droit enfoncé + glisser / Glisser à 2 doigts |
| **Changer d'ambiance** | Bouton `🌙 Nuit` / `☀️ Jour` |
| **Vues rapides préconfigurées** | Boutons du panneau latéral : `⛲ Place & Fontaine`, `🛣️ Grande Avenue`, `🏖️ Plage Minipoly`, `🔎 Fontaine Détail`, `🏝️ Îlots & Phare`, `🏇 Hippodrome`, `⚓ Port`, `⛰️ Ouen Toro`, `🌐 Panorama` |

---

## ⚙️ Performances

* **Draw Calls GPU** : ~75 (budget <= 85)
* **Polygones rendus** : ~537k triangles
* **Framerate** : 60 FPS constants
* **Poids** : ~925 Ko tout-en-un