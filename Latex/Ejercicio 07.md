## Enunciado
Dada $B = \begin{pmatrix} 0 & 1 \\ 0 & 2\end{pmatrix}$. Hallar en cada caso todas las matrices $A \in \mathbb{F}^2$.

## a)
Enunciado $A.B = 0$
Sea $\begin{pmatrix} x &y \\ z &w \end{pmatrix} \in \mathbb{F}^{2\times2}$
$$
\begin{array}{@{}cc|c@{}}
& & \begin{matrix} 0 & 1 \\ 0 & 2\end{matrix} \\
\hline
& \begin{matrix} x & y \\ z & w\end{matrix} & \begin{matrix} (x\cdot0 + y\cdot 0) & (x\cdot 1 + y\cdot 2) \\
(z\cdot 0 + w\cdot 0) & (z\cdot 1 + w\cdot 2)\end{matrix}
\end{array}
$$
Entonces
$$
\begin{cases}
x+ 2y = 0 \implies x = -2y \\
z+ 2w = 0 \implies z = -2w
\end{cases}
$$
$$
\boxed{\therefore S = \left\{\begin{pmatrix} -2y & y \\ -2w & w\end{pmatrix} = A; \;y, w \in \mathbb{F} \right\}}
$$

## b)
Enunciado: $B \cdot A = 0$
$$
\begin{array}{@{}cc|c@{}}
& & \begin{matrix} x & y \\ z & w \end{matrix} \\
\hline
& \begin{matrix} 0 & 1 \\ 0 & 2 \end{matrix} & \begin{matrix} z & w \\ 2z & 2w\end{matrix}
\end{array}
$$
Luego, si $BA=0$, debe ser $z=w=0$, y en consecuencia, todas las matrices $A\in\mathbb{R}^{2\times2}$ son las matrices del conjunto
$$
S=\left\{ \begin{pmatrix} x & y \\ 0 & 0\end{pmatrix} : x, y \in \mathbb{F} \right\}
$$

## c)
Enunciado: $A^2 = 0$
Respuesta: mirar el documento de ejercicios resueltos.