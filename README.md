# Biai · Asistente de WhatsApp para tu negocio (partner de LAIA)

Página de venta de **Biai S.A.C.**, partner oficial de LAIA.

- En línea: https://gabrielbarrientos99.github.io/biai-laia/
- Estructura: título → 3 videos de publicidad → cifras → caso real en 5 pasos → chat simulado por rubro → 3 planes (Básico S/ 249, Estándar S/ 899, Premium S/ 1,199 + acompañamiento opcional S/ 300) con pago por QR → preguntas.
- Píxel de Meta "Biai - Pixel web" (1138176152527787): `PageView`, `ViewContent`, `Contact`, `CustomizeProduct`, `InitiateCheckout`, `AddPaymentInfo`.
- Los chats, flyers y videos de ubicación del chat son **ejemplos con negocios y datos ficticios**. Las capturas del caso real tienen difuminados los datos de pacientes y de la clínica.

Esta carpeta es la **versión construida** (HTML, JS y CSS listos). El código fuente está en `biai-web` (repositorio evolai): `laia.html`, `src/pages/LaiaVenta.tsx` y `src/app/temasVenta.ts`, hecho con la librería Astryx. Para actualizar:

```
cd biai-web
npx vite build --base /biai-laia/ --outDir <carpeta temporal> --emptyOutDir
# copiar laia.html como index.html, los assets/ que usa y los archivos de laia/ que usa la página
```
