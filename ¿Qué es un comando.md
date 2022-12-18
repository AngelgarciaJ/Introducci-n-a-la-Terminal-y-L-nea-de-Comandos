# ¿Qué es un comando?

Un comando puede ser cuatro cosas:

1. Un programa ejecutable.
2. Un comando de utilidad de la `shell`.
3. Una función de `shell`.
4. Un alias.

<aside>
💡 El comando `type` es un comando que nos permite analizar la naturaleza de otros comandos.

</aside>

Para crear alias en la terminal podemos hacer uso de la palabra reservada `alias`, este nos crea un alias temporal para la sesión actual en la que estamos trabajando; hacerlo persistente se verá en una siguiente sección.

```bash
alias l="ls -lh"
```

### Comandos de esta clase

**Comando**

help {comando}

man {comando}

info {comando}

whatis {comando}

**Acción**

Muestra información sobre cómo usar un comando (BASH).

Muestra el manual del comando indicado.

Muestra el manual del comando indicado.

Muestra una descripción corta del comando indicado.