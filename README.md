# Roue Chromatique d'Atelier (RYB) v3.4

[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-Soutenir-orange?style=for-the-badge&logo=buy-me-a-coffee&logoColor=white)](https://buymeacoffee.com/Bloow85)
[![Statut](https://img.shields.io/badge/Version-3.4-blue.svg)](https://bloow85.github.io/roue-chromatique/)

Outil interactif reproduisant la roue chromatique double-disque traditionnelle d'atelier, concu sur mesure pour les peintres de figurines, modelistes et createurs visuels.

Contrairement aux ecrans qui fonctionnent par addition de lumiere (RVB), la peinture physique fonctionne par synthese soustractive a partir du cercle traditionnel RYB (Red - Yellow - Blue / Rouge - Jaune - Bleu). Cet outil simule le comportement optique des pigments reels directement dans votre navigateur.

---

## Fonctionnalites Principales (v3.4)

### 1. Disque Rotatif & Equivalences Pots de Peinture
- Palette physique 12 secteurs : Navigation fluide avec disque rotatif interactif ou boutons pas-a-pas.
- Correspondances directes pour figurinistes : Pour chaque teinte selectionnee, l'application donne immediatement les references exactes des pots equivalents du marche :
  - Citadel (ex: Mephiston Red, Macragge Blue, Moot Green)
  - Vallejo / Prince August (gammes Model Color et Game Color)
  - The Army Painter (gamme Warpaints)

### 2. Harmonies Visuelles & Neutralisation
- Calcul automatique des accords : Complementaire (180 degres), Oppose divise (Split-Complementary), Triade (120 degres), Tetrade (90 degres) et Analogue (30 degres).
- 4 Declinaisons d'Atelier : Teinte pure, eclaircie (+ blanc), rompue (+ gris) et assombrie (+ noir).
- Simulateur de neutralisation : Dosage precis de melange soustractif pour creer des ombres naturelles et des gris chromatiques sans salir au noir pur.
- Reglage d'ambiance d'atelier : Sliders de saturation et de luminosite pour adapter toute la roue aux ambiances sombres (Grimdark) ou pastel.

### 3. Simulation Optique & OSL (Object Source Lighting)
- Moteur optique physique : Simulation du comportement d'un faisceau lumineux colore frappant un pigment de base (absorption et reflexion).
- Presets de lumieres d'ambiance : Soleil blanc, Flamme orange, Plasma vert, Cyan magique, Alarme rouge.
- Rendu sur sphere 3D : Visualisation en direct du point focal, de la demi-teinte et du reflet speculaire avec conseils d'application (glacis, rehauts, ombres).

### 4. Analyseur de Reference & Loupe Haute Precision
- Import d'image de reference : Glissez-deposez n'importe quelle photo de figurine ou concept art.
- Loupe dynamique au pixel : Zoom au survol avec reticule de visee pour isoler les details minuscules.
- Zoom molette et mode N&B : Analyse instantanee des contrastes de valeurs sans distraction de couleur.
- Pipette intelligente & calage : Analyse de la valeur lumineuse de la zone ciblee (ombre, demi-teinte, lumiere) avec proposition du pot de peinture le plus proche et bouton pour recaler immediatement la roue sur cette couleur.

---

## Guide Theorique pour Debutants

### 1. La Hierarchie des Couleurs
- Primaires (Rouge, Jaune, Bleu) : Couleurs fondamentales pures, impossibles a obtenir par melange.
- Secondaires (Orange, Vert, Violet) : Obtenues en melangeant deux primaires a parts egales.
- Tertiaires (Rouge-Orange, Jaune-Vert, etc.) : Melange d'une primaire avec sa secondaire voisine.

### 2. Les Regles d'Harmonies
- Complementaire (180 degres) : Contraste maximal. Ideal pour faire ressortir un point focal (yeux, gemmes, armes energetiques).
- Complementaire adjacente : Contraste marque mais plus doux et nuance pour l'oeil.
- Triade (120 degres) : Trois teintes equidistantes pour une composition riche et equilibree.
- Tetrade (90 degres) : Deux paires complementaires, a manipuler en gardant une couleur tres dominante.
- Analogue (30 degres) : Teintes voisines pour un degrade naturel et une ambiance feutree.

---

## Utilisation
- En ligne : Utilisez directement l'application hebergee sur GitHub Pages : https://bloow85.github.io/roue-chromatique/
- Copie rapide : Cliquez sur n'importe quel echantillon de couleur pour copier son code hexadecimal dans le presse-papiers.
- 100 % autonome : Fonctionne sur PC, tablette et smartphone, sans installation et sans connexion internet requise une fois la page chargee.

---

## Propriete Intellectuelle & Droits d'Auteur

(c) 2026 Marc BRONKAERT (bloow85). Tous droits reserves.

Cette application, son code source, son interface graphique et ses algorithmes sont la propriete exclusive de l'auteur.  
- Usage autorise : Utilisation personnelle, pedagogique et d'atelier non-commerciale.  
- Restrictions : Toute reproduction, modification non autorisee, redistribution ou exploitation commerciale sans accord ecrit prealable est formellement interdite.
