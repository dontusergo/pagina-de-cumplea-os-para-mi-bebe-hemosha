# Para nini, con amor

Página estática de cumpleaños en español. No usa frameworks, dependencias ni proceso de compilación; `index.html` está en la raíz para que GitHub Pages lo sirva directamente.

## Contenido

- `index.html`: página y estilos.
- `assets/nini.webp`: fotografía del retrato.
- `assets/pusheen.png`: ilustración animada del fondo.
- `assets/cumpleanos-feliz.mp3`: canción del reproductor.

## Publicar en GitHub Pages

1. Crea un repositorio en GitHub y sube todos los archivos y carpetas de este proyecto, conservando `index.html` en la raíz.
2. En el repositorio, abre **Settings > Pages**.
3. En **Build and deployment**, elige **Deploy from a branch**.
4. Selecciona la rama `main` y la carpeta `/(root)`, y pulsa **Save**.
5. Espera a que termine el despliegue; GitHub mostrará la dirección pública del sitio en esa misma sección.

No configures una acción de build: es un sitio estático listo para servirse tal cual.

## Antes de publicar

Los archivos de un sitio de GitHub Pages son accesibles públicamente. Comprueba que tienes permiso para compartir la grabación MP3 y que deseas publicar la fotografía incluida.

## Personalizar

Edita las frases en `index.html`. Para cambiar la fotografía o la ilustración, reemplaza el archivo correspondiente dentro de `assets/` y conserva su nombre, o actualiza su ruta en `index.html`.
