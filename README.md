# Biai · Asistente de WhatsApp para tu negocio (partner de LAIA)

Página de venta de **Biai S.A.C.**, partner oficial de LAIA: seguimiento, automatizaciones a medida, un agente que propone mejoras y pestañas con lo que se activa en cada rubro (clínicas, tiendas, servicios, cursos, inmobiliarias).

- En línea: https://gabrielbarrientos99.github.io/biai-laia/
- Estilos de diseño para revisar: `?estilo=editorial` (por defecto), `?estilo=afiche`, `?estilo=libreta`.

Esta carpeta es la **versión construida** (HTML, JS y CSS listos). El código fuente vive en el proyecto `biai-web` (repositorio evolai), en `src/pages/LaiaVenta.tsx` y `src/app/temasVenta.ts`, hecho con la librería Astryx. Para actualizar:

```bash
cd biai-web
MSYS_NO_PATHCONV=1 npx vite build --base /biai-laia/ --outDir ../biai-laia --emptyOutDir
# luego dejar solo laia.html (renombrado a index.html), assets/ y laia/
```
