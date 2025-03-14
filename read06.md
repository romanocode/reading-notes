

# Respuestas read 06

# 1 ¿Qué hacen los siguientes comandos?
- `pwd` → Muestra el directorio actual en el que estás trabajando.
- `ls` → Lista los archivos y carpetas en el directorio actual.
- `cd [directorio]` → Cambia al directorio especificado.
- `mkdir [nombre]` → Crea una nueva carpeta.
- `touch [archivo]` → Crea un nuevo archivo vacío.

---

# 2 Explicación del escenario en la línea de comandos

```bash
cd projects → Entra en la carpeta projects (asumiendo que existe en el directorio actual).
mkdir new-project → Crea una nueva carpeta llamada new-project dentro de projects.
touch new-project/newfile.md → Crea un archivo vacío llamado newfile.md dentro de la carpeta new-project.
cd .. → Vuelve al directorio padre de projects.
ls projects/new-project → Muestra la lista de archivos dentro de la carpeta new-project, donde aparecerá newfile.md.
```

---

# 3 ¿Qué comando usarías en la terminal para listar todos los archivos, incluidos los archivos ocultos, en un directorio de Linux o macOS? Explica qué significan los parámetros utilizados en el comando.

- `ls` → Lista los archivos y directorios en la ubicación actual.
- `-l` → Muestra información detallada de cada archivo (permisos, propietario, tamaño, fecha de modificación).
- `-a` → Muestra todos los archivos, incluidos los ocultos (los archivos ocultos comienzan con un `.`).

