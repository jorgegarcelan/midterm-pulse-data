# Pronóstico final · Midterms de EE. UU. 2026

Pronóstico de Jorge Garcelán para las elecciones del 3 de noviembre de 2026, **congelado el 1 de noviembre de 2026 a las 18:22:22 UTC** (19:22 en España) como referencia de la noche electoral. Publicado aquí antes de la votación para que cualquiera pueda comprobar después qué se pronosticó y cuándo. Web: https://www.us-elections.dev

Pronósticos y modelos independientes: sin vínculo con partidos, campañas ni medios.

## Titulares

| | Cámara de Representantes | Senado |
|---|---|---|
| **MP-26 v0.5** (resultados previos, incumbencia, entorno nacional y encuestas; 1 nov.) | 245 escaños demócratas (80 %: 228–266) · mayoría demócrata 99 % | 52 escaños demócratas (80 %: 49–56) · mayoría demócrata 76 % |
| **Census-26** (solo perfil demográfico; 19 oct.) | 239 escaños demócratas (200–283) · mayoría demócrata 75 % | 50 escaños demócratas (45–55) · mayoría demócrata 47 % |

Mayorías: 218 en la Cámara; 51 en el Senado (a los republicanos les bastan 50 con el voto de calidad del vicepresidente).

## Ficheros

- `races.csv`: las 470 carreras (435 de la Cámara, 35 del Senado): líder y margen de MP-26 (D − R, puntos), probabilidad de victoria, probabilidad demócrata de MP-26 y de Census-26, valoración de los analistas y número de encuestas.
- `mp26-model.json`: la salida completa de MP-26 tal como la publicaba la web (`/api/model`): distribución de escaños, supuestos y cada carrera.
- `race-models.json`: probabilidad demócrata de cada carrera según MP-26 y Census-26 (`/api/race-models`).
- `models-summary.json`: el resumen de los dos modelos (`/api/models-summary`).
- `frozen-baseline.json`: la referencia congelada en la mesa de la noche electoral (los márgenes de las 470 carreras con los que se leen las proyecciones), con la hora del congelado.

## Sumas de comprobación (SHA-256)

```
bf58a36a063304eafa505c74513d28e2514f3c861c21de74af167f972fedd43e  frozen-baseline.json
fd873cdd6c45b5a7ac6de7c2f6d9566e273dba89e8e70ea101f5068d97dc52e8  models-summary.json
7ee442123c9d50237b085cf38b93343b5f9281aaf88de1814a80d3e421b5fa3e  mp26-model.json
600aabd2fd5d026b0505ec7347d0e98876190ec624aa51c4222db486b404de34  race-models.json
5dd9a143a035bba06635fddee014c2f5dedd6565d4072e6010f9e5143be7689c  races.csv
```

---

**English.** Jorge Garcelán's final forecast for the 3 November 2026 US midterms, frozen on 1 November 2026 at 18:22:22 UTC as the election-night baseline and published before the vote. MP-26 v0.5: House 245 Democratic seats (80% range 228–266), 99% chance of a Democratic majority; Senate 52 (49–56), 76%. Census-26 (demographics only, 19 Oct): House 239 (200–283), 75%; Senate 50 (45–55), 47%. Files and checksums above. Independent: not tied to any party, campaign or media outlet.
