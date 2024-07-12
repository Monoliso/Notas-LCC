---
fecha_creacion: 2023-09-14
---

# Motivación
Queremos saber cuándo dado un lenguaje existe un AEF que lo reconozca.

# Idea
Podemos aprovecharnos de que la cantidad de estados en todo autómata es necesariamente finito para hacer un ciclo, haciendo que las palabras detectadas puedan ser *bombeadas*, rompiendo la condición inicial. Entonces, necesariamente, dicho lenguaje no pertenece a $\mathcal{L}_3$.

# Hipótesis
Sea un lenguaje $L = \{x^n y^n | n \in \mathbb{N}\}$ y un autómata finito $A$.

# Demostración
Por definición $A$ tiene una cantidad finita de estados $S$, por lo que siempre puedo encontrar un $n > |S|,\ n \in \mathbb{N}$.
Como consecuencia de esto, necesariamente para que sea detectado se generará un ciclo con los estados. Pero entonces, el autómata detecta más palabras, pues la forma $x^{n+km} y^n$ (con $k$ siendo el largo del bucle y $m$ la cantidad de vueltas) también es aceptada. Entonces el autómata falla en la detección, existen palabras que se filtran, que pueden *bombearse*, aceptando un lenguaje de la forma $x^{n+km} y^n$.