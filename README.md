# HYROX Santiago

App de seguimiento rumbo a **HYROX Cancún 2027 (Doubles, sub 65 min)**: clase del día, hábitos, rachas, checkpoints InBody y progreso.

- Un solo `index.html`, sin backend y funciona sin internet.
- Los datos se guardan solo en el teléfono (`localStorage`); se respaldan exportando JSON desde Ajustes.
- El InBody se puede capturar a mano o subiendo el PDF/foto: se lee en el propio teléfono con [PDF.js](https://mozilla.github.io/pdf.js/) y [Tesseract.js](https://tesseract.projectnaptha.com/) (en `vendor/`).

## Usarla en el iPhone

Abre la página de GitHub Pages en Safari → Compartir → **Agregar a pantalla de inicio**.

## Probar otra fecha

Agrega `?fecha=AAAA-MM-DD` al final del link (por ejemplo `?fecha=2026-11-05`).

## Editar el plan

Fechas, fases, semanas tipo, checkpoints y reglas están en el objeto `CONFIG` al inicio del script de `index.html`.
