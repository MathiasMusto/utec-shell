# Shell Basics
Comandos basicos de shell 
## Comandos de Navegación y Listado

* `pwd` — Muestra la ruta del directorio actual.
* `ls` — Lista los archivos y carpetas del directorio actual.
* `cd` — Cambia al directorio personal ($HOME).
* `cd ~` — Cambia al directorio personal ($HOME).
* `ls -l` — Lista archivos en formato detallado (permisos, propietario, tamaño, fecha).
* `ls -la` — Lista todos los archivos, incluyendo archivos ocultos.
* `ls -lan` — Lista archivos incluyendo ocultos, mostrando los ID numéricos de usuario y grupo.
* `ls -la . .. /boot` — Lista de forma detallada e incluyendo ocultos el directorio actual, el padre y /boot.

## Gestión de Archivos y Directorios

* `file /tmp/iamafile` — Muestra el tipo de archivo de `/tmp/iamafile`.
* `ln -s /bin/ls __ls__` — Crea un enlace simbólico llamado `__ls__` que apunta a `/bin/ls`.
* `cp -u *.html ..` — Copia al directorio padre solo los archivos `.html` más recientes.
* `mv [A-Z]* /tmp/u` — Mueve archivos o directorios que inician con mayúscula a `/tmp/u`.
* `rm *~` — Elimina los archivos temporales que terminan en `~`.
* `mkdir -p welcome/to/school` — Crea la estructura de carpetas anidadas `welcome/to/school`.
* `mkdir /tmp/my_first_directory` — Crea el directorio `my_first_directory` en `/tmp`.
* `mv /tmp/betty /tmp/my_first_directory/` — Mueve `betty` dentro de `/tmp/my_first_directory/`.
* `rm /tmp/my_first_directory/betty` — Elimina el archivo `betty`.
* `rmdir /tmp/my_first_directory` — Elimina el directorio `my_first_directory` (debe estar vacío).
