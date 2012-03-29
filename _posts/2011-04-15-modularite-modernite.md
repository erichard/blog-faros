---
layout: post
type:   post
title:  Modularité & Modernité

status: published

toc:
  - { text : Les modules, link : "#modules" }
  - { text : La modernité, link : "#modern" }
  - { text : Conclusion, link : "#conclusion" }

summary:
    "Maintenant que la première étape est terminée, passons aux deux
    suivantes : l'analyse de la modularité et de la modernité."

---

## Les modules {#modules}

Un module est une fonctionnalité plutôt situé dans la couche basse de nos
applications. Ce sont des briques hautement ré-utilisables et très peu
spécifique à l'application qui va les utiliser. La liste des modules ci-
dessous n'est pas exaustive mais présente les modules sur lequels nous
estimons pouvoir gagner du temps avec l'arrivé du nouveau framework.

- Gestion de **formulaire**
- Gestion de **date**
- Génération de **document**
- Prise en charge du **multi-linguisme** et de la **localisation**
- Gestion de **media** (images et vidéos)
- Envoie de **mail** (texte et HTML)
- Moteur de **template**
- **Authentification** et **Autorisations**
- **Pagination** et liste triable
- **Contexte** et **session**
- Gestion de tâches (cron)

L'utilisation de ces modules est nécessairement facultative lors de la
réalisation de nos sites, sinon il ne s'agit plus de modules mais de
composants.


## La modernité {#modern}

Abordons maintenant les fonctionnalités clés et nécessaires à la réalisation
de nos projets. Voici la liste de ces fonctionnalités où on doit gagner du
temps avec le nouveau framework.

- Moteur de Ré-écriture d'URL
- Système de cache
- Gestion de la sécurité
- Gestion des erreurs et des logs
- Système d'accès aux Bases de données
- Gestion d'évènements
- Gestion de modules


## Conclusion {#conclusion}

Établir ces deux listes a été relativement simple mais ces deux étapes sont
nécessaires pour pouvoir établir une feuille de route pour la conception de
Faros. En plus de cela, ces listes nous servirons d'étalonnage pendant toute
la période de réalisation du projet.