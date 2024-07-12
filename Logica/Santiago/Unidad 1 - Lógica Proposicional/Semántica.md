1. [[Valores de verdad]]
2. [[Valuación]]

## Semántica para [[El conjunto Prop#Definición 1 (Prop)|Prop]], definición formal
#### Definición 5
sea v una [[Valuación]]. Definimos la función
$$[[]]_v\ :\ Prop \rightarrow \{T, F\}$$
por inducción en Prop:
$[[⊥]]_v = F$ 
$[[p_i]]_v = v(p_i)$
$[[\phi \land \psi]]_v = min([[\phi]]_v, [[\psi]]_v)$
$[[\phi \lor \psi]]_v = max([[\phi]]_v, [[\psi]]_v)$
$[[\phi \rightarrow \psi]]_v = F\ sii\ [[\phi]]_v = T\ y\ [[\psi]]_v = F$
$[[\lnot \phi]]_v = F\ sii\ [[\phi]]_v = T$

#### Definición 6 (Tautología)
Una fórmula $\phi \in Prop$ es una tautología sii para cualquier valuación v, $[[\phi]]_v = T$

#### Definición 7 (Contradicción)
Una fórmula $\phi \in Prop$ es una contradicción sii para cualquier valuación v, $[[\phi]]_v = F$

#### Definición 8 (Fórmula satisfactible)
Una fórmula $\phi \in Prop$ es satisfactible sii para alguna valuación v, $[[\phi]]_v = T$
