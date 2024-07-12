---
fecha_creacion: 2024-04-30
---
La multiplexación permite a un proceso atender "al mismo tiempo" a varios clientes. La idea es que un proceso agregue a una estructura manejada por el kernel los clientes que quiere atender. Luego se quedará esperando a que alguno necesite un servicio.
Depende de la implementación esta idea puede escalar a una gran cantidad.

 - [[epoll]] - Implementación moderna de Linux.
 - [[select]] - Implementación antigua universal.