# JavaScript Cheat Sheet


### VARIABLES :

Déclaration : `let` nomVariable;
Assignation : `nomVariable = valeur`;
Constante : `const` nomConstante = valeur;

---

### TYPES DE DONNÉES :

Nombre : `let nombre = 42`;
Chaîne de caractères : `let texte = "Hi, Martin"`;
Booléen : `let estVrai = true`;
Tableau : `let tableau = [1, 2, 3]`;
Objet :

```javascript
let objet = { 
    clé1: "valeur1", 
    clé2: "valeur2" 
    };
```

---

### OPÉRATEURS ARITHMÉTIQUES :

Addition : `+`
Soustraction : `-`
Multiplication : `*`
Division : `/`
Modulo (reste de la division) : `%`

---

### OPÉRATEURS DE COMPARAISON :

Égalité avec : `==`
Égalité stricte avec : `===`
Différent de : `!=`
Inférieur à : `<`
Supérieur à : `>`
Inférieur ou égal à : `<=`
Supérieur ou égal à : `>=`

---

### STRUCTURES DE CONTRÔLE :

Condition If-Else :

```javascript
if (condition) {
    // Instructions si vrai
} else {
    // Instructions si faux
}
```

Boucle While :

```javascript
while (condition) {
    // Instructions répétées
}
```

Boucle For :

```javascript
for (let i = 0; i < limite; i++) {
    // Instructions répétées
}
```

Fonctions :

```javascript
function nomFonction (paramètre1, paramètre2) {
    // Instructions
    return résultat;
}
```

Appel de fonction :

```javascript
let résultat = nomFonction(arg1, arg2);
```

---

### TABLEAUX ET OBJETS :

Accéder à un élément de tableau : `tableau[indice]`
Ajouter un élément à un tableau : `tableau.push(valeur)`
Accéder à une propriété d'un objet : `objet.clé`
Modifier une propriété d'un objet : `objet.clé = nouvelleValeur`

### ITERATION SUR UN TABLEAU :

```javascript
tableau.forEach(function (élément) {
    // Instructions pour chaque élément
});
```

---

### MAP :

```javascript
const nouveauTableau = tableau.map(function (élément) {
    // Transformation de chaque élément
    return nouveauÉlément;
});
```

---

### FILTRE :

```javascript
const tableauFiltré = tableau.filter(function (élément) {
    // Condition de filtrage
    return condition;
});
```
