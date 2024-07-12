---
fecha_creacion: 2023-09-14
aliases:
  - s-precede-conjunto-partes-s
---

# Idea
Realizar una inyección y demostrar que la suryección es imposible, por lo que la biyección también. El truco es generar una paradoja en la sobreyección, demostrando su inexistencia.

# Demostración

Teniendo a $S$ y $P(S)$ podemos realizar una función inyectiva de la forma $f: S \to P(S)$ donde $f(a) = \{a\}$. Entonces, al menos $S \preceq P(S)$.

Supongamos que $\exists f1: S \to P(S)$ sobreyectiva.

Luego sea el conjunto $B$ = $\{a \in S \mid a \notin f(a)\}$, es decir los elementos de $S$ que no pertenecen a su imagen. Por definición $B \in P(S)$, y al ser sobreyectiva $\exists x \in S \mid f1(x) = B$.

Luego nos preguntamos ¿$x \in B$?

Si pertenece, entonces $x \notin f1(x) = B$, pero entonces no pertenece. ABS!
Si no pertenece, entonces $x \notin f1(x) = B$, pero entonces pertenece. ABS!

$$ \therefore \ \nexists f1 : S \to P(S) \text{ sobreyectiva}$$