---
title: Guide de Syntaxe MathJax
description: Guide de Syntaxe MathJax
---

# **Guide de Syntaxe MathJax**

Ce guide explique comment utiliser MathJax pour afficher des formules mathématiques.

!!! warning "Avertissement"
    Cette page a été principalement générée à l'aide d'une IA (ChatGPT). Des erreurs peuvent être présentes

## **1. Configuration de MathJax**
Ajoutez cette ligne dans le fichier mkdocs.yml pour activer MathJax :
```yml
markdown_extensions:
  - pymdownx.arithmatex:
      generic: true
extra_javascript:
  - https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/MathJax.js?config=TeX-MML-AM_CHTML
```

---

## **2. Affichage des formules**

### **1.1. Formules en ligne**
Utilisez **`\(...\)`** ou **`$...$`** pour afficher une équation dans une phrase :

```md
La formule de l'énergie est $E = mc^2$.
```
<div class="result" markdown>

La célèbre équation d'Einstein est \( E = mc^2 \).

</div>

### **1.2. Formules en bloc**
Utilisez **`\[...\]`** ou **`$$...$$`** pour afficher une équation sur une ligne séparée :

```md title="exemple"
Voici une équation importante :

\[
a^2 + b^2 = c^2
\]
```

<div class="result" markdown>

Voici une équation importante :

\[
a^2 + b^2 = c^2
\]

</div>

---

## **3. Opérateurs Mathématiques**

| Symbole | Syntaxe MathJax | Affichage |
|---------|----------------|-----------|
| Addition | `a + b` | \( a + b \) |
| Soustraction | `a - b` | \( a - b \) |
| Multiplication | `a \times b` ou `a \cdot b` | \( a \times b \), \( a \cdot b \) |
| Division | `\frac{a}{b}` | \( \frac{a}{b} \) |
| Puissance | `x^n` | \( x^n \) |
| Racine carrée | `\sqrt{x}` | \( \sqrt{x} \) |
| Racine n-ième | `\sqrt[n]{x}` | \( \sqrt[n]{x} \) |
| Intégrale | `\int a \,dx` | \( \int a \,dx \) |
| Somme | `\sum_{i=1}^{n} a_i` | \( \sum_{i=1}^{n} a_i \) |
| Produit | `\prod_{i=1}^{n} a_i` | \( \prod_{i=1}^{n} a_i \) |

---

## **4. Exposants et Indices**

| Syntaxe | Affichage |
|---------|----------|
| `x^2` | \( x^2 \) |
| `x^{n+1}` | \( x^{n+1} \) |
| `a_1` | \( a_1 \) |
| `a_{i,j}` | \( a_{i,j} \) |

```md title="exemple"
\[
E = mc^2, \quad a_{i,j} = x^i y^j
\]
```

<div class="result" markdown>

\[
E = mc^2, \quad a_{i,j} = x^i y^j
\]

</div>

---

## **5. Fractions et Racines**

| Syntaxe | Affichage |
|---------|----------|
| `\frac{a}{b}` | \( \frac{a}{b} \) |
| `\sqrt{x}` | \( \sqrt{x} \) |
| `\sqrt[3]{x}` | \( \sqrt[3]{x} \) |

```md title="exemple"
\[
\frac{x+1}{y-2}, \quad \sqrt{x^2+1}, \quad \sqrt[3]{8}
\]
```

<div class="result" markdown>

\[
\frac{x+1}{y-2}, \quad \sqrt{x^2+1}, \quad \sqrt[3]{8}
\]

</div>

---

## **6. Intégrales et Sommes**

| Syntaxe | Affichage |
|---------|----------|
| `\int_a^b f(x) \,dx` | \( \int_a^b f(x) \,dx \) |
| `\sum_{n=1}^{\infty} a_n` | \( \sum_{n=1}^{\infty} a_n \) |

```md title="exemple"
\[
\int_0^1 x^2 \,dx, \quad \sum_{n=1}^{\infty} \frac{1}{n^2}
\]
```

<div class="result" markdown>

\[
\int_0^1 x^2 \,dx, \quad \sum_{n=1}^{\infty} \frac{1}{n^2}
\]

</div>

---

## **7. Matrices et Déterminants**

### **7.1. Matrice 2×2**

```md title="exemple"
\[
\begin{bmatrix} 
a & b \\ 
c & d 
\end{bmatrix}
\]
```

<div class="result" markdown>

\[
\begin{bmatrix} 
a & b \\ 
c & d 
\end{bmatrix}
\]

</div>

### **7.2. Matrice 3×3**

```md title="exemple"
\[
\begin{vmatrix} 
a & b & c \\ 
d & e & f \\ 
g & h & i 
\end{vmatrix}
\]
```

<div class="result" markdown>

\[
\begin{vmatrix} 
a & b & c \\ 
d & e & f \\ 
g & h & i 
\end{vmatrix}
\]

</div>

---

## **8. Symboles Divers**

| Symbole | Syntaxe | Affichage |
|---------|--------|-----------|
| Infini | `\infty` | \( \infty \) |
| Appartenance | `\in` | \( \in \) |
| Non-appartenance | `\notin` | \( \notin \) |
| Pour tout | `\forall` | \( \forall \) |
| Il existe | `\exists` | \( \exists \) |
| Flèche droite | `\rightarrow` | \( \rightarrow \) |
| Double flèche | `\Rightarrow` | \( \Rightarrow \) |

```md title="exemple"
\[
\forall x \in \mathbb{R}, \quad x^2 \geq 0
\]
```

<div class="result" markdown>

\[
\forall x \in \mathbb{R}, \quad x^2 \geq 0
\]

</div>

---

## **9. Fonctions Trigonométriques et Logarithmes**

| Fonction | Syntaxe | Affichage |
|----------|--------|-----------|
| Sinus | `\sin x` | \( \sin x \) |
| Cosinus | `\cos x` | \( \cos x \) |
| Tangente | `\tan x` | \( \tan x \) |
| Logarithme | `\log x` | \( \log x \) |
| Exponentielle | `e^x` | \( e^x \) |

```md title="exemple"
\[
\sin^2 x + \cos^2 x = 1, \quad \log(e^x) = x
\]
```

<div class="result" markdown>

\[
\sin^2 x + \cos^2 x = 1, \quad \log(e^x) = x
\]

</div>

---

## **Conclusion**
MathJax utilise une syntaxe inspirée de LaTeX et permet d'afficher des équations mathématiques directement sur le web. Avec ce guide, vous avez un bon aperçu des commandes les plus courantes !