```tex
\begin{pmatrix}
	-1 &0 &2\\
	4 &3 &-2
\end{pmatrix}
```

```tex
\begin{pmatrix} -1 &0 &2\\ 4 &3 &-2\end{pmatrix}
```

Cuando quiero hacer los casos solamente con operadores
```latex
X(m, n) = \left.
\begin{cases}
	x(n), & \text{for } 0 \leq n \leq 1 \\
	x(n - 1), & \text{for } 0 \leq n \leq 1 \\
	x(n - 1), & \text{for } 0 \leq n \leq 1
\end{cases}
\right\} = xy
```

Para cuando quiero hacer producto de matriz
```latex
\begin{array}{@{}cc|c@{}}
& & \begin{matrix} \end{matrix} \\
\hline
& \begin{matrix} \end{matrix} & \begin{matrix} \end{matrix}
\end{array}
```

Para cuando quiero poner texto normal
```latex
f(x) = \begin{dcases*}
	x & when $x$ is even\\
	-x & when $x$ is odd
\end{dcases*}
```