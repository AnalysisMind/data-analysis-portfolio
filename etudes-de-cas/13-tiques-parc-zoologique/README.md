# Étude de cas 13 — Diversité des tiques en parc zoologique et périphérie

**Domaine** : écologie, biodiversité, épidémiologie  
**Outils** : R, indices de diversité et de similarité

## Question posée

Quelles espèces de tiques sont présentes le long de deux axes dans un parc et sa périphérie, et comment leur abondance, leur sex-ratio et leur diversité varient-elles selon les sites et les saisons ?

## Données

Collectes sur quatre sites (deux axes, parc/périphérie), avec effectifs, espèces, stades de développement et saison. Données confidentielles.

## Démarche statistique

1. Description des variables qualitatives par effectifs, fréquences et intervalles de confiance exacts de Clopper-Pearson (IC 95 %).
2. Richesse spécifique (S), abondance relative, indice de Shannon-Wiener (H') et équitabilité de Piélou (J').
3. Indices de similarité de Sørensen et de dissimilarité de Bray-Curtis.
4. Rarefaction de la richesse pour standardiser l'effort d'échantillonnage.
5. Comparaison des distributions par tests statistiques et analyse des sex-ratios.

## Résultats

- Quatre espèces d'importance vétérinaire et zoonotique identifiées, présentes sur les deux axes mais en proportions significativement différentes (p < 0,0001).
- La richesse spécifique est constante (S = 4) et l'indice de Shannon varie de 1,069 à 1,215 : diversité élevée et équilibrée.
- Sørensen = 1,000 pour toutes les paires de sites : mêmes espèces partout, sans espèce exclusive.
- Bray-Curtis varie de 0,139 à 0,265 : similarité de composition malgré des abondances différentes.
- Deux profils de sex-ratio s'opposent (p < 0,001) : prédominance femelle chez certaines espèces, mâle chez d'autres.

*Limites : aucune capture en saison sèche et effectifs réduits en périphérie.*

## Interprétation

L'analyse distingue clairement **composition** (identique) et **structure des peuplements** (abondances et sex-ratios différents). Elle illustre l'usage combiné des indices de diversité, de rarefaction et de similarité en écologie.
