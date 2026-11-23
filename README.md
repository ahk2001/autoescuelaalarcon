# Autoescuela Alarcón — Albacete

Sitio web oficial de **Autoescuela Alarcón** en **Av. Ramón Menéndez Pidal, nº 11, 02005 Albacete (España)**.

## Estructura del Proyecto

- `index.html`: Landing page oficial de alta conversión, responsive y autocontenida.
- `assets/`: Logotipo oficial, banners (desktop/mobile), flota Hyundai i30 y galería de alumnos aprobados.
- `docs/`: Dossiê estratégico y datos de referencia (excluidos de indexación vía `robots.txt`).
- `.github/workflows/deploy.yml`: Pipeline automatizado de despliegue seguro en GitHub Pages (`Least Privilege`).
- `vercel.json`: Cabeceras de seguridad HTTP (`HSTS`, `X-Frame-Options`, `X-Content-Type-Options`, `Referrer-Policy`, `Permissions-Policy`) y caché optimizada para `/assets/`.
- `robots.txt` y `sitemap.xml`: Configuración SEO lista para producción.
