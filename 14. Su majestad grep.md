# Su majestad: grep

`Grep` es uno de los comandos más útiles que hay en la terminal, además de ser muy potente dentro del ambiente de desarrollo de Linux.

### Pero... ¿Qué hace?

Lo que nos permite hacer es encontrar coincidencias de una búsqueda dentro de un archivo de texto o en general dentro de cualquier texto, por ejemplo un *standard output*.

Ejemplo de uso:

```bash
grep {expReg} {file}
```

Buscará todas las coincidencias de lo indicado en el parámetro primer parámetro que de hecho es una expresión regular, dentro del archivo seleccionado. 

Por defecto las búsquedas con grep son *case sensitive* si queremos que no sean así añadimos la opción de `-i`.

```bash
grep -i {expReg} {file}
```

Si queremos contar el número de ocurrencias que hay, añadimos la opción de `-c`.

```bash
grep -c {expReg} {file}
```

Encontrar todas las no coincidencias, para esto añadimos la opción de `-v`.

```bash
grep -v {expReg} {file}
```

### Bonus

Contar la cantidad de palabras de un archivo.

```bash
wc {file}
# 0000   00000    000000 {file name}
# líneas palabras bits   nombre del archivo
```

Retorna solo el número de líneas

```bash
wc -l {file}
```

Retorna solo el número de palabras.

```bash
wc -w {file}
```

Retorna solo el número de bits.

```bash
wc -c {file}
```