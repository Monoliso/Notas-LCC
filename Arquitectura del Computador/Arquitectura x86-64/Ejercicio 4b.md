Si, es necesario usar gdb en este caso, ya que para todas las operaciones el resultado está almacenado en un registro de 32 bits. Como concluimos en el ejercicio 2, el código de salida del programa se representa con 8 bits, por lo que no se puede representar correctamente en ningún resultado (excepto el h, cuyo resultado es 0).