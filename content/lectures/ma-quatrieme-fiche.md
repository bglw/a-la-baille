---
title: "Fiche : From data mining to knowledge discovery in databases"
date: 2022-07-12T09:56:10-04:00
draft: false
type: lectures
---

## Résumé

À travers cet article de 1996, les auteurs souhaitent présenter une vue d'ensemble de ce champ d'application qu'est la découverte des connaissances dans les bases de données (_knowledge discovery in databases_ aka KDD) au moyen d'outils appartenant au domaine de l'informatique et de l'intelligence artificielle (_machine learning_, _data mining_, statistiques, etc.).

### Citation

> Data mining is a step in the KDD process that consists of applying data analysis and discovery algorithms that produce a particular enumeration of patterns (or models) over the data. 

### Résumé des parties

La première partie de l'article revient sur les fondamentaux d'une telle technologie : quels sont les besoins ? comment mettre en place le processus de transformation des données en connaissances ?
Le constat est le suivant : les technologies numériques produisent des millions de données et l'être humain n'a pas la capacité de le traiter "à la main". L'emploi de technologies dédiées à cette application devient nécessaire. Ces applications ont du succès dans plusieurs domaines comme le commerce au sens large ou encore ce qui relève de la santé.
Ensuite, les auteurs distinguent le KDD du 8machine learning8 en appuyant sur la dimension interdisciplinaire du KDD, et sur la prise en compte de l'ensemble du processus, de la découverte des données jusqu'au stockage de celles-ci et leur accessibilité.

Dans une seconde partie les auteurs détaillent les étapes qui composent le processus du KDD :
- Sélection des données
- Préprocessing
- Transformation des données
- Exploitation des données (_data mining_)
- Interprétation et évaluation

Le point important de ce processus est qu'il est __itératif__ : un modèle n'émerge pas tout seul ou lors du premier essai. Avant d'interpréter les données pour faire émerger des connaissances, il est nécessaire de répéter les premières étapes pour affiner le modèle au jeu de données. Une fois le modèle validé, il devient possible de réaliser les deux dernières étapes d'exploitation et d'interprétation.

Dans la partie suivante, les auteurs détaillent les méthodes de _data-mining_, il en existe plusieurs types, toutefois, il n'y a pas de critère pré-établi d'usage d'une méthode particulière à appliquer à un jeu de données particulier.

Les auteurs ouvrent en conclusion sur le potentiels du KDD dans divers champs, notamment l'analyse du langage naturel ou le développements d'agents intelligents ou la représentation des connaissances.

### Mise en perspective

Cet aperçu du KDD offert par Fayyad, Piatetsky-Shapiro et Smyth en 1996 pose les bases méthodologiques de ce qui est aujourd'hui largement répandu dans beaucoup de disciplines, celles nommées dans l'article mais aussi les sciences de l'information et de la communication, les sciences humaines et sociales, les lettres, etc.
Le point névralgique de cet article est à l'endroit de l'organisation des connaissances énoncé en conclusion. 
Les auteurs ont écrit : « Knowledge representation includes _ontologies_, new concepts for representing, storing, and accessing knowledge ».
À ce jour, nous pouvons interpréter ce rapport aux ontologies de deux manières.
Premièrement, chaque discipline développe une vision du monde se traduisant par des méthodes heuristiques et par une organisation des connaissances qui lui est propre. Il est donc nécessaire que le modèle développé dans le cadre du KDD soit conforme aux attentes épistémologiques énoncées par les acteurs de chaque champ disciplinaire. Pour être bref (le format des résumés est un peu court!), ce rapport aux algorithmes rappelle la théorie de l'éditorialisation telle qu'énoncée par Marcello Vitali-Rosati (à approfondir).
Deuxièmement, certaines références bibliographiques sont liées au _World Wide Web_ et, dans ce cas, le mot "ontologie" fait directement écho aux technologies du web sémantique qui pourtant n'ont été officiellement présentées qu'en 2001 ! Il y aurait donc une inspiration commune de l'organisation des connaissances sur de larges corpus de données, qu'il s'agisse de KDD ou du web. Cette modélisation des connaissances grâce aux ontologies est l'argument grâce auquel le KDD dépasse ce que nous entendons aujourd'hui par intelligence artificielle. Le modèle commun de l'IA repose sur le moissonnage et l'analyse de données en très grande quantité ; or, avec la vision du W3C un autre modèle de l'IA apparaît : celui des relations entre concepts (qui fonctionne par inférence). Le KDD montre que ces deux approches ne sont pas antagonistes mais qu'au contraire elles sont complémentaires. 
Nous pourrions faire des recherches appronfondies à ce sujet.

