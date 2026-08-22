# Bentobox Guitar

Transcripción de stems de guitarra y bajo a tablatura, con mástil animado, digitación humana, capo, acordes, técnicas, secciones, modo ensayo y exportación a Guitar Pro / MusicXML / MIDI / texto. Corre 100 % en el navegador.

Motores: Basic Pitch (Spotify, Apache 2.0) para notas; detectores propios para power chords, riffs/solos y acordes por croma; alphaTab (MPL 2.0) para exportar .gp. También importa MIDI de otros modelos (MuScriptor, YourMT3+…).

## Archivos
- `index.html` — la app completa (logo embebido).
- `favicon.ico`, `apple-touch-icon.png`, `og.png` — iconos e imagen para compartir.
- `catalogo/index.json` — lista de temas: `[{ "file": "...", "title": "...", "artist": "..." }]`.
- `catalogo/*.bbx.json` — cada tema, exportado desde la app con "Guardar".

## Publicar un tema en el catálogo
1. En la app: sube el stem, corrige la tab, pon título y artista, "Guardar".
2. Renombra el `.bbx` a `nombre.bbx.json` y súbelo a `catalogo/`.
3. Agrega una línea en `catalogo/index.json`.
