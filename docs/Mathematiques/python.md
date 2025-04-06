---
title: Python
description: Introduction aux codes Python les plus communs dans les exercices de mathématiques.
---

# Python en mathématiques

Les exercices en Python représentent, en mathématiques, une opportunité d'obtenir un point ou deux facilement.

Ils se présentent pour la quasi-totalité sous forme de texte à trous qu'il faut compléter.

## **1. boucles**

Quasiment la totalité des exercices de code Python en mathématiques sont des boucles à compléter, afin de calculer un certain seuil d'une suite.

Les boucles permettent de répéter un code. Chaque exécution de la boucle est appelée une **itération**

En python, il existe deux types de boucle:

### **1.1 Les Boucle "For"**

La boucle ```for``` (en français **"Pour"**) est une boucle qui est exécutée pour un nombre déterminé d'itérations

Exemple: **Pour** ```i``` compris entre 0 et 10 :

``` py title="Boucle 'for'" linenums="1"
nombre = 0
for i in range (0, 10):
    nombre = nombre + 1
print(nombre)

>>> 10
```

### **1.2. Les Boucle "While"**

La boucle ```while``` (en français **"tant que"**) est une boucle qui est exécutée tant qu'une certaine condition est valide 

Exemple: **tant que** la variable ```nombre``` est inférieur à 10 :

``` py title="Boucle 'while'" linenums="1"
nombre = 0
while nombre < 10:
    nombre = nombre + 1
print(nombre)

>>> 10
``` 

!!! warning "attention aux boucles infinies !"
    Assurez-vous à ce que la condition d'arrêt de la boucle soit atteinte, autrement elle deviendra une **boucle infini** !

    Par exemple, prenons le code suivant:
    ``` py linenums="1"
    nombre = 5
    while nombre > 4:
        nombre = nombre + 1
    print(nombre)
    ``` 
    Ici la boucle _while_ va incrémenter la variable ```nombre``` tant que ```nombre``` est supérieur à 4, le programme ne va donc jamais s'arrêter !

## 2. Exercices

!!! Example "2.1 Boucles 'For'"
    _A venir_

!!! Example "2.2 Boucles 'While'"
    g(n) = $0.1*0.5^{n-1}+0.4$

    Compléter les lignes 4 et 6 de la fonction suivante afin qu'elle renvoie le plus petit rang à partir duquel les termes de la suite $(g_n)$ sont tous inférieurs ou égaux à $0.4+e$, où e est un nombre réel strictement positif.
    ```py linenums="1"
    def seuil(e):
        g=0.5
        n=1
        while............:
            g=0.5*g+0.2
            n=.........
        return(n)
    ```
    ??? success "Corrigé"
        ```py linenums="1" hl_lines="4 6"
        def seuil(e):
            g=0.5
            n=1
            while g > 0.4+e:
                g=0.5*g+0.2
                n= n+1
            return(n)
        ```