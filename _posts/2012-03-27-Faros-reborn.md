---
layout: post
type: post
title: "Faros reborn !"

status : "draft"

toc:
  - { text : Soyons efficace !, link : "#efficace" }
  - { text : Vers l'infini et au-delà !, link : "#infini" }
  - { text : La naissance de Faros, link : "#faros" }
  - { text : Mise en place du projet, link : "#mise_en_place" }

summary:
    Après bientôt neuf mois d'absence nous voici de retour. Beaucoup de choses se sont passés ces derniers mois : des décisions ont été prises et des actions ont été menées.

---

Avant d'entrée dans le vif du sujet, profitons de ce nouveau départ pour faire un court historique du projet.

## Soyons efficace ! {#efficace}

Le phare existe depuis plus de 10 ans et en une décennie la nature de nos
réalisations a changé. Les projets que nous réalisons sont de plus en plus
complexes, de plus en plus spécifiques, de plus en plus sur-mesure.

Cette évolution est la conséquence de l'orientation stratégique du Phare
vers la conception et le développement d'application métier de type
Extranet ou Intranet.

Le framework applicatif maison, développé en interne à une époque où il n'en
existait pas, est suffisamment efficace pour avoir permit au Phare de se
distinguer par sa compétence, sa réactivité et son adaptabilité. Son
efficacité tient essentiellement à la pratique d'un développement strict et
rigoureux et à l'application de recettes éprouvées prêtes à l'emploi.

Le manque de documentation et de convention des pratiques de programmation/conception, la complexité toujours croissante de nos projets, l'arrivé de nouvelles techniques de programmation (POO, Design Pattern) et l l'agrandissement de l'équipe de développement font que notre framework est depuis quelques années a bout de souffle, de plus en plus contraignant et donc de moins en moins efficace.

C'est donc logiquement qu'il nous a fallu nous pencher sur la refonte de notre framework.


## Vers l'infini et au-delà ! {#infini}

En 2011, entre les nombreux CMS et les frameworks existant, il nous parait
inconcevable de faire notre outil dans notre coin.

L'utilisation d'un CMS a été écartée dès le début de nos réflexions. Même si
certains de ces projets affiche des fonctionnalités intéressantes, nos
objectifs de souplesse, réactivité et efficacité nous conduises
naturellement vers l'eldorado des frameworks PHP.

La décision de la refonte a été prise entre 2010 et 2011. Dans le monde des
framework PHP il s'agissait d'une période délicate. Avant 2010, plusieurs
frameworks étaient en vogue. Entre Zend Framework, CodeIgniter, EZPublish,
symfony et bien d'autre il y avait de quoi choisir. Puis est arrivé la
version 5.3 de PHP apportant plusieurs fonctionnalités très intéressantes
mais nécessitant de casser la compatibilité avec les versions précédentes.

Quelques mois après l'arrivé de cette version majeure plusieurs projets PHP
ont annoncé leurs volontés de concevoir une version _NextGen_ de leurs
framework. Le projet Symfony a été un des premiers frameworks professionnel à
annoncé Symfony 2.0 vers le début de l'année 2010. Dans la foulé, Zend à
également annoncé le démarrage de son nouvel outil Zend Framework 2.

Partagé entre l'excitation d'attendre de nouveaux outils utilisant les dernières technologies et l'inquiétude de passer à coté des frameworks déjà en place et bien éprouvé nous avons alors préféré retarder notre projet de refonte en attendant d'y voir plus clair.


## La naissance de Faros {#faros}

Comme il est plus facile de parler d'un projet quand il porte un nom, j'ai
voulu baptisé notre projet. Le nom est venu de l'île de Pharos, où fut érigé
le phare le plus connu du monde, celui d'Alexandrie. Pour une entreprise
appelée Le Phare, cela reste dans le ton. Après une petite transformation
typographique voici donc **Faros** notre nouveau framework.

Après une fin d'année 2011 passé sous la pression d'un projet devant sortir (très) rapidement, voila que l'on me libère à nouveau du temps pour me consacrer presque essentiellement au projet Faros. Du coup j'ai essayé de ne pas en perdre et de m'y mettre sérieusement !


## Mise en place du projet {#mise_en_place}

Après le PHPTour 2011 à Lille, il nous paraissant évident que notre futur outil se baserait sur un framework existant de nouvelle génération. Et c'est [fin janvier 2012](https://twitter.com/dhalsimfr/statuses/163944291276824576) que la décision finale à été prise. Nous utiliserons Symfony2 !

Nous avons également décidé de mener cette refonte en parallèle avec un projet client. Il s'agit de la future e-boutique [Ponroy](http://www.ponroy.com/), premier développement nouvelle-génération du Phare !

La suite est assez logique, nous avons commencé par suivre une formation pour être rapidement efficace avec le framework (merci [KnpLabs](http://knplabs.fr)).

La conception a démarré dans la foulée avec un premier jet de spécifications générales. Un groupe de travail interne s'est formé pour établir les spécifications de nos interfaces d'administrations. Et les premiers développements ont démarré pour se familiariser avec ce nouveau framework.

Le projet Faros va donc devenir un bundle symfony, le LephareFarosBundle. Quelle aventure !

## A venir !

La publication sur ce blog devrait reprendre un rythme plus soutenu. J'ai déjà plusieurs idées en tête. En vrac nous parlerons : d'interface d'admin, d'organisation de travail création/intégration/développement, d'environnement de développement, de github, de ..., <small>de ...</small>