## Enunciado
Si $A, B \in \mathbb{F}^3$.

## a)
Si la 1° y 3° columnas de $B$ son iguales también lo son la 1° y 3° de $A.B$.

$A = (a_{ij}), \; i= 1,2,3 \wedge j=1,2,3$
$B = (b_{ij}) \rightarrow b_{i1} = b_{i3},  \;\forall i=1,2,3 \;(1)$

Entonces:
$A.B = C = \sum_{k=1}^3 a_{ik}.b_{kj}$ - Siendo $i$ fila, $j$ columna.

$$C_{i1} = \sum_{k=1}^3 a_{ik}.b_{k1}$$
$$C_{i3} = \sum_{k=1}^3 a_{ik}.b_{k3}$$

Veamos que:
$C_i1 = \sum_{k=1}^3 a_{ik}.b_{k1}$ = (por 1) $\sum_{k=1}^3 a_{ik}.b_{k3} = C_i3 \implies C_{i1} = C_{i3}$
$\therefore$ Es verdadero.