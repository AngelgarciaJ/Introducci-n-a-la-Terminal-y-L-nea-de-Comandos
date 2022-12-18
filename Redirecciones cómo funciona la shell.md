# Redirecciones: cómo funciona la shell

![Redirecciones%20co%CC%81mo%20funciona%20la%20shell%207f8ebbf6d2e0432ba99b3351f0c5d647/2._Slides.png](Redirecciones%20co%CC%81mo%20funciona%20la%20shell%207f8ebbf6d2e0432ba99b3351f0c5d647/2._Slides.png)

En el diagrama tenemos una entrada que se le conoce como *standard input* (`stdin`) que proviene de nuestro teclado; pero que también lo podemos redirigir desde archivos de texto.

<aside>
💡 El `0` en el `stdin` se le conoce como un *file descriptor*.

</aside>

Este `stdin` entra dentro del `comando` donde tenemos dos opciones:

1. Que nos produzca un *standard output* (`stdout`). Por ejemplo cuando usamos un `ls` este `stdout` sería que nos muestre todos los directorios.
2. Que nos muestre un *standard error* (`stderr`). Por ejemplo que intentemos listar un directorio que no existe, entonces el comando nos dirá que hay un error.

Ambas salidas se manejan de manera distinta. `stdout` se maneja con un *file descriptor* con el código 1 y el `stderr` con el código 2.

### Comandos de esta clase

**Comando**

ls {folder} > {name}.txt

ls {folder} >> {name}.txt

ls {folder} 2> {name}.txt

ls {folder} > {name}.txt 2>&1

**Acción**

El listado de los archivos del directorio seleccionado se listaran en un nuevo archivo de extensión `.txt`

Si el archivo ya existe el nuevo listado se va a concatenar al contenido que ya tiene el archivo.

Redirige un `stderr` a una salida por archivo.

Redirige ambas salidas, tanto el `stdout` y `stderr`.