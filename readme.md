# repo02

En este ejercicio, se creó un repositorio remoto en GitHub, se clonó a mi ordenador, se añadió un archivo `readme.md`, se realizaron commits y se documentaron los pasos seguidos.

## Pasos realizados

1. **Creación del repositorio remoto:** Se creó el repositorio `repo02` en GitHub a través de la interfaz web.

2. **Clonación del repositorio:** Se clonó el repositorio remoto a mi ordenador usando el comando `git clone <URL_del_repositorio>`.

3. **Creación del archivo `readme.md`:** Se creó el archivo `readme.md` con el comando `touch readme.md` (en macOS/Linux) o `type nul > readme.md` (en Windows).

4. **Edición del archivo `readme.md`:** Se añadió contenido al archivo `readme.md` usando un editor de texto.

5. **Añadir al "staging area":** Se añadió el archivo `readme.md` al "staging area" con el comando `git add readme.md`.

6. **Creación del commit:** Se creó un commit con el mensaje "Añadido archivo readme.md inicial" usando el comando `git commit -m "Añadido archivo readme.md inicial"`.

## Comandos y funcionalidades aprendidas

Durante el aprendizaje de Git, se utilizaron los siguientes comandos y funcionalidades:

### Staging Area (Área de Preparación)

El "staging area" es un área intermedia donde se preparan los cambios antes de confirmarlos (commit).

*   `git add <archivo>`: Añade el archivo especificado al "staging area".
*   `git add .`: Añade todos los cambios del directorio actual al "staging area".
*   `git rm --cached <archivo>`: Elimina el archivo del "staging area" pero lo mantiene en el directorio de trabajo.

### Commits (Confirmaciones)

Los commits son instantáneas del repositorio en un momento determinado.

*   `git commit -m "Mensaje del commit"`: Crea un nuevo commit con el mensaje especificado.
*   `git commit -a -m "Mensaje del commit"`: Añade todos los cambios y crea un commit con el mensaje especificado.
*   `git log`: Muestra el historial de commits.

### Otros comandos útiles

*   `git status`: Muestra el estado del repositorio.
*   `git diff`: Muestra las diferencias entre el directorio de trabajo y el "staging area".
*   `git pull`: Descarga los cambios del repositorio remoto y los fusiona con la rama local.
*   `git push`: Envía los commits locales al repositorio remoto.

## Enlaces útiles

*   Manual de Markdown: [https://www.markdownguide.org/](https://www.markdownguide.org/)
