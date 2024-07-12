$$
\begin{pmatrix}
1 & 5 & 6 & 3 & 86 \\
1 & 32 & 2 & 2 & 23 \\
1 & 2 & 3 & 3 & 2
\end{pmatrix}
$$
$\sum_{i}^{5}$

$$
\begin{pmatrix}
2 & 3 & 5 \\
3 & 45 & 8
\end{pmatrix}
\text{Notable...}
$$
$\tau+\sigma \geq \implies\sigma^{2\times{3}} \frac{1}{56}$

$$
\begin{matrix}
1 & 3 & l & 4 \\
5 & 6 & 7 & 8
\end{matrix}
$$
$$
\begin{pmatrix}
1 & 3 & 4 \\
2 & 4 & 6
\end{pmatrix}
$$
$\frac{2+3+4}{45}3\times2$

$\boxed{1+2 \xrightarrow[T]{\text{álgebra}} 3}$

```tikz 
\usepackage{circuitikz} 
\begin{document} 
\begin{circuitikz}[american, voltage shift=0.5] 
\draw (0,0) to[isource, l=$I_0$, v=$V_0$] (0,3) to[short, -*, i=$I_0$] (2,3) to[R=$R_1$, i>_=$i_1$] (2,0) -- (0,0); 
\draw (2,3) -- (4,3) to[R=$R_2$, i>_=$i_2$] (4,0) to[short, -*] (2,0); 
\end{circuitikz} 
\end{document}
```
---
```tikz
\begin{document}
\begin{tikzpicture}
\draw[thick,red] (-1,-1) -- (1,1); 
\draw[thick,red] (-1,1) -- (1,-1); 
\end{tikzpicture}
\end{document}
```
---
```tikz 
\begin{document} 
\begin{tikzpicture}[domain=0:4] 
\draw[very thin,color=gray] (-0.1,-1.1) grid (3.9,3.9); \draw[->] (-0.2,0) -- (4.2,0) node[right] {$x$}; 
\draw[->] (0,-1.2) -- (0,4.2) node[above] {$f(x)$}; \draw[color=red] plot (\x,\x) node[right] {$f(x) =x$}; \draw[color=blue] plot (\x,{sin(\x r)}) node[right] {$f(x) = \sin x$}; \draw[color=orange] plot (\x,{0.05*exp(\x)}) node[right] {$f(x) = \frac{1}{20} \mathrm e^x$}; \end{tikzpicture} 
\end{document}
```

El environment [array](https://tex.stackexchange.com/questions/204838/difference-between-tabular-and-array-environment#:~:text=The%20array%20environment%20is%20for,be%20typeset%20in%20text%20mode%20.) si está soportado.

Buenísimo [link](https://en.wikibooks.org/wiki/LaTeX/Mathematics#Matrices_and_arrays), super informativo.

$\LaTeX$ $\TeX$
$\textsf{R}$

**MathJax only implements the macros used for math layout, not text layout, so things like `\begin{tabular}` and `\begin{center}` are not supported**

 - [Comandos soportados](https://docs.mathjax.org/en/latest/input/tex/macros/index.html#t)
 - [(3) Math tables don't work : ObsidianMD (reddit.com)](https://www.reddit.com/r/ObsidianMD/comments/lm6gr7/math_tables_dont_work/)
 - [LaTeX/Advanced Mathematics - Wikibooks, open books for an open world](https://en.wikibooks.org/wiki/LaTeX/Advanced_Mathematics)
 - [Using labels with mathJax? - Physics Meta Stack Exchange](https://physics.meta.stackexchange.com/questions/5396/using-labels-with-mathjax)
 - [Automatic Equation Numbering — MathJax 3.2 documentation](https://docs.mathjax.org/en/latest/input/tex/eqnumbers.html)