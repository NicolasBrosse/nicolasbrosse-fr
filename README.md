## Introduction
Ce dépot contenait le code du site https://nicolasbrosse.fr

Le site lui-même était constitué de pages statiques générées par le [framework Hugo](https://gohugo.io/).
Il s'agissait ici de pratiquer à la fois Hugo et git.

## Sous modules
Le thème du site était considéré comme un sous-module git ([submodule](https://git-scm.com/docs/git-submodule)) puisque clonable depuis [son repo sur Github](https://github.com/aerohub/hugrid).

Ainsi, lorsque le thème était mis à jour par son auteur principal, il suffisait de l'upgrader sans que celui-ci ne vienne perturber le fonctionnement de git localement.

Hugo permet de surcharger les thèmes importés. Il n'est donc pas nécessaire d'éditer les fichiers source du thème importé.

## Archivage
Après différents changement d'hébergement du site et du code associé, ce dépôt n'est plus valide/actif et a été archivé sur Github (mis en lecture seule, fonctionnalités réduites au minimum...) le 24 février 2025.
