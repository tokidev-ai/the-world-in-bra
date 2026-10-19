# The Bra Index · Mapa mundial de PIB en Fantasy Bras

Web interactiva en español. Compara el PIB nominal anual de los países y territorios del mundo con el valor estimado del Fantasy Bra de Kylie Jenner en Victoria's Secret (US$ 50.000.000, edición 2026).

## Iniciar

Abre `index.html` directamente en tu navegador. No requiere instalación ni compilación. Para publicarlo en GitHub Pages, Netlify o Vercel, basta subir `index.html` como página principal.

## Funcionalidades

- Mapa mundial con países coloreados según su equivalencia en Fantasy Bras.
- Búsqueda por nombre, filtrado por continente, zoom, selección y detalles por país.
- Tabla completa ordenada por PIB de economías con datos y comparación entre países.
- Actualización desde la API pública del Banco Mundial (indicador `NY.GDP.MKTP.CD`, serie 2015–2025; se usa el año más reciente disponible de cada economía).
- Respaldo local sin conexión con geometría de 177 países y estimaciones históricas de Natural Earth, identificadas claramente como cifras demo. Bolivia tiene un dato confirmado de 2025 de US$ 64.768.947.525,30. El directorio de búsqueda contiene 252 países y territorios y puntos para países pequeños; los faltantes permanecen sin PIB hasta disponer de fuente.

## Cálculo

`número de bras = PIB nominal anual en US$ / 50.000.000`

El PIB es producción anual, no patrimonio ni ahorros de un país. En datos de respaldo se mezclan años y no deben usarse para rankings académicos.

## Fuentes

- Banco Mundial: https://data.worldbank.org/indicator/NY.GDP.MKTP.CD
- Dato PIB Bolivia 2025: https://data.worldbank.org/country/bolivia
- Vogue México: https://www.vogue.mx/articulo/kylie-jenner-victorias-secret-fashion-show-2026-fantasy-bra
- Geometría: Natural Earth (datos de muestra pyogrio/GeoPandas).
