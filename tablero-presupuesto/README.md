# Tablero Presupuestario UMCE 2026

Tablero web inicial para visualizar la información presupuestaria de la hoja `Saldo_Presupuestario`.

## Archivos

- `index.html`: estructura del tablero.
- `styles.css`: estilos visuales.
- `app.js`: filtros, tarjetas, gráficos y tabla.
- `data/saldo_presupuestario.json`: datos usados por el tablero.

## Publicación en GitHub Pages

1. Entrar al repositorio en GitHub.
2. Ir a `Settings`.
3. Ir a `Pages`.
4. En `Branch`, elegir `main` y carpeta `/root`.
5. Guardar.

La URL final tendrá una forma similar a:

`https://raulrojastaborga-conejo.github.io/presupuesto-UMCE2026/tablero-presupuesto/`

## Nota

La primera versión usa un archivo JSON estático. Más adelante se puede conectar a Google Sheets mediante Apps Script publicado como endpoint JSON para actualizar automáticamente el tablero.
