---
layout: post
type:   post
title:  L'État de l'art - 1ère partie

status: published

toc:
  - { text : Pourquoi ?, link : "#pourquoi" }
  - { text : Quels gains ?, link : "#gain" }
  - { text : Quels délais ?, link : "#délai" }

summary:
    "Ce billet présente une méthodologie d'analyse pour le démarrage du
    projet. Il s'agit de formaliser les réponses à deux questions
    fondamentales : Pourquoi avons-nous besoin d'un nouveau framework et que
    gagnerait-on à utiliser un framework moderne ?"

---

## Pourquoi avons-nous besoin d'un nouveau framework ? {#pourquoi}

La première chose à faire avant d'analyser les outils existants est de
formaliser la réponse à la question précédente. Ce projet est-il né d'un
constat bien identifié, d'un problème bien défini ou bien d'une volonté de
modernisation, d'une intuition collective ?

Nous avons ainsi identifié plusieurs problèmes que nous rencontrons
actuellement.

Par ordre de priorité :

- Notre framework n'est pas assez sécurisé
- Il n'est pas assez efficace.
  Le temps de conception/développement est trop long
- La courbe d'apprentissage n'est pas satisfaisante
- Il est difficile d'écrire des tests et de les automatiser
- Pas d'identification à un outil connu
- Il n'est pas assez structuré et modulaire


## Que gagnerait-on à utiliser un framework moderne ? {#gain}

Plusieurs axes d'analyses sont possibles, mais cette méthode propose de
considérer chaque axe d'un point de vue opérationnel en se basant sur des
réalisations concrètes du Phare.


### Étudier la similarité {#similarité}

Il s'agit d'analyser un échantillon de réalisation et de construire une
matrice des fonctionnalités clés et des problèmes survenus sur chacun de ces
projets.

Nous avons choisi de construire l'échantillon en choisissant les trois ou
quatre projets les plus importants par an sur les cinq dernières années.
Cet échantillon réprésente donc entre 15 et 20 projets et leur analyse doit
préférablement se conduire avec le chef de projet et éventuellement le
déveleppeur principal correspondant.

À partir de la matrice ainsi construite, nous allons déterminer des
regroupements de fonctionnalités similaires. L'objectif est d'observer ces
regroupements pour en tirer des conclusions et des pistes sur la structure
de **Faros**. Un nombre de regroupement faible indique une grande similarité
entre nos projets, à l'inverse un nombre élevé indique une faible similarité.


### Étudier la modularité {#modularité}

À partir de l'analyse précédente nous pouvons, pour chaque regroupement,
essayer d'estimer le gain de temps que l'on pourrait obtenir en améliorant
la ré-utilisation des développements réalisés.

L'objectif est de déterminer l'influence d'un développement modulaire sur le
temps de réalisation de nos projets.


### Analyser le gain de la modernité {#modernité}

Une autre piste d'amélioration de la performance est d'essayer d'estimer le
gain apporté lors d'une réalisation, indépendemment des autres projets.

Des idées de points à analyser :

- création et modification du schéma de donnée
- capacité d'évolution du projet
- traduction dans une langue étrangère
- création et sécurisation de formulaire
- ...


## Les délais {#délai}

Répondre à la première question est relativement simple et rapide, cela nous
à pris environ 2 heures de discussions avec Vincent Caillaud (Directeur
Technique) et Hervé Cartron (Responsable de la production). Les réponses
sont souvent connus à l'avance, la difficulté est de les formaliser et
éventuellement les priorisés.

La deuxième réponse nécessite une étude approfondie des réalisations, nous
en sommes au démarrage de l'étude de la similarité. Pour cette étude nous
avons estimer environ 20h/h d'analyse pour deux personnes.

