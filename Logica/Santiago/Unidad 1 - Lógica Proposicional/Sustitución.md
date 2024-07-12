Definimos $\phi[\psi/p_i]$ por inducción en $\phi$:
$$\bot[\psi/p_i] = \bot$$
$$
p_j[\psi/p_i] = \begin{cases} \psi & \text{si i=j} \\ p_j & \text{si } i\ne j \end{cases}
$$
$$(\phi_1 \square \phi_2)[\psi/p_i] = \phi_1[\psi/p_i]\square \phi_2[\psi/p_i]$$
$$(\lnot \phi)[\psi/p_i] = \lnot (\phi[\psi/p_i])$$

### Teorema 2 (Teorema de sustitución)
Sean $\phi_1, \phi_2, \psi \in Prop, p_i \in AT$ ([[El conjunto Prop#Alfabeto|conjunto de proposiciones atómicas]])
Si |= $\phi_1 \iff \phi_2$, entonces |= $\psi[\phi_1/p_i] \iff \psi[\phi_2/p_i]$
