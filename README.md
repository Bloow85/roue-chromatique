# Roue Chromatique d'Atelier (RYB) & Suite Figuriniste v4.3

[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-Soutenir-orange?style=for-the-badge&logo=buy-me-a-coffee&logoColor=white)](https://buymeacoffee.com/Bloow85)
[![Statut](https://img.shields.io/badge/Version-4.3-blue.svg)](https://bloow85.github.io/roue-chromatique/)

Outil interactif complet conçu pour les peintres de figurines, modélistes et créateurs visuels, réunissant une **roue chromatique double-disque traditionnelle d'atelier (RYB)** et une **Suite d'Atelier** (convertisseur multi-marques & calculateur de dilution aérographe/pinceau) directement dans le navigateur.

Contrairement aux écrans qui fonctionnent par addition de lumière (RVB), la peinture physique suit une logique de synthèse soustractive inspirée du cercle RYB (*Red - Yellow - Blue* / Rouge - Jaune - Bleu). L'application aide à choisir des harmonies, doser les mélanges et dilutions, anticiper l'OSL, convertir vos références entre marques et analyser des photos de référence sur PC, tablette ou smartphone.

---

## Nouveautés & Fonctionnalités Clés (v4.3)

### 1. Ergonomie d'Atelier, Aide Interactive & Navigation Tactile
- **Double espace de travail :** Basculez instantanément entre la **🎨 Roue Chromatique** et la **🖌️ Suite d'Atelier** depuis la barre de navigation supérieure.
- **Guide Pratique intégré (`❓ Aide`) :** Modale pédagogique expliquant l'usage des codes `#HEX`, les harmonies, l'OSL, la loupe 1 px et les dosages de dilution pour les débutants et non-graphistes.
- **7 boutons `?` contextuels :** Chaque module dispose d'un bouton d'aide tactile/cliquable affichant un encart explicatif directement dans sa carte.
- **Infobulles `#HEX` pédagogiques & copie rapide :** Touchez n'importe quelle pastille couleur pour copier son code `#HEX` exact dans le presse-papiers.
- **Interface responsive :** Conçue pour ordinateur, tablette et mobile avec zones tactiles élargies et contrôle gestuel.

### 2. Disque Rotatif RYB & Base de Pots Dynamique (JSON)
- **Palette rotative 12 secteurs :** Tournez le disque central au glisser (souris ou tactile) ou touchez directement un quartier / les boutons pas-à-pas.
- **Correspondances multi-marques :** Recherche des teintes proches selon la distance perceptuelle **Redmean + HSL** parmi **Citadel**, **Vallejo / Prince August**, **The Army Painter** et **AK Interactive**.
- **Base personnalisable :** Importez un fichier `peintures_db.json` local, synchronisez une URL JSON ou exportez votre catalogue actuel.

### 3. Harmonies Visuelles & Neutralisation Soustractive
- **Accords automatiques :** Complémentaire (180°), Opposé divisé (*Split*), Triade (120°), Tétrade (90°) et Analogue (30°).
- **4 Déclinaisons :** Teinte pure, éclaircie (+ blanc), rompue (+ gris) et assombrie (+ noir).
- **Neutralisation soustractive :** Mélangez une teinte avec son opposée pour assombrir et désaturer naturellement sans salir vos ombres au noir pur.
- **Ambiance globale :** Ajustez la saturation et la luminosité de la roue pour simuler des rendus sombres (*Grimdark*) ou pastel, avec mise à jour des pots conseillés en temps réel.

### 4. Simulation Optique & OSL (*Object Source Lighting*)
- **Réaction pigment / lumière :** Aperçu sur sphère 3D simulée et pastilles de rendu selon la source lumineuse choisie (*Soleil*, *Flamme*, *Plasma Vert*, *Cyan Magic*, *Alarme*).
- **Aide à l'application :** Repères sur les zones d'absorption, de glacis intermédiaire et de rehauts d'arête.

### 5. Photo de Référence, Zoom x4, Déplacement & Loupe 1 px
- **Zoom ciblé jusqu'à x4 :** Molette de souris centrée sous le pointeur et pincement à deux doigts sur écran tactile.
- **Déplacement libre (*Pan & Drag*) :** Glissez sur l'image pour parcourir les zones agrandies sans perdre le cadrage ; un clic/tap court sans glissement prélève la couleur à la pipette.
- **Loupe à réticule circulaire :** Agrandissement au survol avec viseur circulaire et repère central de **1 pixel** pour cibler les petits détails.
- **Outils rapides :** Passage en **N&B** pour juger les contrastes et valeurs, **Reset Zoom**, **Caler roue** sur la couleur sondée et **Changer** de photo.

### 6. Assistant IA & Fiche de Recette (API Gemini — Optionnel)
- **Lecture de l'image :** Extraction des teintes dominantes (cliquables pour caler la roue) et analyse de la lumière.
- **Recette structurée en 4 phases :** *Base*, *Ombrage/Lavis*, *Glacis* et *Rehauts* selon le style (*Tabletop*, *Grimdark*, *Exposition*, *NMM*) et une précision optionnelle, en s'appuyant sur les pots de la base active.
- **Copie en un clic :** Récupération rapide de la fiche complète dans le presse-papiers.

### 7. Suite d'Atelier : Convertisseur Multi-Marques (5 Marques)
- **Catalogue maître intégré :** **Vallejo**, **Citadel**, **AK Interactive**, **Army Painter (Fanatic)** et **Scale75** (teintes mates et métalliques).
- **Algorithme perceptuel Redmean + HSL :** Calcule le pourcentage de proximité visuelle dans les 4 autres marques en séparant automatiquement les peintures mates et métalliques.
- **Rebond & personnalisation :** Bouton **Cibler →** pour basculer d'un pot équivalent vers sa marque, recherche par nom/référence/`#HEX`, et import/export de catalogues `.json`.

### 8. Suite d'Atelier : Calculateur de Dilution (Aérographe & Pinceau)
- **Modes dédiés :** **Aérographe** (avec sélection du diamètre de buse : `0,2 mm`, `0,28 mm`, `0,35 mm`, `0,4 mm` et pression indicative en PSI / bar) ou **Pinceau**.
- **Usages & viscosités :** Aplat, Glacis/Filtre, Lavis/Ombrage, Effets/Dégradés fins ou Brossage à sec, ajustés selon la viscosité du pot (Acrylique standard, Épaisse/Dense, Métallique).
- **Dosage précis Peinture / Diluant / Retardateur :** Conversion automatique en gouttes et millilitres (`1 ml ≈ 20 gouttes`), barre visuelle des proportions, conseils d'établi et sauvegarde de **Mémos d'atelier** en local.

---

## Démarrage Rapide & Configuration

### 1. Ouvrir l'outil
Accédez directement à [https://bloow85.github.io/roue-chromatique/](https://bloow85.github.io/roue-chromatique/) dans votre navigateur (PC, tablette ou smartphone)[cite: 1]. La roue chromatique, l'OSL, la loupe, le convertisseur multi-marques, le calculateur de dilution et les bases intégrées fonctionnent sans aucune configuration préalable.

### 2. Configurer l'analyse IA Gemini (optionnel)
La clé et le modèle sont enregistrés uniquement en local dans votre navigateur (`localStorage`) :
1. Cliquez sur **`API Gemini : À configurer`** en haut de la page.
2. Saisissez votre clé API Google AI Studio et choisissez le modèle souhaité (`gemini-3.8-flash` par défaut).
3. Validez avec **Enregistrer**.

### 3. Charger ou personnaliser les bases de pots JSON (optionnel)
1. Cliquez sur **`Base pots`** en haut de la page (ou utilisez la barre d'import/export dans le **Convertisseur Multi-Marques**).
2. Importez un fichier `.json` local ou saisissez l'URL d'un JSON compatible, puis cliquez sur **Sync**.
3. Cliquez sur **Exporter JSON** à tout moment pour sauvegarder ou éditer la structure des pots (`brand`, `range`, `name`, `ref`, `hex`).

---

## Rappels Théoriques Rapides
- **Primaires / Secondaires / Tertiaires :** Les 3 primaires RYB (Rouge, Jaune, Bleu) génèrent les secondaires (Orange, Vert, Violet), puis les tertiaires intermédiaires.
- **Contraste & équilibre :** Les harmonies complémentaires dynamisent un point focal, tandis que les harmonies analogues favorisent des transitions plus douces.

---

## Propriété Intellectuelle & Droits d'Auteur

(c) 2026 Marc BRONKAERT (bloow85). Tous droits réservés.

Usage personnel, pédagogique et d'atelier non-commercial autorisé. Toute reproduction, modification non autorisée, redistribution ou exploitation commerciale sans accord écrit préalable de l'auteur est interdite.
