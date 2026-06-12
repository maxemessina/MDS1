# git log

## Funcion:

Muestra el historial completo de todos los commits realizados en la rama actual. Es fundamental para revisar la linea de tiempo, ver quien hizo que cambio, y obtener los codigos para saber a que punto especifico del proyecto regresar en caso de error.

## Comandos principales y ejemplos:

**Ver el historial resumido:**

```bash
git log --oneline
```

*Muestra una lista compacta de los commits, indicando su hash corto y el mensaje descriptivo en una sola linea.*

---

# git revert

## Funcion:

Deshace los cambios introducidos por un commit anterior de forma segura. A diferencia de otros comandos destructivos, en lugar de borrar la historia, crea un nuevo commit que aplica exactamente las modificaciones inversas.

## Comandos principales y ejemplos:

**Revertir el ultimo commit:**

```bash
git revert HEAD
```

*Genera un nuevo commit que anula todo lo que se hizo en el ultimo guardado registrado, manteniendo el historial intacto.*

---

# git reset

## Funcion:

Retrocede la linea de tiempo del proyecto a un punto anterior, eliminando los commits recientes del historial local. Debe utilizarse con precaucion, ya que altera de forma destructiva la linea de tiempo de la rama.

## Comandos principales y ejemplos:

**Retroceder un commit preservando modificaciones:**

```bash
git reset --soft HEAD~1
```

*Elimina el ultimo commit del historial de Git, pero mantiene los archivos modificados listos en el area de preparacion (stage) para volver a guardarlos.*

> **Nota sobre los flags de reset:** El uso del modificador `--soft` mantiene tus archivos a salvo. Si se utilizara `--hard`, Git borraria tanto el historial como los cambios fisicos en los archivos, perdiendo el trabajo no guardado.