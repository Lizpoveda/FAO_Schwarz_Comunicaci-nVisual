# FAO Schwarz — El Zen de la Construcción

Portada / landing editorial para la propuesta gráfica **“El Zen de la Construcción”**, desarrollada a partir del documento de planeación de Elizabeth Cuervo Poveda (CUN, Bogotá D.C., 2026).

La página no es una tienda: presenta el concepto, el sistema visual, la composición y el documento completo de la propuesta.

## Vista previa

```text
http://localhost:8080/
```

El servidor local ya está corriendo. Para levantarlo de nuevo:

```powershell
powershell -NoProfile -ExecutionPolicy Bypass -File .\serve.ps1
```

También puede abrirse directamente `index.html` en el navegador.

## Contenido

- **Inicio:** dragón low-poly en postura de loto, malla dorada interactiva al pasar el cursor / enfocar / tocar.
- **La propuesta:** objetivo de comunicación, público y ficha de la pieza.
- **Concepto:** el dragón como metáfora de concentración y calma al armar un rompecabezas 3D.
- **Sistema visual:** paleta esmeralda / dorado / arena, tipografía serif + sans, retícula de 12 columnas y wireframes.
- **Composición:** recorrido visual, contraste, equilibrio, centro de impacto y leyes de la Gestalt.
- **Documento:** descarga y apertura del PDF original, datos de la autora y referencias.

## Archivos

```text
index.html
styles.css
script.js
serve.ps1
assets/
  dragon-cutout.png   → dragón transparente del hero y del concepto
  dragon-mask.png     → máscara de la malla dorada
  dragon-crop.jpg     → imagen para Open Graph
  dragon-source.jpg   → fuente original (no se carga en la página)
  Planeacion_Propuesta_Grafica_FAO_Schwarz_APA.pdf
```

## Notas

- Tipografías: **Bodoni Moda** (serif, logotipo) y **Archivo / Manrope** (sans, interfaz), vía Google Fonts.
- Paleta: verde esmeralda, dorado y arena; el rojo tradicional se evita.
- El PDF se sirve localmente y se descarga desde el encabezado, el capítulo “Documento” y el pie de página.
- La página es estática y puede publicarse en Netlify, Vercel o GitHub Pages subiendo la carpeta completa.

## Créditos

Propuesta gráfica y documento: **Elizabeth Cuervo Poveda**  
Corporación Unificada Nacional de Educación Superior (CUN) — Bogotá D.C., Colombia, 2026.
