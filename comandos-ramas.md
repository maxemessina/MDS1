# Comandos de Historial y Remotos

## Git Commit

¿Que hace?
Toma una "foto" de los cambios preparados y los guarda permanentemente en el historial local.
un ejemplo seria:git commit -m "feat: agregar comandos"

---

## Git Log

¿Que hace?
Muestra el historial completo de todos los commits realizados en la rama actual.
un ejemplo seria:git log --oneline

---

## Git Fetch

¿Que hace?
Descarga los cambios nuevos del repositorio remoto (GitHub) sin mezclarlos con tus archivos actuales.
un ejemplo seria:git fetch origin

---

## Git Pull

¿Que hace?
Descarga los cambios del servidor remoto y los fusiona automáticamente con tu rama local actual.
un ejemplo seria:git pull origin main

---

## Git Push

¿Que hace?
Sube tus commits locales al repositorio remoto para que el resto del equipo pueda verlos.
un ejemplo seria:git push origin feat/comandos-historial-remoto

---

## Git Revert

¿Que hace?
Crea un nuevo commit que deshace de forma segura los cambios de un commit anterior.
un ejemplo seria:git revert 3a5f8b2

---

## Git Reset

¿Que hace?
Retrocede la línea de tiempo del proyecto a un punto anterior, eliminando los commits recientes del historial.
un ejemplo seria:git reset --hard HEAD~1