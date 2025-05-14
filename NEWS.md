# NEWS - Notice thermie

## 2025-05-14
### Ajouts
- Ajout d'explications manquantes de champs dans le fichier excel des stations
- Actualisation des structures de données suite à MAJ dans `aquatools` (`0.0.174`)
  * Ajout du champs `chmes_referentiel_temporel` dans les champs associés aux mesures
  * Ajout des champs `chsta_codehydro`, `chsta_codemeteofrance`, `chsta_infl_ant_type`, `chsta_infl_nappe` dans les champs associés aux stations

### Modifications
- Modification de la position des champs `chsta_codehydro`, `chsta_codemeteofrance`, `chsta_infl_ant_type`, `chsta_infl_nappe` dans le fichier excel des stations
- Renommage dans jeux de données `chronique_exemple`, `chronique_structure` et `chronique_structure_hors_bdd` de `suivi_structure` par `suivis_structure` pour harmonisation

### Corrections
- Corrections de la description du champs `chsta_infl_nappe` dans les champs des stations

## 2025-05-12
### Ajouts
- Ajout des champs `chsta_codehydro`, `chsta_codemeteofrance`, `chsta_infl_ant_type`, `chsta_infl_nappe` dans le fichier excel des stations

## 2024-10-07
### Ajouts
- Changement de pile

## 2023-11-17
### Ajouts
- Création d'un chapitre traitement
  * Jeu de données d'exemple
  * Importation des données

## 2022-12-22
### Ajouts
- Valorisation/Résultats/Acronymes : précision concernant `DateDEpisodesSupN` et `DateFEpisodesSupN` afin d'indiquer qu'on parle de l'épisode le plus tardif.
- Fiches atlas résultats : Précision du nombre maximal de caractères affichables au niveau des commentaires
