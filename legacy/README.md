# ⚠️ legacy — données synthétiques, à ne pas citer comme résultat

Ce dossier contient la **première version** du projet (septembre 2026). Il est
conservé pour l'historique uniquement.

## Ce que contiennent ces fichiers

`alternances_france_2026.csv` — **1 500 lignes générées par programme.**
Ce n'est *pas* un relevé d'offres réelles. Les valeurs (métier, ville, salaire,
télétravail, durée) ont été tirées aléatoirement à partir de distributions
inspirées de tendances publiées par Indeed / Hellowork / Glassdoor.

Les cinq PNG (`graphe1`…`graphe5`) sont les graphiques issus de ce fichier.

## Pourquoi c'est en legacy

Aucune des conclusions tirées de ce dataset n'est vérifiable :

- les « salaires médians par métier » sont ceux du générateur, pas du marché ;
- la « part de Paris/IDF à 38 % » est un paramètre d'entrée, pas une mesure ;
- le nuage de mots des compétences reflète la liste codée en dur dans le script.

Un dataset synthétique peut servir à tester une chaîne de traitement. Il ne peut
pas servir à décrire un marché. Les chiffres de ce dossier ne doivent donc pas
être repris, ni dans le README principal, ni ailleurs.

## Ce qui l'a remplacé

L'analyse actuelle (`eda.ipynb`) porte sur des offres **réellement collectées**
par un pipeline de veille (LinkedIn, France Travail, La Bonne Alternance),
snapshot du 3 octobre 2026. Elle porte sur la **qualité et la couverture des
sources**, et non sur le marché — c'est un échantillon d'une recherche
personnelle, pas un échantillon représentatif.
