# Demo de Audio y Video con Captura de Fotograma en Blanco y Negro

Este repositorio contiene un archivo HTML (`index.html`) que demuestra el uso de elementos de audio y video en HTML5. Además, se incluye un script JavaScript que permite capturar un fotograma del video y convertirlo a escala de grises.

## Contenido del Repositorio

- `index.html`: El archivo principal que contiene la estructura HTML, elementos de audio y video, así como el script JavaScript para la captura de fotogramas.

- `media/`: Carpeta que contiene los archivos multimedia utilizados en la demo.
  - `techbg.mp3`: Archivo de audio en formato MP3.
  - `metro.mp4`: Archivo de video en formato MP4.
  - `metro.ogg`: Archivo de video en formato OGG.
  - `captions/`: Carpeta que contiene archivos de subtítulos en diferentes idiomas.
    - `metro-cat.vtt`: Subtítulos en catalán.
    - `metro-es.vtt`: Subtítulos en español.

## Uso del Archivo HTML

El archivo HTML (`index.html`) está diseñado para mostrar un reproductor de audio y video, así como permitir la captura de un fotograma del video en blanco y negro.

### Audio

El elemento de audio incluido reproduce el archivo "techbg.mp3". En caso de que el navegador no admita la reproducción de audio HTML5, se mostrará un mensaje de fallback.

### Video

El elemento de video reproduce los archivos "metro.mp4" y "metro.ogg". Se incluyen subtítulos en catalán y español para mejorar la accesibilidad. Si el navegador no puede reproducir el video, se muestra un mensaje de fallback.

### Captura de Fotograma

Se ha agregado un botón con el texto "Capturar Fotograma". Al hacer clic en este botón, se ejecuta un script JavaScript que captura el fotograma actual del video y lo convierte a escala de grises. El resultado se muestra en un canvas debajo del botón.

## Licencia de los Medios Utilizados

Se proporciona información sobre la licencia del archivo de audio utilizado:
- "Background Technology" by Taj Tim
- [Licencia](https://creativecommons.org/licenses/by-nc-nd/4.0/)
- [Enlace a la Música](https://timtaj.com/royalty-free-music/background-technology)
- [Perfil del Artista](https://freemusicarchive.org/music/timtaj/contact)

## Instrucciones para la Captura de Fotograma

1. Reproduce el video utilizando los controles proporcionados.
2. Haz clic en el botón "Capturar Fotograma".
3. El fotograma capturado en blanco y negro se mostrará en el canvas debajo del botón.

¡Disfruta explorando la demo de audio y video con funcionalidad adicional de captura de fotograma!
