# Serenazgo Conectado — Miraflores (Arequipa)

Prototipo web demostrativo basado en la presentación del problema de atención ciudadana del Serenazgo de Miraflores, Arequipa.

## Cómo abrir

Abre `prototipo.html` en Chrome, Edge o Firefox. Funciona sin servidor, sin npm y sin backend. Se almacena el historial simulado en `localStorage`.

## Código fuente

- `src/app.ts`: interfaz, navegación y lógica de demostración en TypeScript.
- `src/styles.css`: estilos y adaptabilidad móvil.
- `tsconfig.json`: configuración del compilador TypeScript.

Para recompilar el JavaScript, instala TypeScript globalmente y ejecuta `tsc -p tsconfig.json`. El archivo resultante estará en `dist/app.js`. La versión `prototipo.html` incluye el JS compilado y los estilos integrados.

## Características

1. Botón de alerta con cancelación en 3 segundos.
2. Historial de reportes y estados Recibida / En camino / Atendida.
3. Mapa conceptual ilustrativo con unidades simuladas.
4. Avisos comunitarios de ejemplo.
5. Calificación y comentarios simulados.

**Importante:** prototipo académico no operativo. No envía avisos ni información a la municipalidad ni a emergencias. El mapa no ofrece posiciones reales ni debe usarse para decisiones de seguridad.
