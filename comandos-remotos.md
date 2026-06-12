# git fetch

## Funcion:

Descarga los cambios nuevos del repositorio remoto de GitHub a tu entorno local, sin mezclarlos ni alterar tus archivos actuales de trabajo. Es para revisar las actualizaciones del equipo antes de integrarlas a tu codigo.

## Comandos principales y ejemplos:

**Descargar cambios del repositorio remoto:**

```bash
git fetch origin
```

*Sincroniza el estado del servidor remoto con tu computadora sin modificar tu rama local.*

---

# git pull

## Funcion:

Descarga los cambios del servidor remoto y los fusiona automaticamente con la rama local activa. En la practica, es la combinacion de ejecutar un `fetch` e inmediatamente despues un `merge`.

## Comandos principales y ejemplos:

**Actualizar la rama local:**

```bash
git pull origin main
```

*Trae las actualizaciones de la rama principal del servidor remoto y las integra directamente a tu entorno de trabajo.*

---

# git push

## Funcion:

Sube los commits locales que guardaste en tu computadora al repositorio remoto de GitHub. Esto hace que el resto del equipo pueda ver, revisar y descargar tus modificaciones.

## Comandos principales y ejemplos:

**Subir cambios al remoto:**

```bash
git push origin feat/comandos-local-remoto
```

*Envia el historial local de la rama en la que estas trabajando hacia el servidor remoto (origin).*