---
fecha_creacion: 2023-11-07
---
## Requerimientos
Para poder interpretar una [[Fórmula]] hay que primero poder [[Interpretación de un término|interpretar cada uno de los términos]] que la componen. Para ello necesitamos que el modelo $\mathcal{M}$ y la fórmula $\phi$ estén definidas sobre la misma [[Signatura]].

Al definir la interpretación de los términos se establece una función $\operatorname s$ sobre *todas* las variables. Eso no es un problema porque las variables son indiferentes en los términos, pero no así en las *fórmulas*.

Al momento de hacer una valuación de una fórmula los resultados de $\operatorname s$ se pasan a los predicados definidos en $\mathcal{M}$, pero también se aplican a los cuantificadores. Para estos casos también se obtiene un valor de verdad, definiendo un entorno nuevo para cada uno de los elementos.
Es decir, para los cuantificadores se irá evaluando con distintas funciones que relacionan el valor fijado con cada uno de los posibles valores a tomar del universo. Se trata entonces de un conjunto por comprensión.

## Definición
Sea $\phi \in Form$ definimos la semántica de $\phi$ en $(\mathcal{M},s)$, y lo notamos $[\![\phi]\!]_{\mathcal{M},s}$ por inducción en $\phi$.

 - Fórmulas atómicas
 - Conectivos
 - Cuantificadores