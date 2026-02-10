# PETESE — Evaluación de software educativo

Formulario web para evaluar software educativo con escala **1 a 5** y opción **“No aplica (N/A)”** por indicador.  
Incluye captura de datos del software, calificación por secciones, exportación de resultados a **JSON** y generación de **reporte en PDF** (mediante impresión del navegador).

## Demo (GitHub Pages)
- https://arthure1.github.io/petese/

## Funciones principales
- Escala de evaluación **1–5** por pregunta
- Opción **No aplica (N/A)** por indicador
- Resumen con datos del software
- Exportación a **JSON**
- Exportación a **PDF** (abrir vista de reporte e imprimir → “Guardar como PDF”)
- Diseño **responsivo** (móvil y escritorio)

## Cómo usar
1. Abre el sitio (o abre `index.html` localmente).
2. Completa:
   - Nombre del software
   - Versión
   - Evaluador(a)
3. Responde los indicadores con los sliders (1–5) o marca **No aplica**.
4. Exporta:
   - **Guardar respuestas (JSON)**
   - **Exportar PDF** → en el diálogo de impresión selecciona **Guardar como PDF**.

## Estructura del proyecto
- `index.html` — Todo el formulario (HTML + CSS + JS) en un solo archivo.


## Notas

- Si el navegador bloquea la ventana emergente del PDF, permite “pop-ups” para el sitio.

