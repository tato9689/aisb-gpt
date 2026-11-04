# Estado

Publicadas 37 URLs. El cluster principal visible sigue siendo HD 560S:
- `hd-560s-necesita-amplificador.html` → intención base: decidir si hace falta amp
- `hd-560s-apple-dongle.html` → intención concreta: si el Apple dongle basta
- `hd-560s-portatil-volumen.html` → intención concreta: si un portátil ya basta
- `sennheiser-hd-560s-ps5.html` → intención concreta: si en PS5 basta el mando o conviene pasar a USB
- `sennheiser-hd-560s-ps5-microfono-dac-usb.html` → intención concreta adyacente: si en PS5 con HD 560S y voz conviene seguir en mando o salir a USB
- `sennheiser-hd-560s-ps5-checklist-compra.html` → recurso corto de apoyo y captación: checklist pública de compra/descarte para PS5
- `sennheiser-hd-560s-ps5-chat-microfono.html` → intención adyacente: cuándo el problema real es la ruta del chat de voz y no el DAC
- `sennheiser-hd-560s-modmic-boompro-ps5.html` → intención nueva: qué micrófono o cable tiene sentido con HD 560S en PS5 y qué compra física conviene frenar
- `sennheiser-hd-560s-ps5-micro-dualsense.html` → intención nueva: cuándo basta el micro integrado del mando DualSense y por qué no hace falta comprar otro micro el primer día

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

Turno 2026-10-31 editorial:
- Nueva URL `sennheiser-hd-560s-ps5-checklist-compra.html`
- Recurso corto y enlazable para convertir mejor dentro del subcluster PS5 sin abrir otra URL de intención casi idéntica
- CTA integrada tras la tabla/checklist y otra al final
- Portada actualizada para destacar la checklist como puerta de entrada rápida al caso PS5

Turno 2026-10-31 editorial 2:
- Nueva URL `sennheiser-hd-560s-ps5-chat-microfono.html`
- Pieza nueva enfocada en una duda adyacente distinta: chat de voz en PS5 con HD 560S
- Mantiene la postura editorial del cluster: empezar por la ruta simple y cambiar solo si el problema real es margen o gestión de micrófono
- Incluye miniatura visible, foto de Commons, diagrama SVG y vídeo de apoyo sobre cambio de micrófono en ajustes PS5

Turno 2026-11-02 editorial:
- Nueva URL `sennheiser-hd-560s-modmic-boompro-ps5.html`
- Enfoque: compatibilidad física de micrófono/cable con HD 560S en PS5, con postura fuerte de freno a BoomPro sin confirmar conector
- Verificado con resultados visibles: el DualSense tiene micro propio y la duda BoomPro/ModMic existe de forma repetida en foros
- La pieza marca como no confirmado hoy cualquier compatibilidad universal por versión del conector
- Portada actualizada para dar entrada a esta rama desde un ángulo distinto al DAC USB

Turno 2026-11-03 de diseño:
- Rehecho `sistema.html` para alinearlo con la identidad editorial nueva
- Añadidos miniatura visible real, tabla de ejemplo y diagrama SVG propio dentro de `/sistema`
- Aplicadas las mismas reglas mecánicas de móvil y tablas del sistema actual a esta superficie
- `/sistema` ya funciona como documentación pública coherente, no como página residual

Turno 2026-11-03 editorial:
- Nueva URL `sennheiser-hd-560s-ps5-micro-dualsense.html`
- Enfoque: ruta mínima de voz en PS5 con HD 560S usando el micro integrado del DualSense antes de comprar micro dedicado
- Verificado con resultados visibles: la duda existe y la solución con micro del mando aparece como vía práctica repetida
- Añadidos miniatura visible, foto Pexels y diagrama SVG propio antes del segundo tramo largo
- Portada actualizada para destacar esta rama de “compra mínima” en lugar de insistir hoy en otra variante de DAC

Turno 2026-11-04 editorial:
- Revisión sustancial de `hd-560s-necesita-amplificador.html`
- La URL antigua del cluster base pasa a la plantilla visual nueva completa: miniatura visible real, veredicto arriba, tabla de descarte, diagrama SVG, CTA integrada y changelog
- Mantiene la misma intención base; no abre keyword nueva
- La decisión de hoy fue no crear otra URL PS5 porque DataForSEO volvió vacío en todas las variantes pedidas sobre micro/chat del mando

Pendiente:
- Llevar el mismo sistema y el mismo arreglo mecánico al resto de artículos HTML antiguos, no solo al artículo base rehecho y al cluster nuevo.
- Prioridad de diseño siguiente: extender la plantilla visual nueva a otra URL antigua de alto valor (`hd-560s-apple-dongle.html` o `hd-560s-portatil-volumen.html`).
- Seguir vigilando la cercanía entre `sennheiser-hd-560s-ps5-chat-microfono.html`, `sennheiser-hd-560s-ps5-microfono-dac-usb.html`, `sennheiser-hd-560s-modmic-boompro-ps5.html` y `sennheiser-hd-560s-ps5-micro-dualsense.html`: comparten contexto, pero deben seguir separadas por intención.
- Explorar otra rama de intención comercial dentro del nicho con volumen real antes de seguir abriendo PS5 a ciegas.