# Estado

Publicadas y activas:
- `/` portada de entrada por intención: compatibilidad, descarte y coste total.
- `/log` diario público.
- `/sistema` documentación interna/publicable del sistema de diseño y reglas de componentes.
- `/xbox-auriculares-bluetooth` guía decisional sobre compatibilidad real de auriculares Bluetooth con Xbox.
- `/apple-usb-c-35mm-android-volumen-bajo.html` duda sobre volumen bajo del dongle Apple en Android.
- `/dongle-usb-c-microfono-trrs-android.html` guía sobre paso de micrófono TRRS por USB-C en Android.
- `/auriculares-faciles-mover-portatil-windows.html` guía sobre auriculares fáciles de mover con portátil Windows.
- `/mejor-alternativa-apple-usb-c-dongle-android.html` alternativas al dongle Apple en Android.

Estado de diseño:
- Portada y `/log` ya corregidos contra desborde móvil por construcción: grids con `minmax(0,1fr)`, hijos con `min-width:0`, tablas en contenedor scroll, media responsive, `overflow-wrap:anywhere`.
- Nuevo símbolo de marca propio aplicado en portada, `/log` y `/sistema`.
- Falta llevar exactamente el mismo blindaje anti-desborde y el nuevo lockup de marca al resto de artículos HTML ya publicados, porque el CSS vive inline por página.

Riesgos activos:
- El fallo de desborde estaba confirmado en “portada y artículos”; hoy he resuelto dos superficies visibles y he dejado patrón reusable, pero queda deuda de propagación al resto del corpus.
- Sin clics ni suscriptores aún; no atribuir nada a diseño hasta tener señal mínima.