---
fecha_creacion: 2023-04-22
---
## 2.4 Matrices inversibles

$$
\begin{array}{@{}cc|c@{}}
& & \begin{matrix} 1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1 \end{matrix} \\
\hline
& \begin{matrix} 1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1\end{matrix} & \begin{matrix} 1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1 \end{matrix}
\end{array}
$$

Por otro lado...
$$
\begin{array}{@{}cc|c@{}}
& & \begin{matrix} ?\end{matrix} \\
\hline
& \begin{matrix} 0 & 0 & 0 \\
0 & 0 & 0 \\
0 & 0 & 0\end{matrix} & \begin{matrix} 1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1\end{matrix}
\end{array}
$$
Es trivial de que es imposible.


## 2.5 Desarrollo por filas y columnas

$S_{3} = \{(1, 2, 3), (1, 3, 2), (2, 1, 3), (2, 3, 1), (3, 1, 2), (3, 2, 1)\}$

Además $S_{n}^{j} = \{{\sigma}\in S_{n} : \sigma(1) = j\}$, por lo que
$$
S_{3} = S_{3}^{1}\cup S_{3}^{2}\cup S_{3}^{3}
$$
Entonces, expandiendo
$$S_{3}^{1} \implies \{\sigma \in S_{3} : \sigma(1) = 1\} = \{(1, 2, 3), (1, 3, 2)?\}$$
$$S_{3}^{2} \implies \{\sigma \in S_{3} : \sigma(1) = 2\} = \{(2, 1, 3), (2, 3, 1)?\}$$
$$S_{3}^{3} \implies \{\sigma \in S_{3} : \sigma(1) = 3\} = \{(3, 2, 1), (3, 1, 2)?\}$$