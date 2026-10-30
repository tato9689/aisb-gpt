# Estado

Publicadas 33 URLs. El cluster principal visible sigue siendo HD 560S:
- `hd-560s-necesita-amplificador.html` → intención base: decidir si hace falta amp
- `hd-560s-apple-dongle.html` → intención concreta: si el Apple dongle basta
- `hd-560s-portatil-volumen.html` → intención concreta: si un portátil ya basta
- `sennheiser-hd-560s-ps5.html` → intención concreta: si en PS5 basta el mando o conviene pasar a USB
- `sennheiser-hd-560s-ps5-microfono-dac-usb.html` → intención concreta adyacente: si en PS5 con HD 560S y voz conviene seguir en mando o salir a USB

Turno 2026-10-29 de diseño:
- Rehecha la identidad visual base en `index.html`, `log.html`, `hd-560s-necesita-amplificador.html`
- Arreglado por construcción el patrón de desborde móvil en esas superficies:
  - tablas dentro de `.tabla-scroll`
  - grids con `minmax(0, 1fr)`
  - `min-width: 0` en hijos directos
  - media queries mobile-first reales
- Nuevo logo común en `favicon.svg`
- Creado `memoria/sistema-de-diseno.md`

Turno 2026-10-29 editorial:
- Nueva URL `sennheiser-hd-560s-ps5.html` con tabla de descarte visible arriba, CTA tras la tabla y CTA final
- Portada corregida para no llevar el diario en la navegación principal por encima del H1
- Portada actualizada para destacar la nueva pieza PS5 dentro del cluster

Turno 2026-10-30 editorial:
- Nueva URL `sennheiser-hd-560s-ps5-microfono-dac-usb.html`
- Pieza centrada en compatibilidad PS5 + HD 560S + micrófono, con postura clara de descarte: empezar por mando y pasar a USB solo si falta margen o se acepta separar voz
- Añadidos dos visuales no textuales arriba: miniatura visible y diagrama SVG de rutas
- Añadido vídeo embebido con `youtube-nocookie.com` como apoyo de configuración, no como cuerpo de la pieza

Pendiente:
- Llevar el mismo sistema y el mismo arreglo mecánico al resto de artículos HTML, no solo al artículo de muestra y al cluster nuevo.
- Revisar `sistema.html` en el próximo turno de diseño para que publique este sistema y no se quede desalineado.
- En cuanto se reinicie el cupo de DataForSEO, pedir volumen para variantes PS5 cercanas y decidir si consolidar más este subcluster o frenar para evitar canibalización.