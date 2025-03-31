---
title: Fonctions Sinus et Cosinus
description: Fonctions Sinus et Cosinus
status : new
---

# Fonctions Sinus et Cosinus

!!! Warning "En construction"

    Cette page est toujours en cours de rédaction. 
    
    Merci de votre patience.

## **1. Rappels**

### **1.1. Définition**

!!! note "**Définition : Fonctions sinus et cosinus**"

    À tout réel \( x \), on associe un point unique \( M \) du cercle d'unité de centre \( O\), dont les coordonnées sont :

    \[ M(x) = (\cos x, \sin x) \]

    On définit alors les fonctions sin et cos sur \( R \) par :

    $$
      x \rightarrow \sin x \quad et \quad x \rightarrow \cos x
    $$

### **1.2. Mesure principale d'un angle**

!!! note "**Définition**"
    La mesure principale d’un angle \( \alpha \) est la mesure \(x \in ]-\pi, \pi] \).

**Exemple :** Déterminer la mesure principale des angles demesures $\frac{17\pi}{4}$ \text{et} $-\frac{31\pi}{6}$

- $\frac{17\pi}{4}\gt\pi$ mesure trop grande. On enlève $k$ de tours soit $k 2\pi = \frac{8k\pi}{4}$

On enlève à 17 un multiple de 8, ici 16 : $\frac{(17-16)}{4} = \frac{\pi}{4}$

- $-\frac{31\pi}{6}\le-\pi$ mesure trop petite. On ajoute $k$ de tours soit $k 2\pi = \frac{12k\pi}{6}$

On ajoute un multiple de 12, ici 36 : $\frac{\pi(-31+36)}{6} = \frac{5\pi}{6}$

### **1.3. Résolution d'équations**

!!! abstract "Théorème : Résolution de $\cos x = a$ et $\sin x = a$"

    - si $|a| \gt 1$, il n’y a pas de solution.

    - si $|a| \le 1$, alors on détermine $\alpha$ tel que $a = \arccos(x)$ ou $a = \arcsin(x)$

    - Deux cosinus sont égaux si leurs angles sont égaux ou opposés :

    $$
    \cos x = \cos \alpha \Leftrightarrow 
    \left\{ 
        \begin{array}{l}
            x = \alpha + k2\pi &\\
            x = -\alpha + k2\pi
        \end{array} 
    \right.
    \text{, avec k} \in \mathbb{Z}
    $$

    - Deux sinus sont égaux si leurs angles sont égaux ou supplémentaires :

    $$
    \sin x = \sin \alpha \Leftrightarrow 
    \left\{ 
        \begin{array}{l}
            x = \alpha + k2\pi &\\
            x = \pi - \alpha + k2\pi
        \end{array} 
    \right.
    \text{, avec k} \in \mathbb{Z}
    $$

!!! Failure "Fin de la rédaction ici (la suite est uniquement du plan)"

### **Signes des fonctions sinus et cosinus**

Les signes de \( \sin x \) et \( \cos x \) dépendent du quadrant dans lequel se trouve l’angle \( x \).

### **Résolution d'inéquations**

Les inéquations trigonométriques se résolvent en déterminant les valeurs de \( x \) satisfaisant les conditions imposées par les inégalités.

### **De sinus à cosinus**

On utilise l'identité fondamentale :

\[ \cos^2 x + \sin^2 x = 1 \]

pour transformer une équation en fonction de l'une ou l'autre des fonctions trigonométriques.

---

## **Étude des fonctions sinus et cosinus**

### **Périodicité et parité**

Les fonctions sinus et cosinus sont périodiques de période \( 2\pi \), avec les propriétés suivantes :

- \( \sin(-x) = -\sin x \) (fonction impaire)
- \( \cos(-x) = \cos x \) (fonction paire)

### **Dérivées**

Les dérivées des fonctions sinus et cosinus sont :

\[ \frac{d}{dx} \sin x = \cos x \]
\[ \frac{d}{dx} \cos x = -\sin x \]

### **Variation en 0**

La fonction \( \sin x \) est croissante en 0 et la fonction \( \cos x \) est décroissante en 0.

### **Variations des fonctions sinus et cosinus**

- \( \sin x \) est croissante sur \( [ -\frac{\pi}{2}, \frac{\pi}{2} ] \) et décroissante sur \( [ \frac{\pi}{2}, \frac{3\pi}{2} ] \).
- \( \cos x \) est décroissante sur \( [ 0, \pi ] \) et croissante sur \( [ \pi, 2\pi ] \).

### **Courbes représentatives**

Les courbes représentatives des fonctions sinus et cosinus sont des sinusoïdes oscillant entre \( -1 \) et \( 1 \).

### **Dérivée de la composée**

Si \( f(x) = \sin(g(x)) \), alors sa dérivée est :

\[ f'(x) = \cos(g(x)) \cdot g'(x) \]

De même, pour \( f(x) = \cos(g(x)) \) :

\[ f'(x) = -\sin(g(x)) \cdot g'(x) \]

### **Étude d'une fonction**

L'étude de fonctions trigonométriques repose sur l'analyse de leur période, parité, variations et points caractéristiques.

