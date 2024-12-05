# Mi Bitácora - Taller de Páginas Web

Este proyecto es una plantilla básica de una página web diseñada para que los niños aprendan a crear y personalizar páginas web utilizando **HTML** y **CSS**. La página tiene un enfoque de bitácora personal, donde los participantes pueden describirse, compartir sus expectativas del taller y registrar lo aprendido día a día.

## Características

- **Perfil Personal**: Sección inicial para que los niños incluyan su foto, una breve descripción personal y sus expectativas del taller.
- **Bitácoras por Día**: Espacio dedicado a registrar las actividades y aprendizajes de cada día del taller.
- **Navegación Fácil**: Un menú en la parte superior permite navegar entre el perfil y las bitácoras.
- **Wallpaper**: Un fondo con imagen difuminada para darle un toque moderno y atractivo a la página.
- **Estilo Responsive**: Diseño adaptado para verse bien en diferentes dispositivos.

## Archivos del Proyecto

- **`index.html`**: Archivo principal que contiene la estructura de la página.
- **`styles.css`**: Archivo que define los estilos de la página, incluyendo colores, fuentes y diseño visual.
- **`fondo.jpg`**: Imagen de fondo estilo wallpaper (debe añadirse manualmente).

## Cómo Usarlo

1. **Descarga o Clona el Proyecto**
   - Descarga este repositorio o clónalo en tu máquina local:
     ```bash
     git clone https://github.com/usuario/mi-bitacora.git
     ```

2. **Coloca tu Imagen de Fondo**
   - Asegúrate de tener una imagen de fondo llamada `fondo.jpg` en el directorio `/media` que los archivos HTML y CSS.
   - Si deseas usar otra imagen, actualiza la línea en `styles.css`:
     ```css
     background-image: url('nombre-de-tu-imagen.jpg');
     ```

3. **Edita el Archivo `index.html`**
   - Completa los campos `[ ]` en la sección de perfil con tu información personal y expectativas.
   - Agrega más entradas de bitácora copiando y pegando el siguiente bloque:
     ```html
     <article class="entrada">
         <h3>Día X: [Título del Día]</h3>
         <p>[Descripción de lo aprendido o realizado]</p>
     </article>
     ```

4. **Abre el Proyecto en tu Navegador**
   - Simplemente abre el archivo `index.html` en tu navegador favorito para ver la página.

## Personalización

- **Fondo Difuminado**: Puedes ajustar el desenfoque del fondo cambiando el valor de `blur` en esta línea del archivo `styles.css`:
  ```css
  backdrop-filter: blur(10px);
