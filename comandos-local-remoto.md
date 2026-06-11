# Comandos Locales y Remotos

Los comandos locales y remotos sirven para manejar el trabajo en Git. Los comandos locales son para guardar, revisar y deshacer cambios en el historial de la computadora. Los comandos remotos, son para sincronizar el codigo con el servidor de GitHub.

## Guardado de Historial Local

### git commit

¿Que hace?
Agarra los cambios preparados y los guarda en el historial local.

Un ejemplo seria: `git commit -m "feat: agregar comandos"`

---

### git commit --amend

¿Que hace?
Modifica el ultimo commit hecho.

Un ejemplo seria: `git commit --amend -m "feat: agregar bien los comandos"`

---

### git log

¿Que hace?
Muestra el historial de todos los commits realizados en la rama actual.

Un ejemplo seria: `git log --oneline`

---

## Sincronización con GitHub

### git fetch

¿Que hace?
Descarga los cambios nuevos del repositorio de Github sin mezclarlos con los archivos actuales.

Un ejemplo seria: `git fetch origin`

---

### git pull

¿Que hace?
Descarga los cambios del servidor remoto y los fusiona automaticamente con la rama local.

Un ejemplo seria: `git pull origin main`

---

### git push

¿Que hace?
Sube los commits locales al repositorio remoto para que el resto del equipo pueda verlos.

Un ejemplo seria: `git push origin feat/comandos-local-remoto`

---

## Deshacer Cambios y Errores

### git revert

¿Que hace?
Crea un nuevo commit que deshace los cambios de un commit anterior.

Un ejemplo seria: `git revert HEAD`

---

### git reset

¿Que hace?
Elimina los commit recientes del historial volviendo a un guardado viejo.

Un ejemplo seria: `git reset --soft HEAD~1`