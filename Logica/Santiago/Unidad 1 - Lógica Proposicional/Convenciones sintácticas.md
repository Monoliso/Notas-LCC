- [[El conjunto Prop#Alfabeto|Alfabeto]]

Cuando no haya lugar a ambigüedades:
- Omitiremos los paréntesis más externos de una fórmula
- Usaremos el siguiente orden de precedencia: ¬, ∧, ∨, →

#### Ejemplo:
Escribiremos
$$p_1 \lor \lnot p_2 \rightarrow p_3$$
en lugar de 
$$((p_1 \lor (\lnot p_2))\rightarrow p_3)$$
- Sea v una [[Valuación]]. Extenderemos la definición de $[[]]_v$ a conjuntos:
$$[[\Gamma]]_v = T\ \text{sii para toda}\ \phi \in \Gamma, [[\phi]]_v = T$$

#### Definición de ↔
Definimos el operador ↔ de la siguiente forma:
$$(\phi ↔ \psi) \equiv (\phi \rightarrow \psi) \land (\psi \rightarrow \phi)$$
