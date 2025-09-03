![Vista previa de la página](./imgs/actividad0209.png)

### Tutorial para capturar una página completa con las herramientas de desarrollo de Google Chrome

1. **Abre la página en Google Chrome**:

   * Abre Google Chrome y carga la página web que deseas capturar.

2. **Accede a las herramientas de desarrollo**:

   * Haz clic derecho en cualquier lugar de la página y selecciona **"Inspeccionar"**.
   * O simplemente presiona `Ctrl + Shift + I` (Windows/Linux) o `Cmd + Option + I` (Mac) para abrir las herramientas de desarrollo.

3. **Abre la barra de comandos**:

   * En las herramientas de desarrollo, haz clic en los tres puntos verticales (más opciones) en la esquina superior derecha de la ventana de desarrollo.
   * Selecciona **"Run command"** (o presiona `Ctrl + Shift + P` / `Cmd + Shift + P`).

4. **Selecciona "Capturar captura de pantalla completa"**:

   * En la barra de búsqueda que aparece, escribe **"screenshot"**.
   * Selecciona la opción **"Capture full size screenshot"**.

5. **Guarda la captura de pantalla**:

   * Google Chrome generará automáticamente una captura de la página completa y te ofrecerá guardarla como una imagen en formato PNG.

6. **Ubicación del archivo**:

   * El archivo de imagen será descargado en tu carpeta de descargas predeterminada, o bien podrás seleccionar la ubicación de descarga en tu navegador.

### Agregar esta captura a tu `README.md`

Una vez que hayas hecho la captura, puedes agregarla a tu `README.md` de la siguiente manera:

1. **Sube la captura de pantalla a tu repositorio**:

   * Asegúrate de que la imagen que has capturado esté subida al repositorio de GitHub, en una carpeta llamada `imgs` (o alguna carpeta similar).

2. **Referenciar la imagen en el `README.md`**:

   * Para mostrar la imagen en tu archivo `README.md`, utiliza el siguiente código Markdown:

   ```markdown
   ![Captura de pantalla de la página](imgs/captura.png)
   ```

   * Asegúrate de que el nombre del archivo de la imagen coincida con el que has subido, en este caso he puesto `captura.png`, pero debes cambiarlo según el nombre de tu archivo.

### Ejemplo de `README.md`

````markdown
# Proyecto "Hello World - Newspaper / Magazine / Publisher"

Este es un proyecto de ejemplo de un periódico en línea utilizando HTML y CSS.

## Vista previa de la página

A continuación, se muestra una captura de la página completa del proyecto:

![Captura de pantalla de la página](imgs/captura.png)

## Instrucciones de instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu_usuario/tu_repositorio.git
````

2. Abre el archivo `index.html` en tu navegador para ver el proyecto en acción.

## Cómo tomar capturas de pantalla de la página completa

1. Abre la página web en **Google Chrome**.
2. Accede a las herramientas de desarrollo presionando `Ctrl + Shift + I` (Windows/Linux) o `Cmd + Option + I` (Mac).
3. En las herramientas de desarrollo, presiona `Ctrl + Shift + P` (Windows/Linux) o `Cmd + Shift + P` (Mac) para abrir la barra de comandos.
4. Escribe **"screenshot"** y selecciona **"Capture full size screenshot"**.
5. La captura se descargará automáticamente como una imagen PNG en tu carpeta de descargas.

```

Con esto, la captura de pantalla se mostrará en tu archivo `README.md` y cualquier persona que vea tu repositorio podrá visualizar cómo se ve la página completa.
```
