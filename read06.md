

# RESPUESTAS

# 1. ¿Qué hacen los siguientes comandos?

- `pwd` → Muestra la ruta absoluta del directorio en el que te encuentras actualmente.
- `ls` → Lista los archivos y carpetas dentro del directorio actual.
- `cd [directorio]` → Cambia al directorio especificado. 
- `mkdir [nombre]` → Crea una nueva carpeta con el nombre especificado.
- `touch [archivo]` → Crea un nuevo archivo vacío con el nombre especificado.

---

# 2 ¿Puedes explicar qué sucede en el siguiente escenario si ingresas estos comandos y argumentos en la línea de comandos? (Los argumentos son instrucciones adicionales dadas a un comando).

```bash
- cd projects → Entra en la carpeta projects (asumiendo que existe en el directorio actual).
- mkdir new-project → Crea una nueva carpeta llamada new-project dentro de projects.
- touch new-project/newfile.md → Crea un archivo vacío llamado newfile.md dentro de la carpeta new-project.
- cd .. → Vuelve al directorio padre de projects.
- ls projects/new-project → Muestra la lista el contenido de la carpeta new-project, mostrando newfile.md.

---

# 3 ¿Qué comando usarías en la terminal para listar todos los archivos, incluidos los archivos ocultos, en un directorio de Linux o macOS? Explica qué significan los parámetros utilizados en el comando.

ls → Lista los archivos y directorios en la ubicación actual.
-l → Muestra información detallada de cada archivo (permisos, propietario, tamaño, fecha de modificación).
-a → Muestra todos los archivos, incluidos los ocultos (los archivos ocultos comienzan con un .)