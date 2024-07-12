## a)

Enunciado: $C + D$, donde 
$$D = 
\begin{pmatrix}
	-1 &0 &2\\
	4 &3 &-2
\end{pmatrix}
\in \mathbb{F}^{2\times3}$$

$$C = 
\begin{pmatrix}
	3 &2 &-1\\
	4 &5 &0
\end{pmatrix}
\in \mathbb{F}^{2\times3}$$

Por lo que puede calcularse $C + D$.

$$C + D =
\begin{pmatrix}
	3 &2 &-1\\
	4 &5 &0
\end{pmatrix}
+
\begin{pmatrix}
	-1 &0 &2\\
	4 &3 &-2
\end{pmatrix}
=
\begin{pmatrix}
	3-1 &2+0 &-1+2\\
	4+4 &5+3 &0-2
\end{pmatrix}
=
\begin{pmatrix}
	2 &2 &1\\
	8 &8 &-2
\end{pmatrix}
$$

## b)
Enunciado: $B - C + 3A$.
Rta: Como los tamaños de las matrices no coinciden no puedo restar $B - C$.

## c)
### Enunciado
$2A-\frac{1}{2}B = 2A+\left[ -\frac{1}{2}B \right]$

### Resolución
$$
2A=
2\begin{pmatrix}
0 & 0 \\
0 & 1
\end{pmatrix}=
\begin{pmatrix}
2\cdot{0} & 2\cdot{0} \\
2\cdot{0} & 2\cdot{1}
\end{pmatrix}=
\begin{pmatrix}
0 & 0 \\
0 & 2
\end{pmatrix}
$$
$$
-\frac{1}{2}B=
-\frac{1}{2}\begin{pmatrix}
0 & 0 \\
1 & 0
\end{pmatrix}=
\begin{pmatrix}
-\frac{1}{2}\cdot0 & -\frac{1}{2}\cdot0 \\
-\frac{1}{2}\cdot1 & -\frac{1}{2}\cdot0
\end{pmatrix}=
\begin{pmatrix}
0 & 0 \\
-\frac{1}{2} & 0
\end{pmatrix}
$$
Por lo que 
$$2A - \frac{1}{2}B=\begin{pmatrix}
0 & 0 \\
\frac{1}{2} & 2
\end{pmatrix}$$

## f)
### Enunciado
$H\cdot J$, donde
$$H=\begin{pmatrix}
2 & -1 & 0 & 2 \\
3 & 2 & 3 & -1 \\
5 & 3 & 2 & 3 \\
4 & 0 & -1 & 4 \\
\end{pmatrix} \in\mathbb{F}^{4\times4}$$
$$
J=\begin{pmatrix} -1 \\ 0 \\ 3 \\ 4 \end{pmatrix} \in\mathbb{F}^{4\times1}
$$
Por lo que puedo realizar el producto $H\cdot J\in\mathbb{F}^{4\times4}$

$$
\begin{array}{@{}cc|c@{}}
& & \begin{matrix} -1 \\ 0 \\ 3 \\ 4 \end{matrix} \\
\hline
& \begin{matrix}
2 & -1 & 0 & 2 \\
3 & 2 & 3 & -1 \\
5 & 3 & 2 & 3 \\
4 & 0 & -1 & 4
\end{matrix}
& \begin{matrix} 6 \\ 2 \\ 13 \\ 9 \end{matrix}
\end{array}
$$

## i)
Enunciado: $G \in \mathbb{F} ^{4\times1}$
Resolución: $F \in \mathbb{F}^{1\times4} \quad \therefore G\cdot{F}$ no es posible hacerse.