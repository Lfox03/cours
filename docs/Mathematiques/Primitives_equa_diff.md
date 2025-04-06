---
title: Primitives - Equations différentielles
description: Primitives - Equations différentielles
status: new
---

!!! Warning "accès anticipé"

    Cette page est toujours en cours de rédaction. 
    
    Merci de votre patience.
    
# Primitives - Equations différentielles

## **1) Equation différentielle y' = y**

### **A) Définition**

Soit $f$ une fonction continue sur un intervelle $I$. On appelle solution sur $I$ de l'équation différentielle $y' = f$ toute fonction de $I$ dans $\mathbb{R}$ qui a pour dérivée $f$.

### **B) Primitive**

Si $f$ est une fonction définie sur un intervalle $I$, on appelle primitive de $f$ sur $I$ toute fonction $F$ de $I$ dans $\mathbb{R}$, dérivable sur $I$, et qui vérifie :

Pour tout x de $I$, $\quad F'(x) = f(x)$

### **C) Théorème**

Deux primitives d'une même fonction continue sur un intervalle diffèrent d'une constante.

---

Dans les deux tableaux suivants, $n$ désigne un entier, et la fonction $F$ de $I$ dans $\mathbb{R}$ est une primitive sur $I$ de la fonction $f$

## **2) Primitives des fonctions de référence**

|         f(x)         |           F(x)          |                 I                |
|:-------------------: |:-----------------------:|:--------------------------------:|
|    x^n^ (n$\geq$1)   | $\frac{x^{(n+1)}}{n+1}$ |           $\mathbb{R}$           |
|   x^n^ (n$\leq$-2)   | $\frac{x^{(n+1)}}{n+1}$ | $]-\infty; 0[$ ou $]0; +\infty[$ |
| $\frac{1}{\sqrt x}$  | $2 \sqrt x$             | $]0; +\infty[$                   |
| sin(x)               | -cos(x)                 |           $\mathbb{R}$           |
| cos(x)               | sin(x)                  |           $\mathbb{R}$           |
| $\frac{1}{x}$        | ln(x)                   | $]0; +\infty[$                   |
| e^x^                 | e^x^                    |           $\mathbb{R}$           |

## **3) Calcul d'une primitive**

|         f(x)         |           F(x)          |              Conditions             |
|:--------------------:|:-----------------------:|:-----------------------------------:|
|  u' u^n^ (n$\geq$1)  | $\frac{u^{(n+1)}}{n+1}$ |                                     |
|  u' u^n^ (n$\leq$-2) | $\frac{u^{(n+1)}}{n+1}$ |     $u$ ne s'annule pas sur $I$     |
| $\frac{u'}{\sqrt u}$ | $2 \sqrt u$             | $u$ est strictement positif sur $I$ |
| $u'e^u$              | $e^u$                   |                                     |
| $\frac{u'}{u}$       | ln($u$)                 | $u$ est strictement positif sur $I$ |