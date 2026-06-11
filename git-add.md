# git add

## Función:

Este es el comando que le dice a Git que queremos incluir actualizaciones de un archivo en particular, de varios, o de todos, en el próximo guardado que hagamos.

## Comandos principales y ejemplos:

* **Agregar un archivo específico:**
    ```bash
    git add ejemplo.md
    ```
    *Mueve los cambios del archivo desde Working Directory hasta Staging Area y deja los cambios preparados para el commit.*

* **Agregar todos los cambios a la vez:**
    ```bash
    git add .
    ```
    *El punto (`.`) le indica a Git que tome absolutamente todos los archivos nuevos o modificados del directorio actual y los mueva al Staging Area.*