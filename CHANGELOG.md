# Changelog — Recetario Ernesto Otero

## [1.5.0] — 2 abril 2026
### Agregado
- **Omelette au Cottage, Salmon, Pimiento y Espinacas** — sexta receta
  - Receta directa (sin audio/video), ingredientes dictados
  - 5 claras + 1 huevo entero + salmon Labeyrie + cottage + pimiento + espinaca + aguacate + eneldo
  - 490 kcal, 50.8g proteina por receta completa (~495g)
  - HTML individual, PDF, integrada en recetario principal y calculadora

## [1.4.0] — 1 abril 2026
### Agregado
- **Omelette Ligera con Jamon** — quinta receta
  - Receta directa (sin audio/video), ingredientes dictados
  - 2 claras + 1 yema + 2 sprays AOVE + 1 rodaja jamon Fleury Michon -25% sal sin nitrite
  - 125 kcal, 14.5g proteina por receta completa (~109g)
  - HTML individual, PDF, integrada en recetario principal y calculadora

## [1.3.0] — 31 marzo 2026
### Agregado
- **Calculadora Nutricional** interactiva en el recetario principal
  - Desplegable por receta con filtros y buscador
  - Input por gramos o por porciones, calculo automatico de macros
  - Desglose por ingrediente en tabla
  - Total del dia sumando todas las recetas abiertas
- **Informacion nutricional** (calorias, proteina, carbs, grasa, fibra) en las 4 recetas
  - Tabla por ingrediente + totales por porcion y receta completa

## [1.2.0] — 31 marzo 2026
### Agregado
- **Pesto de Albahaca Light con Feta** — tercera receta
  - Audio transcrito con mlx-whisper (Pesto.m4a, 29s)
  - Version light: feta + avellanas en lugar de parmesano + piñones
  - 167 kcal toda la receta, 28 kcal por cucharadita
- **Frittata Light** — cuarta receta
  - Audio transcrito con mlx-whisper (Omelette.m4a, 28s)
  - 3 claras + 3 huevos enteros, cottage, feta, cherry, pesto casero
  - 478 kcal, 41.5g proteina por receta completa
- HTMLs individuales para las 4 recetas (`recetario-pesto.html`, `recetario-frittata.html`, `recetario-spanakopita.html`, `recetario-lentejas.html`)
- PDFs actualizados para las 4 recetas
- Carpeta `Audios recetas/` para audios de recetas sin video

## [1.1.0] — 2026-03-30
### Agregado
- **Lentejas con Carne y Vegetales** — segunda receta
  - 7 videos transcritos (15 min, IMG_2034-2041)
  - 6 screenshots del video en los pasos de la receta (ajo, carne, espuma, sofrito, lentejas)
  - Foto de Ernesto sonriendo como hero (IMG_2040)
- **Pagina principal (index)** con menu y cards para cada receta
- **Archivo todo-en-uno** (`recetario-ernesto-otero.html`) con navegacion por tabs — listo para compartir por WhatsApp
- **Workflow PDF** documentando el ejercicio #2
- Repo en GitHub con GitHub Pages para compartir por link

### Cambiado
- Las fotos de los pasos ahora se recortan para mostrar la coccion (corte inferior)

## [1.0.1] — 2026-03-28
### Corregido
- Color rojo ajustado a rojo oscuro (#8B0000) — no era naranja, era #c0392b
- "Brogui" corregido a "brebis" (queso de cabra)
- "Paprica" corregido a "paprika" con K
- Foto de stock reemplazada por foto real de la spanakopita (Screenshot 2026-03-28)
- Workflow PDF rediseñado como one-pager en dos columnas

## [1.0.0] — 2026-03-28
### Agregado
- **Spanakopita** — primera receta del recetario
  - Audio transcrito con mlx-whisper (Receta Ernesto Spanakopita.m4a, 4 min)
  - Receta redactada en estilo propio de Ernesto (vos, conversacional, con tips)
  - HTML para email con diseno moderno en rojo oscuro
  - Salsa para dipear (fromage blanc/brebis, feta, perejil, paprika, limon)
- **Receta PDF** para imprimir/compartir
- **Transcript** original en Markdown
- **Workflow PDF** documentando el proceso (video → transcript → HTML)
