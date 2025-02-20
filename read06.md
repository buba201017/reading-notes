## Comandos en Linux

### Explicación de los comandos:

1. **`pwd`**: Muestra la ruta completa del directorio de trabajo actual. Es útil para conocer en qué ubicación te encuentras dentro del sistema de archivos.

2. **`ls`**: Lista los archivos y directorios contenidos en el directorio actual. Sin opciones adicionales, no muestra los archivos ocultos (aquellos cuyo nombre comienza con un punto).

3. **`cd`**: Cambia el directorio de trabajo actual al especificado. Por ejemplo, `cd carpeta` te moverá al directorio llamado "carpeta" dentro del directorio actual.

4. **`mkdir`**: Crea un nuevo directorio con el nombre especificado. Por ejemplo, `mkdir nueva-carpeta` creará un directorio llamado "nueva-carpeta" en el directorio actual.

5. **`touch`**: Crea un archivo vacío con el nombre especificado o actualiza la fecha y hora de modificación si el archivo ya existe. Por ejemplo, `touch archivo.txt` creará un archivo llamado "archivo.txt" en el directorio actual.

---

### Explicación del escenario:

Analicemos qué sucede al ingresar los siguientes comandos en la línea de comandos:

```sh
cd projects
mkdir new-project
touch new-project/newfile.md
cd ..
ls projects/new-project
```

1. `cd projects`: Cambia el directorio de trabajo actual al directorio "projects". Si este directorio no existe o no está en la ruta actual, se producirá un error.

2. `mkdir new-project`: Dentro del directorio "projects", crea un nuevo directorio llamado "new-project".

3. `touch new-project/newfile.md`: Crea un archivo vacío llamado "newfile.md" dentro del directorio "new-project".

4. `cd ..`: Retrocede al directorio padre del actual, es decir, vuelve del directorio "projects" al directorio que lo contiene.

5. `ls projects/new-project`: Lista el contenido del directorio "new-project" dentro de "projects". Debería mostrar "newfile.md" como el único archivo presente.

---

### Listar archivos ocultos en Linux/macOS:

Para listar todos los archivos en un directorio, incluyendo los ocultos, se utiliza el siguiente comando:

```sh
ls -a
```

#### Explicación de los parámetros:

- **`-a`**: Esta opción indica a `ls` que muestre todos los archivos, incluyendo aquellos ocultos (los que comienzan con un punto `.`).

Por ejemplo:

```sh
ls -a /ruta/al/directorio
```

Este comando mostrará todos los archivos y directorios, visibles y ocultos, en la ruta especificada.

> **Nota:** Los archivos ocultos suelen ser configuraciones o archivos del sistema, por lo que es importante manejarlos con precaución.
