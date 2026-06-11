# Comandos de Historial y Remotos

## Git Commit

¿Que hace?
Agarra los cambios preparados y los guarda en el historial local.
un ejemplo seria:git commit -m "feat: agregar comandos"

---

## Git Log

¿Que hace?
Muestra el historial de todos los commits realizados en la rama actual.
un ejemplo seria:git log --oneline

---

## Git Fetch

¿Que hace?
Descarga los cambios nuevos del repositorio de Github sin mezclarlos con los archivos actuales.
un ejemplo seria:git fetch origin

---

## Git Pull

¿Que hace?
Descarga los cambios del servidor remoto y los fusiona automaticamente con la rama local.
un ejemplo seria:git pull origin main

---

## Git Push

¿Que hace?
Sube los commits locales al repositorio remoto para que el resto del equipo pueda verlos.
un ejemplo seria:git push origin feat/comandos-historial-remoto

---

## Git Revert

¿Que hace?
Crea un nuevo commit que deshace los cambios de un commit anterior.
un ejemplo seria:git revert HEAD

---

## Git Reset

¿Que hace?
Elimina los commit recientes del historial volviendo a un guardado viejo.
un ejemplo seria:git reset --soft HEAD~1