# Órbita

Sitio académico de exploración espacial desarrollado con HTML5 y CSS3 para el curso **Conceptualización de servicios en la nube**.

- **Estudiante:** Elena Aurora Islas Martinez
- **Código:** 212487959
- **Contacto:** auroraislasmtz@gmail.com

## Abrir el sitio

Descarga o clona el repositorio y abre `dist/index.html` en tu navegador. Conserva la carpeta `dist` completa para cargar los estilos y las imágenes. No requiere instalación de dependencias ni servidor; los enlaces externos requieren conexión a internet.

## Archivos

| Archivo | Contenido |
| --- | --- |
| `dist/index.html` | Página principal con contenedor, encabezado, logo, enlace a video y datos de identificación. |
| `dist/styles.css` | Diseño adaptable e imagen de fondo. |
| `dist/assets/logo-orbita.svg` | Logo vectorial original del proyecto. |
| `dist/assets/universo.jpg` | Imagen del centro galáctico de NASA, PIA12348. |
| `dist/procedimiento.html` | Documentación de la actividad y fuentes consultadas. |
| `Staticfile` | Configuración para que Railpack sirva el contenido de `dist` en Railway. |
| `PROCEDIMIENTO.txt` | Versión en texto de la documentación. |
| `LEEME.txt` | Instrucciones de la entrega local. |

La carpeta `dist` contiene el código estático del sitio y se conserva en el repositorio.

## Actividad y documentación

Se completaron el desarrollo de la interfaz y la consulta del [Quick Start Tutorial de Railway](https://docs.railway.com/quick-start), como recurso de introducción equivalente a “Getting Started”. La plataforma elegida para alojar el sitio es **Railway**. La estudiante realizará la publicación por separado; no se ha ejecutado un despliegue desde esta entrega.

Consulta [el procedimiento en texto](PROCEDIMIENTO.txt) o [la documentación HTML](dist/procedimiento.html) para revisar los requisitos y las referencias oficiales.

## Publicar en Railway

1. En Railway, crea un proyecto con la opción de repositorio de GitHub y selecciona `Houdinidecat/Orbit`.
2. Autoriza a la integración de Railway a acceder al repositorio cuando lo solicite.
3. Conserva la raíz del repositorio como directorio de trabajo. El archivo `Staticfile` contiene `root: dist`, por lo que Railpack detecta el sitio estático y prepara Caddy para servirlo. No necesita comandos personalizados de construcción ni de inicio.
4. Inicia el despliegue y comprueba sus registros.
5. En la configuración del servicio, genera un dominio y revisa la página, los enlaces, las imágenes y los datos de identificación.

GitHub conserva el código y Railway publica la página web. **No hace falta activar GitHub Pages ni mantener un segundo alojamiento.** La configuración estática se basa en la [documentación de Railpack](https://railpack.com/languages/staticfile/).

## Créditos

La imagen de fondo procede de la biblioteca de NASA: [PIA12348 — Great Observatories Unique Views of the Milky Way](https://images.nasa.gov/details/PIA12348). El logo de Órbita es una ilustración vectorial original creada para esta actividad. El sitio es un proyecto académico y no representa a NASA.
