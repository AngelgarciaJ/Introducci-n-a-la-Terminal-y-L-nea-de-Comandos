# Modificando permisos en la terminal

El usuario más privilegiado es el `root` ya que tiene permisos para hacer básicamente de todo.8

Para modificar los permisos en la terminal podemos hacer uso del comando `chmod` con los diferentes modos vistos previamente.

- Modificando permisos con el modo octal
    
    ```bash
    chmod 755 {file_name}
    ```
    
- Quitando permisos de lectura con el modo simbólico
    
    ```bash
    chmod u-r {file_name}
    ```
    
- Dando permisos de lectura con el modo simbólico
    
    ```bash
    chmod u+r {file_name}
    ```
    

### Comandos de la clase

**Comando**

whoami

id

su root

sudo {comando}

passwd

**Acción**

Devuelve el nombre del usuario actual.

Devuelve los grupos a los que pertenece el usuario.

Cambia el usuario al usuario root

Da permisos de root para el comando indicado.

Cambia la contraseña del usuario actual.