---
fecha_creacion: 2023-11-07
aliases:
  - Interpretación
  - Estructura
---
## Definición
Sea una [[Signatura]] $(\mathcal{F}, \mathcal{P})$ denotada como $\sigma$. Un modelo $\mathcal{M}$ para $\sigma$ ($\mathcal{M}_{\sigma}$) consiste en:
 - Un conjunto no vacío $A$, llamado *universo*.
 - Para cada constante $c \in \mathcal{F}$, un elemento $c^{\mathcal{M}} \in A$.
 - Para cada símbolo $f \in \mathcal{F}$ con $\text{ar}(f) = n > 0$ una función $f^{\mathcal{M}} : A^n \to A$.
 - Para cada símbolo de predicados $P \in \mathcal{P}$, un conjunto $P^{\mathcal{M}} \subseteq A^n$ . Es
decir, una relación n-aria sobre $A$.

### Generalización
Una estructura $\mathcal{A}$ se define como la terna $\mathcal{A} = (A, \sigma, I)$ consistiendo de un dominio $A$ (un conjunto arbitrario), una [[Signatura]] $\sigma$, y una [[Función de interpretación]] $I$ que indica cómo la signatura debe ser interpretada en el dominio.

## Observaciones
 - La idea con que cada símbolo de predicado tenga asociado un conjunto en vez de una función es porque es más simple. Pertenecen a ese conjunto los pares ordenados de objetos (es decir, los argumentos) que devuelven $T$ para esa función predicado.
 - Existe un predicado que tendrá la misma semántica en todos los modelos. Se trata del símbolo $=$ , por lo que se asume definido en todos los modelos.

Con estas herramientas podemos decir que cierto modelo $\mathcal{M}$ satisface determinadas [[Fórmula|fórmulas]] $F$ en $Form$, es decir:
$$
\mathcal{M}_{\sigma} \models F \in Form_{\sigma}
$$
Dándole de esta forma significado a las fórmulas en función del modelo que se utilice.
## Recursos
 - https://en.wikipedia.org/wiki/Structure_(mathematical_logic)#Definition
 - https://en.wikipedia.org/wiki/Structure_(mathematical_logic)#Satisfaction_relation
 - https://en.wikipedia.org/wiki/Interpretation_(logic)#First-order_logic