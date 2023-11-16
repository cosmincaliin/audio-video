# Repositorio Principal - Main Branch

Este repositorio principal combina las funcionalidades de dos ramas distintas: una rama centrada en la demostración de audio y video con captura de fotograma en blanco y negro, y otra rama centrada en un reproductor de audio con controles personalizados.

## Ramas Fusionadas

### Rama de Video

#### Demo de Audio y Video con Captura de Fotograma en Blanco y Negro

Este componente demuestra el uso de elementos de audio y video en HTML5. Incluye un archivo HTML (`index.html`) que presenta un reproductor de audio, un reproductor de video, y un botón para capturar un fotograma del video en blanco y negro. La demo utiliza archivos multimedia ubicados en la carpeta `media/` y proporciona información sobre la licencia del archivo de audio utilizado.

Instrucciones detalladas y explicaciones se encuentran en [la rama de video](#rama-de-video).

### Rama de Audio

#### Reproductor de Audio con Controles Personalizados

Este proyecto es un reproductor de audio HTML personalizado con controles visuales atractivos y un control deslizante de volumen. Permite reproducir archivos de audio, ajustar el volumen de reproducción, y muestra el nombre del archivo de audio debajo del reproductor. La demo está disponible en [este enlace](https://cosmincaliin.github.io/audio-video/).

Para más detalles sobre cómo utilizar y personalizar este reproductor, consulta [la rama de audio](#rama-de-audio).

## Rama de Video

### Demo de Audio y Video con Captura de Fotograma en Blanco y Negro

Este repositorio contiene un archivo HTML (`index.html`) que demuestra el uso de elementos de audio y video en HTML5. Además, se incluye un script JavaScript que permite capturar un fotograma del video y convertirlo a escala de grises.

#### Contenido del Repositorio

- `index.html`: El archivo principal que contiene la estructura HTML, elementos de audio y video, así como el script JavaScript para la captura de fotogramas.

- `media/`: Carpeta que contiene los archivos multimedia utilizados en la demo.
  - `techbg.mp3`: Archivo de audio en formato MP3.
  - `metro.mp4`: Archivo de video en formato MP4.
  - `metro.ogg`: Archivo de video en formato OGG.
  - `captions/`: Carpeta que contiene archivos de subtítulos en diferentes idiomas.
    - `metro-cat.vtt`: Subtítulos en catalán.
    - `metro-es.vtt`: Subtítulos en español.

#### Uso del Archivo HTML

El archivo HTML (`index.html`) está diseñado para mostrar un reproductor de audio y video, así como permitir la captura de un fotograma del video en blanco y negro.

##### Audio

El elemento de audio incluido reproduce el archivo "techbg.mp3". En caso de que el navegador no admita la reproducción de audio HTML5, se mostrará un mensaje de fallback.

##### Video

El elemento de video reproduce los archivos "metro.mp4" y "metro.ogg". Se incluyen subtítulos en catalán y español para mejorar la accesibilidad. Si el navegador no puede reproducir el video, se muestra un mensaje de fallback.

##### Captura de Fotograma

Se ha agregado un botón con el texto "Capturar Fotograma". Al hacer clic en este botón, se ejecuta un script JavaScript que captura el fotograma actual del video y lo convierte a escala de grises. El resultado se muestra en un canvas debajo del botón.

#### Licencia de los Medios Utilizados

Se proporciona información sobre la licencia del archivo de audio utilizado:
- "Background Technology" by Taj Tim
- [Licencia](https://creativecommons.org/licenses/by-nc-nd/4.0/)
- [Enlace a la Música](https://timtaj.com/royalty-free-music/background-technology)
- [Perfil del Artista](https://freemusicarchive.org/music/timtaj/contact)

#### Instrucciones para la Captura de Fotograma

1. Reproduce el video utilizando los controles proporcionados.
2. Haz clic en el botón "Capturar Fotograma".
3. El fotograma capturado en blanco y negro se mostrará en el canvas debajo del botón.

¡Disfruta explorando la demo de audio y video con funcionalidad adicional de captura de fotograma!

## Rama de Audio

### Reproductor de Audio con Controles Personalizados

Este proyecto es un reproductor de audio HTML personalizado con controles visuales atractivos y un control deslizante de volumen. Permite reproducir archivos de audio y ajustar el volumen de reproducción. Además, muestra el nombre del archivo de audio debajo del reproductor.

#### Contenido

- [Reproductor de Audio con Controles Personalizados](#reproductor-de-audio-con-controles-personalizados)
  - [Contenido](#contenido)
  - [Demo](https://cosmincaliin.github.io/audio-video/)
  - [Características](#características)
  - [Requisitos](#requisitos)
  - [Instrucciones de Uso](#instrucciones-de-uso)
  - [Personalización](#personalización)
  - [Licencia](#licencia)

#### Demo

Puedes ver una demostración del reproductor de audio personalizado en vivo [aquí](https://cosmincaliin.github.io/audio-video/).

#### Características

- Reproducción de archivos de audio.
- Controles visuales de reproducción y reinicio.
- Control deslizante de progreso.
- Control deslizante de volumen.
- Visualización del nombre del archivo de audio.
- Fondo animado de ondas.
- Soporte para navegadores web modernos.

#### Requisitos

Para utilizar este reproductor de audio personalizado, necesitas:

- Un navegador web moderno que admita HTML5.

#### Instrucciones de Uso

1. Clona o descarga este repositorio en tu sistema.

2. Abre el archivo `index.html` en tu navegador web.

3. El reproductor de audio se mostrará en la página. Puedes cargar tus propios archivos de audio en el directorio `media` y cambiar la fuente en el archivo HTML para reproducirlos.

4. Utiliza los siguientes controles:

   - Reproducir/Pausar: Haz clic en el botón "play" (triángulo) para iniciar o pausar la reproducción.
   - Reiniciar: Haz clic en el botón "replay" (círculo con flecha circular) para reiniciar la reproducción desde el principio.
   - Control deslizante de progreso: Arrastra el control deslizante de progreso para avanzar o retroceder en la pista de audio.
   - Control deslizante de volumen: Arrastra el control deslizante de volumen para ajustar el nivel de volumen.

5. El nombre del archivo de audio se muestra debajo del reproductor.

#### Personalización

Puedes personalizar el reproductor de audio siguiendo estos pasos:

- **Cambio de archivo de audio**: Coloca tus propios archivos de audio en el directorio `media` y actualiza la fuente en el archivo HTML.

- **Cambio de fondo y animación de ondas**: Puedes personalizar el fondo y la animación de ondas modificando las clases CSS en el archivo `style.css`.

- **Cambio de iconos de control deslizante de volumen**: Reemplaza la URL de los iconos en la sección CSS correspondiente en el archivo `style.css`.

#### Licencia

Este proyecto está bajo la Licencia MIT. Puedes encontrar más detalles en el archivo [LICENSE](LICENSE).
