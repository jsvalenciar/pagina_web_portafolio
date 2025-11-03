# TODO: Cambiar imágenes repetidas en la página "Portafolio"

## Información Recopilada
- Las imágenes en "Portafolio" para "primer proyecto" (home-bg.jpg) y "segundo proyecto" (about-bg.jpg) están repetidas de otras páginas.
- Se cambiarán a nuevas imágenes únicas temáticas de alta definición desde Unsplash.
- Temas: Primer proyecto (plataforma de notas) - educación/notas; Segundo proyecto (sitio web de mantenimientos médicos) - medicina/mantenimiento.

## Plan Detallado
- Descargar nuevas imágenes usando `curl` para crear archivos nuevos en `img/`.
- Nuevas URLs seleccionadas de Unsplash:
  - `project1-bg.jpg`: Imagen temática de educación/notas.
  - `project2-bg.jpg`: Imagen temática de medicina/mantenimiento.
- Actualizar `portfolio.html` para usar estas nuevas imágenes.

## Pasos a Ejecutar
- [x] Descargar `project1-bg.jpg` desde URL temática de educación.
- [x] Descargar `project2-bg.jpg` desde URL temática de medicina.
- [x] Actualizar `portfolio.html` para cambiar src de las imágenes de proyectos.

## Archivos Dependientes
- `portfolio.html`: Cambiar src de las imágenes.

## Pasos de Seguimiento
- [x] Verificar que las imágenes se descargaron correctamente listando el contenido de `img/`.
- [x] Probar la plataforma abriendo `index.html` en un navegador para confirmar que las nuevas imágenes se cargan en "Portafolio".
