# Redirecciones: pipe operator

El `pipe operator` nos permite que el `stdout` se convierta en el `stdin` de otro comando. Ejemplo:

```bash
ls -lh | less
```

### Comandos de la clase

**Comando**

echo "Hola"

cat {file}

ls -lh | sort

cowsay {text}

{comando} | lolcat

**Acción**

Imprime en consola lo indicado.

Muestra el contenido de un archivo, también puede concatenar

Ordena la salida del comando.

Imprime una vaca diciendo el texto pasado.

Colorea la salida del comando.

Los últimos dos comandos debemos de instalarlos en nuestra terminal para tenerlos disponibles. Si estás trabajando desde MacOs se instalan de la siguiente manera.

- Lolcat
    
    ```bash
    brew install lolcat
    ```
    
- Cowsay
    
    ```bash
    brew install cowsay
    ```
    

Recuerda que para poder instalarlos a través de brew debemos de tener instalado [Homebrew](https://brew.sh/index_es) en nuestro sistema operativo que no es otra cosa que un gestor de paquetes.