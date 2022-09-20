---
title: "Fiche : Markup Systems and the Future of Scholarly Text Processins"
date: 2022-07-12T09:55:57-04:00
draft: false
type: lectures
---

## Résumé

Les auteurs, J.H. Coombs, A. H. Renear et S. J. DeRose, propose dans cet article de 1987 une apologie des langages de balisage pour l'écriture savante en contexte numérique. Dès cette époque, le conflit entre traitement de texte _versus_ éditeur de texte met en avant les principaux reproches fait aux outils de traitement de texte : l'absence d'une sémantisation des écritures, la non-intéropérabilité des formats propriétaires et la non-pérennité des documents. 

### Citation

> In the end, it should be clear that descriptive markup is not just the best approach of the competing markup systems; it is the best imaginable approach.

### Résumé des parties et mise en perspective

En 1987 les spécifications cadres des langages de balisages ne sont pas encore établies, excepté celle du SGML (_Standard Generalized Markup Language_) qui voit le jour en 1986 soit peu de temps avant la parution de l'article étudié. Pourtant, alors que ce ne sont que les prémisses des technologies de balisages du texte, l'article soulève des enjeux qui, 35 ans plus tard, sont toujours d'actualité. Les questions liées à l'interopérabilité des textes savants (au sein de leur chaine éditoriale et des processus de diffusion), à la sémantisation explicite des contenus, qu'il s'agisse d'une lecture destiné à des robots ou des êtres humain, et la pérennité des documents, surtout lorsqu'ils sont encodés dans des formats propriétaires, sont toujours aussi urgentes à traiter. 
Écrire en contexte numérique ne s'apparente pas du tout à l'écriture sur papier, il ne s'agit pas de reproduire les fonctionnalitées offertes par le papier sur un ordinateur mais de conquérir ce nouvel environnement en exploitant l'ensemble des fonctionnalités de celui-ci et donc d'ajouter une valeur à l'écriture numérique qui, dès lors, se distingue de l'écriture papier. 
Or, ce que nous dit cet article, c'est que l'écriture via un outil de traitement de texte n'apporte rien de nouveau en dehors du changement de support et du rendement amélioré, la capacité à "faire plus vite". 
Ce postulat amène les auteurs à penser ce que pourrait être une écriture augmentée par l'environnement numérique ; il jette leur dévolue sur les technologies de balisage du texte.
Celles-ci offrent plusieurs avantages, à commencer par une hiérarchisation explicite des informations. Par exemple, les niveaux de titre ne sont plus indiqués par une mise en page personnelle mais par une balise (<h1> en HTML) décrivant un titre de niveau 1. Il n'y a plus besoin d'opération mentale de comparaison des mises en page pour que le lecteur comprenne à quel niveau d'information il a affaire. C'est la différence mise en avant dans les types de marqueurs proposés, entre des balises de présentation (invisible comme le saut de ligne) et les balises descriptives (marqueurs dans le texte).
Aussi le type de langage de balisage conseillé est le descriptif : il répond également aux enjeux d'interoperabilité (une portabilité étendue) et de pérennité. En effet, ce dernier relève du texte brut. Quel que soit le format ou le logiciel utilisé pour le lire, le texte brut sera traitable plus facilement qu'un texte comportant une couche de mise en page. De plus, la maintenance requise pour ce type de document est très faible, réduisant par la même occasion les coûts pécuniers et humains liés à cette dernière.
En nous projetant au début du 21e siècle, des langages de balisages légers voient le jour pour répondre justement aux enjeux d'écriture en environnement numérique. Toutefois ils ne répondent pas complètement aux enjeux de l'écriture savante, alors des initiatives comme l'éditeur de texte Stylo tentent d'y répondre.
Stylo, un éditeur développé à la Chaire de recherche du Canada sur les écritures numériques, agrège des technologies telles que Markdown, BibTeX et YAML pour permettre à l'auteur d'avoir tous les outils nécessaires intégrés dans une seule interface.
Trois décennies après la parution de ce papier, certains laboratoires, comme l'exemple qui vient d'être mentionné, ont pris en compte les recommandations faites et les ont même dépassés. Il ne s'agit plus seulement d'écrire selon les modalitées numériques mais également de spécifier et réaliser les besoins des chercheurs, plus fins et précis que le balisage du texte, dans des environnements ouverts à l'ensemble de la communauté scientifique (et au-delà).