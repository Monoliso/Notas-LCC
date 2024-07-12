---
fecha_creacion: 2023-12-12
---
## Implementación
Como su nombre lo indica, esta implementación separa la memoria en páginas que permiten manipular más fácilmente la memoria.

Las páginas físicas son un espacio en la memoria con un determinado tamaño. Estas páginas están asociadas a una dirección *virtual* que permite obtener la dirección física cuando se necesita.
Las páginas virtuales están indexadas en una tabla de páginas que permiten:
 1. Determinar si la dirección está en la memoria secundaria con un bit de validez.
 2. Obtener, en caso válido, la página física.

Ahora bien, algo que me parece confuso y que parece ser igual en toda la bibliografía es que no hay una "página" virtual, sino que la misma se trata de  la entrada en la tabla de páginas. Lo que hay es un número de página virtual, que es el índice en la tabla. Luego, con eso, se obtiene (ahora sí) la dirección de una página física y se indexa el desplazamiento para obtener la dirección final. Todo esto en el caso donde sea de un solo nivel.

En la vida real la implementación de las direcciones virtuales utiliza tablas multinivel, permitiendo almacenar menos entradas en la tabla principal.