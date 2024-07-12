## Usar Latex en entorno Markdown
La generación "pura" de Latex ocurre a partir de un documento de texto plano con pura sintáxis de Latex. A partir de la versión del compilador se puede hacer uso de las instrucciones más recientes. Desde un punto de vista de flexibilidad, un documento generado totalmente con Latex permite la personalización absoluta de cada una de las partes, es totalmente replicable en el futuro. A priori, parecería que Latex es mucho más potente en términos de los [estilos y formas de componer el contenido](https://www.latex-project.org/help/documentation/usrguide.pdf).

Ahora bien, en defensa de Markdown, su poder radica en la *rapidez* para la toma de notas. Sus instrucciones son pocas pero relevantes. Excelentes herramientas para documentos donde la presentación no es de *tanta* relevancia. Porque de todas formas creo yo, se pueden hacer cosas de altísima calidad en Markdown. Y es justamente lo que quiero, pues me interesa hacer mis tareas y resúmenes con alta calidad, *pero no con tanta*.
De todas formas el poder de Markdown se me escapa un poco, pues al ser un dialecto que utiliza a html como bytecode permite el uso de CSS, lo que le da *muchísima* flexibilidad estilística.

### Usar VSCode con el compilador normal?
Está claro que con Markdown y especificamente Obsidian hay algunos elementos de $\LaTeX$ que no están disponibles. Los que se permiten son los que pertences al *math mode*. Como se habló arriba, es más limitado. Además en tema de formateo también es molesto, pues obsidian no es un IDE propiamente dicho, su carencia de *tabs* evitan que esto sea así. Ni hablar del autocompletado con tab como la gente (aunque creo que esto si se puede conseguir). No me termina de quedar claro...
 - [(3) Obsidian LaTeX integration? : ObsidianMD (reddit.com)](https://www.reddit.com/r/ObsidianMD/comments/tyini7/obsidian_latex_integration/)
 - [(3) Using Obsidian for mathematical knowledge base : ObsidianMD (reddit.com)](https://www.reddit.com/r/ObsidianMD/comments/tw1wef/using_obsidian_for_mathematical_knowledge_base/)

Con respecto al compilador, se habla de distribuciones, y parece ser que [LiveText]([texlive - What are the advantages of TeX Live over MiKTeX? - TeX - LaTeX Stack Exchange](https://tex.stackexchange.com/questions/20036/what-are-the-advantages-of-tex-live-over-miktex)) es la que va.

## Usar Latex con Snippets
El ir agregando capas para simplificar (o complejizar) un software implica ir sumando sintaxis y atajos para expandir con lo que se trabaja. Latex es una excelente base, como la historia ha podido demostrar, por lo que el uso de snippets no me parece tan atractiva.

Ahora bien, existen partes de su [sintaxis](https://www.latex-project.org/help/documentation/amsldoc.pdf) que pueden ser un *poco* verborrágicas, como los *environments*, donde hay que colocar la cláusula de apertura y cierre, o como la anotación de conjuntos donde hay que poner ``\mathbb{R}``. Creo que en esos lugares son útiles los snippets y tiene sentido utilizarlos. Para el resto, no sé si vale la pena, puede que las que no se escapan demasiado de su sintaxis original pueden estar bien.

## Usar Latex para la práctica
Esto es lo más controversial, vale la pena hacer este esfuerzo? Y realmente sopandrá simplemente una forma de ver mis resoluciones de forma más hermosa y no me distraerá de mi objetivo real, aprender los conceptos matemáticos?

## Otros
[Scaling up Latex preview - Help - Obsidian Forum](https://forum.obsidian.md/t/scaling-up-latex-preview/25732)