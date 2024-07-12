---
fecha_creacion: 2023-09-14
---

El problema de la parada es un planteamiento que permite sin muchas complicaciones demostrar los límites de las computadoras, y por lo tanto, de la matemática en sí. Demuestra que la matemática es *indecidible*, existen problemas enunciables a los cuales no se puede dar respuesta.

## Idea
Evaluar una máquina particular cuyo dominio son todas las máquinas de Turing consigo misma para generar una paradoja.

## Hipotesis
Suponemos una máquina de Turing $h$ cuya entrada sea una máquina y un valor con el cuál se va a evaluar dicha máquina. Si la máquina provista termina, entonces devuelve 1, en caso contrario 0.

Suponemos además que tenemos otra máquina de Turing $t$ cuyo dominio es $\{0, 1\}$ y que cuando recibe 0 termina, en caso contrario no termina.

Por definición al componer estas máquinas el resultado es otra máquina de Turing. La llamaremos $h+$.

## Demostración

Intentamos evaluar $h+$ *consigo misma*. 

Suponemos que $h+$ termina. Entonces al evaluar $h+$ primero se evalua $h$, entonces  $h(h+, h+) = 1$, que compuesto con $t$ no termina. Pero entonces, al final, $h+$ no termina, por lo que $h$ se equivocó.

Suponemos que $h+$ no termina. Entonces $h(h+, h+) = 0$, y $t(0)$ termina. Pero entonces $h+$ termina. Contradicción!

Por lo tanto no hay máquina posible $h$ que sea capaz de resolver el *halting problem*. Encontramos entonces un problema enunciable pero *indecidible*.

## [[Halting problem - 01|Revisión]]