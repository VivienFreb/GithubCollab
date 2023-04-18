# Exercice de résolution de conflits

## Contexte
Ceci est un projet fictif d'une entreprise. Une page de login a été développée par votre collègue. Celui-ci vous a demandé de rajouter la connexion via les réseaux sociaux (Google, LinkedIn...). Vous avez donc créé une branche séparée pour faire votre fonctionnalité appelée "adding-social". Vous avez également ajouté le code nécessaire pour ajouter cette partie et vous avez également effectué les commandes git nécessaires (add, commit...). Vous devez désormais appliquer les fonctionnalités de cette fonctionnalité sur cette branche. Vous avez essayé la chose suivante :
- Retourner sur la branche "master" via `git checkout master`
- Fusionner les deux branches via `git merge adding-social`
Malheureusement, il y a eu quelques changements depuis le developpement de votre fonctionnalité et il y a désormais un conflit.

## Objectif
Dans un contexte d'entreprise, cela correspondrait à une page où plusieurs fonctionnalités sont développées par plusieurs personnes: il est possible lorsque vous avez fini d'intégrer votre fonctionnalité sans pour autant effacer celles des autres.

## Instructions
Des modifications ont été apportées au fichier que vous avez modifié sur votre branche. Il y a donc une branche "master" où il y a du contenu que vous n'avez pas et votre branche "adding-social" où vous avez développé votre fonctionnalité. Régler le conflit et garder votre fonctionnalité **ET** les modifications de la branche master. 

## Bonus
L'erreur est humaine, cherchez également comment revenir à l'état d'avant votre résolution, cela peut toujours être utile.