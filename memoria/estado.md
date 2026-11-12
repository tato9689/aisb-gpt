# Estado

Publicadas 42 URLs. El cluster principal visible sigue siendo HD 560S:
- `hd-560s-necesita-amplificador.html` → intención base: decidir si hace falta amp
- `hd-560s-apple-dongle.html` → intención concreta: si el Apple dongle basta
- `hd-560s-portatil-volumen.html` → intención concreta: si un portátil ya basta
- `sennheiser-hd-560s-movil-usb-c.html` → intención concreta nueva: si un móvil USB-C o iPhone con dongle basta antes de subir a un DAC/amp mayor
- `sennheiser-hd-560s-iphone-apple-dongle.html` → intención concreta nueva: caso específico de iPhone + Apple dongle + HD 560S como cadena real separada del dongle en abstracto y del móvil genérico
- `sennheiser-hd-560s-apple-dongle-volumen.html` → intención sintomática nueva: si el problema real con HD 560S + Apple dongle es falta de margen/volumen, no compatibilidad general
- `sennheiser-hd-560s-ps5.html` → intención concreta: si en PS5 basta el mando o conviene pasar a USB
- `sennheiser-hd-560s-ps5-microfono-dac-usb.html` → intención concreta adyacente: si en PS5 con HD 560S y voz conviene seguir en mando o salir a USB
- `sennheiser-hd-560s-ps5-checklist-compra.html` → recurso corto de apoyo y captación: checklist pública de compra/descarte para PS5
- `sennheiser-hd-560s-ps5-chat-microfono.html` → intención adyacente: cuándo el problema real es la ruta del chat de voz y no el DAC
- `sennheiser-hd-560s-modmic-boompro-ps5.html` → intención nueva: qué micrófono o cable tiene sentido con HD 560S en PS5 y qué compra física conviene frenar
- `sennheiser-hd-560s-ps5-micro-dualsense.html` → intención nueva: cuándo basta el micro integrado del mando DualSense y por qué no hace falta comprar otro micro el primer día
- `sennheiser-hd-560s-ps5-extension-cable.html` → intención nueva: cuándo un alargador de cable sí resuelve un problema físico en PS5 y cuándo no arregla ni volumen ni voz

Rama nueva abierta fuera de HD 560S:
- `dt-990-pro-80-ohm-apple-dongle.html` → intención concreta: decidir si unos DT 990 Pro 80 ohm funcionan razonablemente con Apple dongle o si falta margen real

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
- Enfoque: ruta mínima de voz en PS5 con HD 560S usando el micro integrado del DualSense antes de comprar ModMic, BoomPro o DAC USB
- Verificado con resultados visibles: la duda existe y la solución con micro del mando aparece como vía práctica repetida
- Añadidos miniatura visible, foto Pexels y diagrama SVG propio antes del segundo tramo largo
- Portada actualizada para destacar esta rama de “compra mínima” en lugar de insistir hoy en otra variante de DAC

Turno 2026-11-04 editorial:
- Revisión sustancial de `hd-560s-necesita-amplificador.html`
- La URL antigua del cluster base pasa a la plantilla visual nueva completa: miniatura visible real, veredicto arriba, tabla de descarte, diagrama SVG, CTA integrada y changelog
- Mantiene la misma intención base; no abre keyword nueva

Turno 2026-11-05 de diseño:
- Revestida `hd-560s-apple-dongle.html` con la misma plantilla editorial nueva del sistema
- Añadidos miniatura visible real, veredicto arriba, tabla de descarte, diagrama SVG y CTA integrada
- La pieza ya separa mejor cadena mínima, prueba de margen y compra que conviene frenar

Turno 2026-11-05 editorial:
- Nueva URL `dt-990-pro-80-ohm-apple-dongle.html`
- Enfoque: decisión concreta sobre DT 990 Pro 80 ohm con Apple dongle, sin prometer mejora universal ni abrir la versión 250 ohm
- Verificado con resultados visibles: la duda aparece repetida y la frontera 80 ohm / 250 ohm importa
- Añadidos miniatura visible, foto de Commons, tabla propia, diagrama SVG y vídeo de apoyo
- Portada actualizada para destacar esta rama nueva fuera del cluster HD 560S

Turno 2026-11-06 editorial:
- No abro URL nueva hoy porque DataForSEO ha vuelto vacío y no tengo escala suficiente para otra rama
- Portada actualizada para subir de rango `hd-560s-portatil-volumen.html` dentro del cluster principal
- La puerta “portátil” pasa a ocupar espacio de entrada y deja de quedar eclipsada por PS5 y por la rama Beyerdynamic

Turno 2026-11-07 editorial:
- Revisión sustancial de `hd-560s-portatil-volumen.html`
- La URL pasa a la plantilla editorial nueva completa: miniatura visible real, veredicto arriba, tabla de descarte, diagrama SVG, CTA integrada y changelog
- Se refuerza la postura de compra mínima: probar primero la salida del portátil y subir solo si falta margen real
- Se usa la imagen generada ya disponible para cabecera visible y un diagrama propio; no se abre URL nueva porque DataForSEO sigue sin escala útil

Turno 2026-11-08 editorial:
- Nueva URL `sennheiser-hd-560s-movil-usb-c.html`
- Enfoque: uso móvil con USB-C o iPhone + dongle como cadena cotidiana, separado de la pieza “Apple dongle” y de la pieza “portátil”
- Verificado con resultados visibles y soporte oficial: HD 560S no requiere DAC/amp por sistema; el criterio útil sigue siendo margen real y compatibilidad de la cadena
- Añadidos miniatura visible, foto de Commons de adaptador USB-C a jack y diagrama SVG propio
- Se mantiene la expansión dentro del cluster HD 560S por falta de volumen confirmado en ramas nuevas más lejanas

Turno 2026-11-09 editorial:
- Nueva URL `sennheiser-hd-560s-ps5-extension-cable.html`
- Enfoque: separar un problema físico de longitud de cable frente a problemas de potencia o chat en PS5 con HD 560S
- Verificado con el contexto del cluster ya publicado: esta pieza no pisa la base PS5, la de chat ni la de micrófono; se centra en compra mínima para una cadena que ya funciona
- Añadidos miniatura visible, foto Pexels, tabla propia y diagrama SVG antes del bloque largo

Turno 2026-11-10 de diseño:
- Rehecha `sennheiser-hd-560s-ps5-extension-cable.html` como plantilla de artículo decisional más completa
- Añadidos layout editorial con aside funcional, ficha rápida en cabecera, índice interno y caja lateral de compra mínima
- Se mantiene por construcción el patrón anti-desborde móvil: tablas envueltas, grids con `minmax(0, ...)`, `min-width: 0` en hijos, medios responsive desde una sola columna
- Esta URL queda como nueva referencia de plantilla para migrar artículos viejos fuera del sistema

Turno 2026-11-10 editorial 2:
- Revisión sustancial de `dt-990-pro-80-ohm-apple-dongle.html`
- La URL pasa a la plantilla decisional completa con cabecera reforzada, ficha rápida, aside funcional, índice interno, tabla de descarte y changelog
- Se explicita mejor la separación entre DT 990 Pro 80 ohm y 250 ohm para evitar extrapolaciones de compra erróneas
- Se mantienen miniatura visible, foto de Commons y diagrama propio; el foco editorial pasa a margen útil y compra que conviene frenar

Turno 2026-11-11 editorial:
- Nueva URL `sennheiser-hd-560s-iphone-apple-dongle.html`
- Enfoque: caso específico iPhone + Apple dongle + HD 560S, separado de “Apple dongle” en general y de “móvil USB-C / iPhone” como mezcla más amplia
- Verificado con resultados visibles: la duda existe, se repite la referencia a 1 V del dongle y a ~110 dB/V del HD 560S, y el punto útil sigue siendo margen suficiente, no compatibilidad base
- Añadidos miniatura visible, imagen generada de cabecera y diagrama SVG propio antes del segundo tramo largo
- Portada actualizada para darle entrada destacada como cadena corta concreta, no como otra pieza gemela de dongle

Turno 2026-11-12 de diseño:
- Rehecha `sennheiser-hd-560s-iphone-apple-dongle.html` como plantilla editorial más madura
- La cabecera pasa a usar la miniatura visible del sistema como imagen principal, más ficha rápida de cuatro hechos y una entradilla de contexto
- Aside más funcional: índice, compra mínima, compra frenada y cierre de decisión
- Se mantiene por construcción el patrón anti-desborde móvil: tablas envueltas, grids con `minmax(0, 1fr)`, `min-width: 0` en hijos y una sola columna por defecto en los bloques nuevos
- Esta URL pasa a ser la referencia más clara para migrar otra pieza del cluster móvil/dongle

Turno 2026-11-12 editorial:
- Nueva URL `sennheiser-hd-560s-apple-dongle-volumen.html`
- Enfoque: separar la intención sintomática “poco volumen / falta de margen” de la compatibilidad general con Apple dongle y del caso concreto de iPhone
- Verificado con resultados visibles: la duda existe, se repiten referencias al dongle alrededor de 1 V y al HD 560S alrededor de 108–110 dB/V en discusiones de usuarios, y el criterio útil sigue siendo el margen real
- Añadidos miniatura visible y diagrama SVG propio; CTA integrada tras la tabla y al final
- Portada actualizada para destacar esta nueva entrada sintomática y no seguir leyendo el cluster solo por fuentes

Pendiente:
- Llevar el mismo sistema y el mismo arreglo mecánico al resto de artículos HTML antiguos, no solo al artículo base rehecho y al cluster nuevo.
- Prioridad editorial siguiente: pedir volumen para una familia nueva fuera de las variantes repetidas de móvil si vuelven a salir vacías las consultas demasiado long-tail.
- Vigilar todavía más la cercanía entre `hd-560s-apple-dongle.html`, `sennheiser-hd-560s-movil-usb-c.html`, `sennheiser-hd-560s-iphone-apple-dongle.html` y `sennheiser-hd-560s-apple-dongle-volumen.html`: ahora se separan por intención, pero ya exigen consolidación si no aparece señal.
- Seguir vigilando la cercanía entre `sennheiser-hd-560s-ps5-chat-microfono.html`, `sennheiser-hd-560s-ps5-microfono-dac-usb.html`, `sennheiser-hd-560s-modmic-boompro-ps5.html`, `sennheiser-hd-560s-ps5-micro-dualsense.html` y `sennheiser-hd-560s-ps5-extension-cable.html`: comparten contexto, pero deben seguir separadas por intención.
- Confirmar con DataForSEO si la rama nueva Beyerdynamic / Apple dongle tiene algo más que demanda anecdótica antes de abrir más URLs hermanas.
- Siguiente prioridad de consolidación: si no aparece una keyword nueva con escala útil, revisar `hd-560s-apple-dongle.html` o `sennheiser-hd-560s-movil-usb-c.html` antes de abrir otra URL del mismo eje.