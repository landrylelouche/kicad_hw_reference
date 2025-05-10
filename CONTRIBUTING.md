# 🤝 Contribuer au projet KiCad Hardware Blocks

Merci de votre intérêt pour contribuer à ce référentiel open source !

## 🧭 Objectif

Ce dépôt a pour but de rassembler des blocs de conception électroniques (MCU, capteurs, SOM, actionneurs, etc.) libres et réutilisables sous KiCad EDA. Chaque contribution renforce l’écosystème open hardware.

---

## ✅ Ce que vous pouvez contribuer :

- Nouveaux blocs de conception complets (schéma + PCB)
- Amélioration des blocs existants
- Documentation (README, fiches techniques, guides d’utilisation)
- Correction de bugs dans les fichiers sources
- Scripts ou outils d’automatisation utiles

---

## 🛠️ Format attendu pour un bloc

Chaque bloc doit être placé dans un dossier `blocks/NOM_DU_BLOC/` et inclure :

- `schematic.kicad_sch`
- `layout.kicad_pcb`
- `bom.csv` (avec références fabricants)
- `doc/README.md` (présentation, brochage, remarques d’intégration)
- (facultatif) `outputs/` (fichiers Gerber/Drill)

---

## 📌 Règles de base

- Utilisez **KiCad 7.x ou supérieur**
- Privilégiez des composants **facilement disponibles**
- Respectez la structure des dossiers
- Documentez les choix techniques dans `README.md`
- Faites une Pull Request claire, avec un titre explicite

---

## 🧪 Tester votre contribution

Avant soumission :
- Ouvrir les fichiers `.kicad_sch` et `.kicad_pcb` sans erreur
- Vérifier l’absence de DRC/Electrical Rule violations
- Vérifier l’orthographe dans la documentation

---

## 📝 Comment contribuer

1. Forkez ce dépôt
2. Créez une branche avec un nom explicite (`feature/new-sensor-block`)
3. Commitez vos fichiers avec des messages clairs
4. Ouvrez une **Pull Request** vers la branche `main`

Merci pour votre contribution au hardware libre ! 💪
