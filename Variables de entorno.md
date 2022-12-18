# Variables de entorno

Las variables de entorno hacen referencia a archivos, directorios y funciones comunes del sistema cuya ruta concreta puede variar, pero que otros programas necesitan poder conocer.

### Comandos de la clase

**Comando**

printenv

echo $variable

**Acción**

Lista todas las variables de entorno.

Imprime el contenido de la variable.

En `zsh` el archivo que contiene toda la configuración, variables y alias lo encontramos como `.zshrc`.

Para añadir rutas a nuestra variable de entorno mejor conocida como `PATH` hacemos uso de la sintaxis presentada a continuación. 

```bash
PATH=$PATH:/home/user/bin
```

Lo que hace dicha sintaxis es que concatena la información previamente guardada en esta variable más la información nueva que nosotros estamos agregando.