# W. Wilfredo Chacón Peluquerías — Sitio Web

## Cómo publicar en Hostinger
1. Sube todo el contenido de esta carpeta (incluyendo .htaccess) al directorio raíz `public_html` de tu hosting vía FTP o el Administrador de Archivos.
2. El archivo `.htaccess` ya está configurado para el manejo óptimo de caché.
3. Usa FileZilla u otro cliente FTP para la carga.

## Personalizar imágenes
Reemplaza las imágenes de Unsplash en el HTML con tus propias fotos:
- Hero: busca `unsplash.com/photo-1522337360788` y reemplaza la URL
- Servicios: las tarjetas usan clases `.svc-maquillaje`, `.svc-corte`, etc.
- Galería: busca las URLs en la sección `#galeria`

## Videos de YouTube
En la sección Galería, reemplaza el iframe de YouTube con tu canal o playlist real:
```
src="https://www.youtube.com/embed/TU_VIDEO_ID"
```

## Logo personalizado
El logo está creado como SVG inline. Puedes reemplazarlo con tu logo real en formato SVG o PNG.
