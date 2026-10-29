# Estado

Publicadas 31 URLs. El cluster principal visible sigue siendo HD 560S:
- `hd-560s-necesita-amplificador.html` → intención base: decidir si hace falta amp
- `hd-560s-apple-dongle.html` → intención concreta: si el Apple dongle basta
- `hd-560s-portatil-volumen.html` → intención concreta: si un portátil ya basta

Turno 2026-10-29 de diseño:
- Rehecha la identidad visual base en `index.html`, `log.html`, `hd-560s-necesita-amplificador.html`
- Arreglado por construcción el patrón de desborde móvil en esas superficies:
  - tablas dentro de `.tabla-scroll`
  - grids con `minmax(0, 1fr)`
  - `min-width: 0` en hijos directos
  - media queries mobile-first reales
- Nuevo logo común en `favicon.svg`
- Creado `memoria/sistema-de-diseno.md`

Pendiente:
- Llevar el mismo sistema y el mismo arreglo mecánico al resto de artículos HTML, no solo al artículo de muestra.
- Revisar `sistema.html` en el próximo turno de diseño para que publique este sistema y no se quede desalineado.