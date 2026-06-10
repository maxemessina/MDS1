En este archivo van a estar todos los comandos de configuracion vistos en la materia

# Comandos de Configuración:

---

## git config

### Función:

Git requiere saber quién está realizando cada modificación en el código. `git config` configura el nombre y el correo electrónico, si no se configuran Git no permitirá guardar los commits. Esta información quedará vinculada de forma permanente al historial de cada cambio.

### Comandos principales y ejemplos:

* **Configurar el nombre de usuario global:**
    ```bash
    git config --global user.name "sebas"
    ```
    *Configura el nombre público que se mostrará como autor de los commits.*

* **Configurar el correo electrónico global:**
    ```bash
    git config --global user.email "sebas@gmail.com"
    ```
    *Configura la dirección de correo electrónico a tus contribuciones.*

* **Verificar las configuraciones activas:**
    ```bash
    git config --list
    ```
    *Muestra una lista con todas las propiedades ya configuradas en el entorno.*

> **Nota sobre el flag `--global`:** Al incluir este modificador, git guarda la configuración de manera global y no hace falta volver a ejecutar estos comandos cuando se crea un nuevo repositorio.

---

## git init

### Función:

Este comando se utiliza para crear un repositorio nuevo de manera local, o para reinicialiar uno ya existente.
Crea una carpeta oculta llamada `.git/` que contiene todo lo necesario para controlar versiones, historial, configuración, ramas, commits, staging area.
Si no es ejecutada, git no registrará nada de lo que hagas en esa carpeta.

### Ejemplo de uso:

* **Inicializar el repositorio:**
    ```bash
    git init
    ```
    *Se ejecuta estando posicionado dentro de la carpeta del proyecto que queremos empezar a trackear.*