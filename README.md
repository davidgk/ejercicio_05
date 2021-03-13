# ejercicio_05
Ejercicio sobre investigacion de comandos en docker


### HEALTHCHECK

Este comando sirve para agregar un monitoreo del container ó por default para inhabilitar si existen previos. 

En el caso de estar habilitado se ejecuta cada cierto intervalo de tiempo, devolviendo 0 si todo esta ok.
Puede haber 1 solo de estos comnados por dockerfile

Puede ser 
HEALTHCHECK CMD /bin/check-running
HEALTHCHECK CMD ["check-running"] // como un entry point.


Further reading on 
https://docs.docker.com/engine/reference/builder/#healthcheck

### ONBUILD


Agrega comportamiento a ser agregado luego del build. Se suele hacer cuando la imagen va aser usada como base para otro build. ( no me quedo claro esto.)

Further reading on 
https://docs.docker.com/engine/reference/builder/#onbuild

### VOLUME

Es para montar volumenes,  ya sea del host nativo o de otro container.
( no me quedo claro esto.)

Further reading on 
https://docs.docker.com/engine/reference/builder/#volume
https://docs.docker.com/storage/volumes/