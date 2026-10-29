# Sistema de diseño — Audio personal sin ruido

## Concepto
Mesa editorial de decisión para compras de audio personal.  
Tres adjetivos: sobrio, preciso, humano.  
No es un escaparate audiófilo lujoso, no es una plantilla SaaS, no es un ranking gritón.

## Tokens
- Fondo claro `#f3efe7`, superficies `#f8f4ed`, `#efe8dc`, `#e4dbc9`
- Tinta `#171411`, secundaria `#4e463d`, tenue `#71675c`
- Línea `#cbc0b1`, línea fuerte `#978977`
- Acento único `#9a4e21`, texto sobre acento `#fff7f0`
- Estados: ok `#2f6a51`, aviso `#8a6517`, error `#8a3a33`
- Oscuro: mismos roles, no mismos hex; contraste AA
- Tipografía: Manrope para interfaz y titulares; Source Serif 4 para lectura
- Escala con `clamp()`, titulares tensos y metadatos en mayúsculas espaciadas
- Números tabulares en tablas y fechas
- Radios: 10 / 16 / 24 px
- Movimiento: corto, seco, sin rebote

## Rejilla
- Contenedor máximo 1180 px
- Lectura a 72 caracteres aprox.
- Una columna por defecto
- Varias columnas solo desde 600 px
- Toda columna usa `minmax(0, 1fr)`
- Todo hijo directo de grid o flex lleva `min-width: 0`

## Componentes
- Cabecera: marca a la izquierda, navegación en versales pequeñas
- Tarjeta de portada: foto 640×336, metadato arriba, título fuerte, texto corto
- Artículo: veredicto breve arriba, tabla o bloque útil antes del tramo largo, CTA integrada, related al final
- Tablas: siempre dentro de `.tabla-scroll`, nunca sueltas
- Formularios: fondo de superficie 2, inputs píldora, foco visible en acento
- Etiquetas: pequeñas, secundarias, nunca promocionales
- Enlaces: subrayado fino, hover en acento, visitado más tenue

## Reglas de uso
- Un solo acento y con función: orientación, foco, llamadas útiles
- Nada de sombras grandes difusas ni gradientes vistosos
- El titular manda más que el bloque decorativo
- Si algo cabe mejor en tabla, va en tabla
- Si una duda es de compatibilidad, el componente debe mostrar descarte antes que entusiasmo
- Toda imagen visible lleva `width`, `height` y tratamiento común
- Todo SVG informativo usa `viewBox`, texto legible y contraste suficiente
- Nunca usar color como único código

## Lo que no se hace
- Glassmorphism
- Hero centrado con botón
- Tres tarjetas idénticas como plantilla de producto
- Rankings “mejor X” sin contexto
- Diagramas vacíos para aparentar profundidad
- Fotos heroicas de estudio o altar audiófilo

## Dirección de arte
Documental creíble. Luz corriente de casa u oficina, ventana o lámpara simple; nada de rim light ni dramatización premium. Encuadre de persona normal: escritorio usado, portátil, móvil, dongle, auriculares o IEMs en contexto real, con ligera imperfección y desgaste visible. Paleta apagada, cálida y mate, cercana a papel, metal cepillado, plástico negro y madera clara. Evitar brillos especulares, fondos bokeh, superficies pulidas y simetría publicitaria. Las miniaturas deben sugerir cadena real y uso doméstico: cable conectado, fuente visible, objetos de trabajo alrededor. Nunca estudio profesional, altavoces de sala, iconografía médica ni escenas “gaming RGB”. Tratamiento común en CSS: recorte 640×336, contraste moderado, saturación algo contenida, borde fino del color de línea.