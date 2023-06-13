# Supprimer des éléments à l'aide de splice()

Ok, nous avons donc appris à supprimer des éléments du début et de la fin des tableaux en utilisant `shift()` et `pop()`, 
mais que se passe-t-il si nous voulons supprimer un élément quelque part au milieu ? Ou supprimer plus d'un élément 
à la fois ? Eh bien, c'est là qu'intervient `splice()`. `splice()` nous permet de faire exactement cela : supprimer n'importe
quel nombre d'éléments consécutifs de n'importe où dans un tableau.

`splice()` peut prendre jusqu'à 3 paramètres, mais pour l'instant, nous allons nous concentrer uniquement sur les 2 premiers.
Les deux premiers paramètres de `splice()` sont des entiers qui représentent des index, ou des positions, d'éléments dans le 
tableau qui splice()est appelé. Et rappelez-vous, les tableaux sont indexés à zéro , donc pour indiquer le premier élément d'un 
tableau, nous utiliserions 0. splice()Le premier paramètre de représente l'index sur le tableau à partir duquel commencer à supprimer 
des éléments, tandis que le second paramètre indique le nombre d'éléments à supprimer. Par exemple:
