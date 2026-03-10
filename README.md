# Herramientas de Mios

Este repositorio contiene una colección de herramientas web ligeras construidas con **HTML**, **Vanilla JavaScript** y **Tailwind CSS** (cargado vía CDN). Cada herramienta está empaquetada en un único archivo HTML, lo que permite usarlas sin dependencias adicionales.

## Herramientas incluidas
- **Prisma Viewer** – visualiza esquemas Prisma.
- **cURL Disector** – analiza comandos `cURL`.
- **TimeStream Visualizer** – inspecciona flujos temporales.
- **HTML Viewer** – renderiza HTML introducido por el usuario.
- **HAR Analyzer** – inspecciona archivos HAR con vista de waterfall y análisis de JSON.

## Contribuir
1. **Fork** este repositorio.
2. Añade una nueva herramienta creando un archivo `tools/<nombre>.html` siguiendo el mismo patrón (HTML + Tailwind CDN).
3. Actualiza `index.html` para incluir un nuevo **card** que enlace a tu herramienta.
4. Envía un **Pull Request**.

¡Todas las contribuciones son bienvenidas!

## Despliegue rápido en Cloudflare Pages
Haz clic en el botón **Deploy to Cloudflare Pages** en la página principal (`index.html`) o visita el repositorio en GitHub y conéctalo a Cloudflare Pages para obtener un sitio estático con un solo clic.
