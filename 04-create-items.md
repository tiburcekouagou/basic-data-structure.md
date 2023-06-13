# Supprimer des éléments d'un tableau avec pop() et shift()

`push()` et `unshift()` ont des méthodes correspondantes qui sont presque fonctionnellement opposées : `pop()` et `shift()`. Comme vous l'avez peut-être déjà deviné, au lieu d'ajouter, `pop()` _supprime_ un élément de la fin d'un tableau, tandis que `shift()` _supprime_ un élément du début. La principale différence entre `pop()` and `shift()` et leurs cousins `push()` et `unshift()`, est qu'aucune des méthodes ne prend de paramètres, et chacune d'elle ne permet la modification d'un seul élément à la fois.

Par exemple:

```js
let greetings = ['whats up?', 'hello', 'see ya!'];

greetings.pop();
```

`greetings` aura comme valeur `['whats up?', 'hello']`

```js
greetings.shift();
```

`greetings` aura comme valeur `['hello']`

Nous pouvons également renvoyer la valeur de l'élément supprimé avec l'une ou l'autre méthode comme celle-ci :

```js
let popped = greetings.pop();
```

`greetingsaurait` aura comme valeur `[]`, et `popped` aura comme valeur `hello`.
