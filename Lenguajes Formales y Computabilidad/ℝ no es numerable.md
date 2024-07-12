---
fecha_creacion: 2023-09-15
aliases: R-no-es-numerable
---

# Idea
Enumerar uno por uno los decimales a partir del cero, formando una diagonal cuyos elementos forman un número que pertenece al rango pero no a la enumeración. Esta es la *Diagonal de Cantor*.

# Demostración
Alcanza con probar que $(0, 1) \subset \mathbb{R}$ no es numerable.

Empezamos entonces enumerar los números a partir del 0, enumerando sus dígitos de forma $a_{mn}$. Entonces quedaría:
$$\begin{align}
0.a_{00}a_{01}a_{02} \dots \\
0.a_{10}a_{11}a_{12} \dots \\ \vdots
\end{align}
$$

Ahora bien, sea $b = 0.b_n \dots$ con $n \in \mathbb{N} - \{n \mod 11 = 0\}$ (Revisar).

Entonces no figura en el listado, ya que difiere al menos en un dígito con cada número de la lista. ABS!

$$ \therefore (0, 1) \subset \mathbb{R} \text{ no es numerable.}$$