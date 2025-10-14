# Monitor Dólar ARS — Bandas del Gobierno + Bollinger

App 100% estática (HTML + JS) que corre en el navegador.

## Funcionalidades
- Cotizaciones en vivo: Oficial, MEP, CCL y Blue.
- Brechas vs Oficial.
- Gráfico histórico con Bandas de Bollinger (SMA + σ).
- Bandas del Gobierno (Oficial): piso/techo dinámicos (base 11/04/2025: $1000/$1400) con deriva ±1% mensual.
- Proyección configurable (meses) para piso/techo.
- Botón Auto‑ajustar Bollinger.

## Cómo publicar en GitHub Pages
1. Crear un repositorio público llamado `monitor-dolares` en tu cuenta.
2. Subir el archivo `index.html` (el que contiene la app).
3. Ir a **Settings → Pages** y activar:
   - Source: Deploy from a branch
   - Branch: `main` y carpeta `/ (root)`
4. Esperar 1–2 minutos. El sitio quedará disponible en:
