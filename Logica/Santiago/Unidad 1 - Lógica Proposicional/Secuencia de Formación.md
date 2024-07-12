## Definición 2
Una secuencia $\phi_0, \phi_1, ..., \phi_n$ es una **Secuencia de formación** para $\phi \in$[[El conjunto Prop#Definición 1 (Prop)|Prop]] sii
- $\phi_n = \phi$, y
- $\forall i \le n, \phi_i\ \text{es atómica (cumple (i)), o}$
	$\phi_i = (\phi_k \square \phi_j)$ para algún k, j < i, (con $\square \in$ {∧, ∨, ⊥})
	$\phi_i = (\lnot \phi_j),$ para algún j < i

#### Observación:
Hay infinitas secuencias de formación para una misma fórmula
ejemplo:
p1, p2,(¬p1),((¬p1) ∧ p2) es una secuencia de formación para ((¬p1) ∧ p2), pero también lo es ⊥, p1, p3,(p1 ∧ p3), p2,(¬p1),(p2 → ⊥),((¬p1) ∧ p2)

### Teorema 1
Una palabra tiene una secuencia de formación sii pertenece a Prop