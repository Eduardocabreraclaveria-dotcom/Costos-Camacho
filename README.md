# Costos Camacho - Calculadora Packing

Aplicación web sencilla (PWA) para calcular el precio de venta de servicios de packing, considerando:

- Costo base (por lote / kilo / unidad)
- Utilidad neta deseada (después de impuesto a la renta)
- % Impuesto a la renta
- % IVA

Calcula automáticamente:

- Utilidad bruta necesaria (antes de impuestos)
- Precio neto mínimo a facturar
- IVA
- Precio total al cliente
- Margen aproximado sobre el costo

## Estructura del proyecto

- `index.html` — Aplicación principal (HTML + CSS + JS).
- `manifest.json` — Configuración PWA (nombre, iconos, colores).
- `sw.js` — Service Worker para cache y modo "app".
- `icons/icon-192.png` — Icono PWA 192x192.
- `icons/icon-512.png` — Icono PWA 512x512.

## Despliegue en Vercel

1. Crear un repositorio público en GitHub llamado **Costos Camacho**.
2. Subir todos los archivos de este proyecto al repositorio.
3. En Vercel, elegir **Import Project** y conectar el repositorio.
4. Deploy y listo: tendrás una URL pública para usar la app e instalarla como PWA.
