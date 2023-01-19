# Instalación
1. **Descomprimimos el ZIP**. Se ha creado una carpeta llamada `openocd` con varias carpetas dentro (**¡atención, el programa de compresión puede que cree una carpeta llamada “openocd” de la que cuelga otra llamada “openocd”. Es esta última la que nos interesa copiar!**).

2. **Copiamos sin cambiar el nombre la carpeta** `openocd` descomprimida en **`C:\Program Files\`** (Equipo → nombre_de_usuario → Archivos de programa).

3. **Introducimos esta ruta la `C:\Program Files\openocd\bin\openocd.exe` en el fichero `launch.json`** de nuestros proyectos, en la variable ***serverpath***. *En los proyectos que les proporcionamos de la asignatura ya está incluida*, **pero es necesario añadirla si creamos un proyecto desde cero.** 