# Agua en Jalisco

Tablero informativo sobre el agua concesionada en Jalisco: de dónde sale, en qué se usa, la disponibilidad de los acuíferos, la sequía y el agua en las viviendas.

- `index.html`: versión principal, pensada para celular (también funciona en computadora). No necesita internet ni servicios externos: los datos y el mapa van dentro del archivo.
- `tablero-escritorio.html`: versión de escritorio generada con QGIS (plugin QGIS Dashboard).

## Fuentes
- Registro Público de Derechos de Agua (REPDA), CONAGUA, corte 2023, y títulos de los distritos de riego.
- Acuerdo de disponibilidad media anual de aguas subterráneas, DOF 9 de noviembre de 2023 (CONAGUA). Valores de la compilación de Platas-López, A. y Cruz-Mejía, O. (2026), Mendeley Data, doi:10.17632/r92tjwgjp9.1.
- Monitor de Sequía de México (CONAGUA–SMN), municipios, 2003 al 15 de octubre de 2026.
- Censo de Población y Vivienda 2020, INEGI.

## Notas
- El volumen concesionado es el máximo que autoriza cada título; no es la extracción medida.
- El uso hidroeléctrico no se suma al consumo: el agua turbinada regresa al río.
- Las concesiones urbanas se ubican en la toma o el pozo, no donde vive la población servida.

El mapa usa [Leaflet](https://leafletjs.com) 1.9.4 (licencia BSD-2-Clause), incluido en el archivo.

## Publicar en GitHub Pages
1. Crea un repositorio público (por ejemplo `agua-jalisco`).
2. Sube `index.html`, `tablero-escritorio.html` y este `README.md`.
3. En *Settings → Pages*, elige *Deploy from a branch*, rama `main`, carpeta `/ (root)` y guarda.
4. En unos minutos el sitio queda en `https://TU-USUARIO.github.io/agua-jalisco/`.
