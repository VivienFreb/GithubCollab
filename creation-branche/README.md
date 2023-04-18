# Exercice de création de branche

## Contexte
Ceci est un projet fictif d'une entreprise. Une page de login a été développée par votre collègue. Celui-ci vous demande de rajouter la connexion via les réseaux sociaux (Google, LinkedIn...). 

## Objectif
Vous devez donc créer une branche séparée, nommée de façon à comprendre ce qui est travaillé. Sur cette branche, vous devrez ajouter le code permettant de se connecter via les réseaux sociaux.
Pour une question de facilité, vous utiliserez simplement ce code:

```HTML
<p class="w-100 text-center">&mdash; Or Sign In With &mdash;</p>
<div class="social d-flex text-center">
	<a href="#" class="px-2 py-2 mr-md-1 rounded"><span class="ion-logo-facebook mr-2"></span> Facebook</a>
	<a href="#" class="px-2 py-2 ml-md-1 rounded"><span class="ion-logo-twitter mr-2"></span> Twitter</a>
</div>
```
NB: Ce code est à placer juste après la fermeture de la balise `</form>`

Il faudra également effectuer les commandes git nécessaires (add, commit...).

## Instructions
Ajouter vos modifications sur une branche séparée. Il sera également possible de switch entre les plusieurs branches et de constater les changements (càd que la connexion via les réseaux sera visible sur la branche que vous aurez créée et elle ne sera pas présente sur la branche "master").

## Bonus
Il y a plusieurs arguments qui peuvent être utiles lors de la création d'une branche. Essayez d'en trouver quelques-un! 
(Exemple d'arguments pour la commande **ls** : ls **--all --escape** etc..)