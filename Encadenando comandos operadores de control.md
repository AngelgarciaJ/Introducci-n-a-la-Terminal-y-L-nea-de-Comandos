# Encadenando comandos: operadores de control

En la terminal podemos encadenar comandos para que se ejecuten de forma síncrona; se realiza separando cada comando por una `;`.

```bash
ls; mkdir NewFolder; cal
```

También los podemos ejecutar de manera asíncrona, esto significa que por cada comando que se ejecute se abrirá una `shell` o línea de comandos en segundo plano. Esto permite ejecutar comandos de forma paralela.

```bash
ls & date & cal
```

Podemos correr comandos de forma condicional, esto quiere decir que por ejemplo, si se cumple un comando queremos que se ejecute un segundo.

```bash

# AND
mkdir test && cd test
# OR
cd test || touch file.txt
```