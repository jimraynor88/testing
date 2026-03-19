# testing

Repositorio para experimentar con ProperDocs, temas Material y Curriculum-Vitae, y plugins.

## Estructura

- `properdocs.yml`: Configuración principal.
- `docs/`: Archivos Markdown.
- `.github/workflows/deploy.yml`: Workflow para construir y desplegar a GitHub Pages.

## Cómo usar

1. Clona este repositorio.
2. Ejecuta `./setup_github.sh` (si no lo has hecho ya).
3. Haz commit y push a la rama `main`.
4. En GitHub, ve a Settings > Pages y configura:
   - Source: Deploy from a branch
   - Branch: `gh-pages` / (root)
   - Custom domain: `testing.jim88.pp.ua` (y marca Enforce HTTPS si tienes SSL)
5. Asegúrate de que tu dominio `testing.jim88.pp.ua` tenga un registro CNAME apuntando a `jimraynor88.github.io`.

El sitio se desplegará automáticamente con cada push.
