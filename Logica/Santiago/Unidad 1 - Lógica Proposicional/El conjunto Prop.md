---
aliases:
  - Lógica proposicional como lenguaje formal
---
### Alfabeto
Para definir un lenguaje formalmente necesitamos un **alfabeto**
Para nosotros, estará formado por:
- Variables proposicionales: {$p_0, p_1, p_2, ...$} 
- Conectivos: ∧, ∨, →, ⊥
- Símbolos auxiliares: ":" (,)

## Definición 1 (Prop)
El conjunto *Prop* de proposiciones es el mínimo conjunto X con las siguientes propiedades:
- $p_i \in X, \forall i \in N, y ⊥ \in X$ 
- Si $\phi, \psi \in X$, entonces $(\phi \land \psi), (\phi \lor \psi), (\phi \rightarrow \psi) \in X$ 
- Si $\phi \in X$, entonces $(\lnot \phi) \in X$ 

Esta definición es equivalente a una definición inductiva, o a una gramática independiente del contexto