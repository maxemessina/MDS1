# git commit

## Función:

Es el comando encargado de confirmar y guardar de forma permanente en el historial del repositorio todos los cambios que preparamos en el *Staging Area* (con `git add`).

El commit guarda:
* Los **cambios** exactos en los archivos.
* El **autor** (quién hizo la modificación).
* La **fecha y hora** en la que se realizó.
* Un **mensaje** descriptivo.
* Un **hash** único (código alfanumérico) que identifica a ese commit.
* Una **referencia al commit anterior** para mantener la línea de tiempo.

El mensaje tiene que representar una cambio lógico, no incompleto ni un conjunto de cambios independientes.

### Comando de uso:
```bash
git commit -m "Añadir validaciones al login"