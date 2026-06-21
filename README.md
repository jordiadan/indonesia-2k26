# Indonesia 2k26

Repo estático para publicar mapas y pequeñas herramientas del viaje con GitHub Pages.

## Estructura

- `index.html`: portada pública con enlaces.
- `maps/munduk.html`: mapa de decisión de Munduk.
- `.github/workflows/pages.yml`: despliegue gratis con GitHub Actions + GitHub Pages.

## Añadir más HTMLs

1. Añade un nuevo archivo dentro de `maps/`, por ejemplo `maps/gili-air.html`.
2. Añade una tarjeta en `index.html` apuntando a ese archivo.
3. Haz push a `main`. GitHub Actions desplegará la web.

## URL esperada

Cuando Pages esté activo, la web debería quedar en:

`https://jordiadan.github.io/indonesia-2k26/`

Para que Marta lo vea sin login y sin coste, el sitio debe ser público. La forma más simple es que el repo sea público o que tu plan de GitHub permita Pages desde repos privados.
