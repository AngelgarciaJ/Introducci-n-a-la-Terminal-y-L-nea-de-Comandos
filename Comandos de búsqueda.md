# Comandos de búsqueda

Los comandos de búsqueda nos ayudan a encontrar archivos o directorios dependiendo de su extensión, nombre, donde se encuentran ubicados, etcétera.

<aside>
💡 Esto es muy usado, por ejemplo al querer buscar archivos `.log`, estos archivos recopilan información de un archivo en ejecución.

</aside>

### Comandos de la clase

**Comando**

which {bin}

find {path} -name {name}

find {path} -type d -name {name}

find {path} -type f -name {name}

find {path} -size 20M

**Acción**

Muestra la ruta donde se encuentra el binario indicado.

Busca en una ruta el archivo indicando.

Busca en una ruta un directorio que coincida con el tipo y el nombre indicado.

Busca en una ruta un archivo que coincida con el tipo y el nombre indicado.

Busca en una ruta el archivo que pese el tamaño indicado.