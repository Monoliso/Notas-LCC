---
fecha_creacion: 2023-09-13
aliases: Haskell
---

El Cálculo Lambda es un modelo de [[00-Lenguajes Formales y Computabilidad|Cálculo]] basado en la abstracción de funciones y aplicación usando asociación y sustitución de variables. Sus tres bloques o átomos son:

 - $x:$ Un término lambda.
 - $(\lambda x. M):$ Una abstracción lambda es una función $M$ donde la $x$ tiene una sustitución explícita en la expresión $M$.
 - $(M)\ N:$ Una aplicación o valuación, que aplica la función $M$ a un argumento $N$.

Esto demuestra que toda la matemática se puede expresar a partir de funciones y valuaciones, ni siquiera los conjuntos son nuestros átomos, son las funciones (había que corroborar esto). Las fundaciones de Haskell remontan a este modelo.

Una variante del cálculo lambda es la [[Lógica Combinatoria]].