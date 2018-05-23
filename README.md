## Introduction
Ce dépot contient le code du site https://nicolasbrosse.fr

Le site lui-même est constitué de pages statiques générées par le [framework Hugo](https://gohugo.io/).
Il s'agit ici de pratiquer à la fois Hugo et git.

## Sous modules
Le thème du site est considéré comme un sous-module git ([submodule](https://git-scm.com/docs/git-submodule)) puisque clonable depuis [son repo sur Github](https://github.com/aerohub/hugrid).

Ainsi, lorsque le thème sera mis à jour par son auteur principal, il suffira de l'upgrader sans que celui-ci ne vienne perturber le fonctionnement de git localement.

Hugo permet de surcharger les thèmes importés. Il n'est donc pas nécessaire d'éditer les fichiers source du thème importé.
