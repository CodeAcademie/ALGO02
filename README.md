# Découvrons les boucles

A partir d'un papier et d'un crayons découvrons l'algorithmie et les boucles. 
Un ensemble d'exercices est listé ci-dessous.

Le formateur choisis le thème, les élèves se penchent sur l'algorithme sur un papier. 
Ils doivent donc rédiger de l'algo, définir des variables mais aussi choisir les bonnes boucles !

Après le temps imparti, ils doivent débattre sur la meilleur solution. 

## Calculer un somme

Créer la fonction **somme(n)** retournant la somme de n éléments.

Exemple : 

 * somme(3) retourne 6
 * somme(5) retourne 15
 * somme(0) retourne 0


## Choix conditionnel 
Implémentons le robot **Q-BOT**, ce dernier analyse une phrase et détermine si cette phrase est une question, une affirmation ou une simple phrase. Pour ce faire, il analyse la question et à partir du symbole de ponctuation.
**Q-BOT** affichera donc soit "question", "affirmation" ou "phrase" et fonction de si la phrase se termine par un point, un point d'interrogation ou un point d'exclamation.

## Afficher un tableau contenant les apprenants de la Code Académie

Nous avons un tableau contenant les élèves de la Code Académie : 

$tab = ["Marcel DUPONT", "Jeanne POIROT", "Aissatou DEMA",  ...]

Nous aimerions automatiser la génération d'un tableau avant le format suivant : 

```html
<table>
	<tr>
		<td> Marcel DUPONT </td>
	</tr>
	<tr>
		<td>Jeanne POIROT</td>
	</tr>
	<tr>
		<td>Aissatou DEMA</td>
	</tr>
	...
</table>
```

## Afficher une liste de choix &lt; select &gt; contenant les 4 prochaines années

Au sein d'une page web, nous aimerions générer une liste de choix.
Cette liste de choix servira pour définir la date d'expiration d'une carte bleue. Elle doit donc afficher l'année actuelle ainsi que les 4 prochaines années.

Si vous êtes en l'an 2000, la liste affichera de 2000 à 2004.

## Jeu de la fourchette
On va demander à l'utilisateur de taper le nombre 47. Tant qu'il n'a pas tapé le nombre 47, on lui redemande le nombre. Le programme ne pourra s'arrêter que si l'utilisateur tape le nombre 47 (je sais, je sais, je suis diabolique) :)

## Générer un jeu de cartes
Nous aimerions générer un jeu de 32 cartes. Comment le feriez-vous ? 

## Factorielle
En mathématiques, la factorielle d'un entier naturel **n** est le produit des nombres entiers strictement positifs inférieurs ou égaux à **n**.

Cette opération est notée avec un point d'exclamation :

* n!

Par exemple : 

 * 3! = 3x2x1 = 6
 * 5! = 5x4x3x2x1 = 120 

Attention 0! = 1 

Créer la fonction factorielle(n)  

