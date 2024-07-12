---
fecha_creacion: 2023-12-12
---
## Definición
El exponente está *sesgado* para simplificar la representación de exponentes negativos. Nuestro punto de referencia es el $0 = 127 = 01111111$. Así, sumando o restando ese número se puede obtener cualquier entero entre $[-126, 127]$ (creo).

## A partir de un decimal
Está claro que el bit más pesado de su forma binaria va a estar implícito. Entonces hay que "mover la coma" hasta cubrir toda la parte entera. Para ello, si queremos "moverla" hacia la derecha tenemos que agrandar su parte entera, por ello multiplicamos por una potencia entera de 2 (ej: $2^2$).

Entiendo entonces, que el exponente negativo está para representar con mucha precisión números entre $[0, 1]$, mientras que los números denormalizados permiten alta precisión entre $[0, 1]$.