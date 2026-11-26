# Étude de cas 12 — Plantes médicinales et signes de la ménopause

**Domaine** : ethnopharmacologie, statistiques descriptives  
**Outils** : R 4.5.3 (`readxl`, `dplyr`)

## Question posée

Quelles plantes, parties de plantes et modes de préparation sont utilisés par les enquêtés pour gérer les signes de la ménopause, et comment les symptômes se répartissent-ils par catégorie clinique ?

## Données

170 questionnaires anonymisés, importés depuis Excel. Données brutes non publiées.

## Démarche statistique

1. Importation (`readxl`) et nettoyage (`dplyr`).
2. Regroupement des réponses à choix multiples en catégories cliniques thématiques.
3. Analyse descriptive des fréquences (âge de survenue, symptômes, plantes, parties utilisées, modes de préparation et d'administration, durée d'usage).

## Résultats

- L'âge moyen déclaré d'apparition des premiers signes est d'environ 46 ans, avec une variation principalement entre 40 et 52 ans.
- Les troubles vasomoteurs (20,23 %), du sommeil et la fatigue (19,58 %) et les douleurs musculaires (17,62 %) sont les signes les plus cités.
- Les feuilles sont la partie la plus utilisée (56,63 %), devant les racines (15,06 %) ; la sève et les fleurs sont marginales (< 1 %).
- La décoction (51,85 %) et l'infusion (31,11 %) dominent ; la voie orale est utilisée par 90,15 % des répondants.
- 54,69 % des utilisateurs poursuivent l'usage jusqu'à satisfaction des symptômes.

*Tableaux détaillés non publiés ici.*

## Interprétation

Le regroupement thématique des réponses multiples permet de produire des **indicateurs de pratique** exploitables, tout en conservant la traçabilité des catégories cliniques. Il facilite la sélection des plantes à étudier en pharmacologie.
