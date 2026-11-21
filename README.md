# Roue Chromatique d'Atelier (RYB) v4.0

[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-Soutenir-orange?style=for-the-badge&logo=buy-me-a-coffee&logoColor=white)](https://buymeacoffee.com/Bloow85)
[![Statut](https://img.shields.io/badge/Version-4.0-blue.svg)](https://bloow85.github.io/roue-chromatique/)

Outil interactif reproduisant la roue chromatique double-disque traditionnelle d'atelier, conçu pour les peintres de figurines, modélistes et créateurs visuels.

Contrairement aux écrans qui fonctionnent par addition de lumière (RVB), la peinture physique suit une logique de synthèse soustractive inspirée du cercle RYB (*Red - Yellow - Blue* / Rouge - Jaune - Bleu). L'application aide à choisir des harmonies, doser les mélanges, anticiper l'OSL et analyser des photos de référence directement dans le navigateur.

---

## Nouveautés & Fonctionnalités Clés (v4.0)

### 1. Disque Rotatif & Base de Pots Dynamique (JSON)
- **Palette rotative 12 secteurs :** Tournez le disque central au glisser ou cliquez directement sur un quartier / les boutons pas-à-pas.
- **Correspondances multi-marques (61 pots intégrés par défaut) :** Recherche des teintes proches selon la distance perceptuelle Redmean parmi **Citadel**, **Vallejo / Prince August**, **The Army Painter** et **AK Interactive**.
- **Base personnalisable :** Importez un fichier `peintures_db.json` local, synchronisez une URL JSON ou exportez votre catalogue actuel.

### 2. Harmonies Visuelles & Neutralisation
- **Accords automatiques :** Complémentaire (180°), Opposé divisé (*Split*), Triade (120°), Tétrade (90°) et Analogue (30°).
- **4 Déclinaisons :** Teinte pure, éclaircie (+ blanc), rompue (+ gris) et assombrie (+ noir).
- **Neutralisation soustractive :** Mélangez une teinte avec son opposée pour assombrir et désaturer sans passer par un noir pur.
- **Ambiance globale :** Ajustez la saturation et la luminosité de la roue pour simuler des rendus sombres (*Grimdark*) ou plus clairs.

### 3. Simulation Optique & OSL (*Object Source Lighting*)
- **Réaction pigment / lumière :** Aperçu sur sphère et pastilles de rendu selon la source lumineuse choisie (*Soleil*, *Flamme*, *Plasma Vert*, *Cyan Magic*, *Alarme*).
- **Aide à l'application :** Repères sur les zones d'ombre, de demi-teinte, de glacis et de rehauts.

### 4. Photo de Référence, Zoom x4, Déplacement & Loupe 1 px
- **Zoom ciblé jusqu'à x4 :** Molette de souris centrée sous le pointeur (et pincement à deux doigts sur écran tactile).
- **Déplacement libre (*Pan & Drag*) :** Glissez sur l'image pour parcourir les zones agrandies sans perdre le cadrage ; un clic court sans glissement prélève la couleur à la pipette.
- **Loupe à réticule circulaire :** Agrandissement au survol avec viseur circulaire et repère central de 1 pixel pour cibler les petits détails.
- **Outils rapides :** Passage en **N&B** pour juger les valeurs, **Reset Zoom**, **Caler roue** sur la couleur sondée et **Changer** de photo.

### 5. Assistant IA & Fiche de Recette (API Gemini)
- **Lecture de l'image :** Extraction des teintes dominantes (cliquables pour caler la roue) et analyse de la lumière.
- **Recette structurée en 4 phases :** *Base*, *Ombrage/Lavis*, *Glacis* et *Rehauts* selon le style (*Tabletop*, *Grimdark*, *Exposition*, *NMM*) et une précision optionnelle, en s'appuyant sur les pots de la base active.
- **Copie en un clic :** Récupération rapide de la fiche complète dans le presse-papiers.

---

## Démarrage Rapide & Configuration

### 1. Ouvrir l'outil
Accédez directement à [https://bloow85.github.io/roue-chromatique/](https://bloow85.github.io/roue-chromatique/) dans votre navigateur de bureau[cite: 1]. Les fonctions chromatiques, la roue, l'OSL, la loupe et la base intégrée fonctionnent sans configuration préalable.

### 2. Configurer l'analyse IA Gemini (optionnel)
La clé et le modèle sont enregistrés localement dans votre navigateur (`localStorage`) :
1. Cliquez sur **`API Gemini : À configurer`** en haut de la page.
2. Saisissez votre clé API Google AI Studio et choisissez le modèle souhaité (`gemini-3.8-flash` par défaut).
3. Validez avec **Enregistrer**.

### 3. Charger ou personnaliser la base de pots JSON (optionnel)
1. Cliquez sur **`Base pots`** en haut de la page (ou sur `Gérer base`).
2. Importez un fichier `peintures_db.json` ou saisissez l'URL d'un JSON compatible, puis cliquez sur **Sync**.
3. Vous pouvez aussi cliquer sur **Exporter JSON** pour sauvegarder ou éditer la structure des pots (`brand`, `range`, `name`, `ref`, `hex`).

---

## Rappels Théoriques Rapides
- **Primaires / Secondaires / Tertiaires :** Les 3 primaires RYB (Rouge, Jaune, Bleu) génèrent les secondaires (Orange, Vert, Violet), puis les tertiaires intermédiaires.
- **Contraste & équilibre :** Les harmonies complémentaires dynamisent un point focal, tandis que les harmonies analogues favorisent des transitions plus douces.

---

## Propriété Intellectuelle & Droits d'Auteur

(c) 2026 Marc BRONKAERT (bloow85). Tous droits réservés.

Usage personnel, pédagogique et d'atelier non-commercial autorisé. Toute reproduction, modification non autorisée, redistribution ou exploitation commerciale sans accord écrit préalable de l'auteur est interdite.
