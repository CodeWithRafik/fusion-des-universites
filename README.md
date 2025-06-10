# Projet de découverte
## Plateforme ETL de Gestion des Notes Étudiantes  
**Auteur : Rafik BOUDALIA**

---

## 🎓 Contexte

Début 2021, les universités de **Mufflins**, **Chichigneux** et **Grapencourt** ont fusionné pour former le **GRUT** (Groupement Régional des Universités Techniques), délivrant un **diplôme unique et commun**.

- **Université de Mufflins** : cursus complet avec cours techniques et non techniques.
- **Universités de Chichigneux & Grapencourt** : cursus orienté Web.
  - Cours techniques dispensés à Grapencourt.
  - Cours non techniques dispensés à Chichigneux.

Pour simplifier et accélérer la validation des diplômes, une **plateforme centralisée de gestion des notes** a été envisagée.

---

## 🎯 Objectif du Projet

Le projet consiste à développer une **plateforme ETL (Extract – Transform – Load)** permettant :

1. L’extraction et la normalisation des données de notes.
2. La transformation des données : calculs, traitements, moyennes.
3. Le chargement et l’affichage via une interface web pour les jurys.

---

## 📐 Règles de Gestion des Notes

À la suite de la crise sanitaire, les règles suivantes ont été définies :

- Notes comprises entre **0 et 100**.
- **Absences** notées avec la lettre `A` (non sanctionnées).
- Cours organisés en deux groupes :
  - **Techniques / Informatique** – Coefficient **2**
  - **Non techniques** – Coefficient **1**
- Moyenne générale :
  ```math
  (2 × moyenne_technique + moyenne_non_technique) / 3
