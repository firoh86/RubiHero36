# RubiHero36: Teclado Mecánico custom ortholineal Vstaggered

![Imagen principal del teclado](ruta/a/tu/imagen.jpg)

## Descripción

Breve descripción del teclado: ¿es un diseño propio? ¿qué lo hace especial? ¿para qué está pensado (gaming, escritura, compacto, etc.)?
Hero36 es un teclado mecánico custom con soporte para switches MX hotswap, compacto y útil, enfocado al uso de ZMK (combos, etc).
Es un diseño propio, basado en el teclado corne, monoblock, es decir, no split.
Es útil y funcional, para escribir, programar, completamente customizable.
el shape está basado en el mikefive, con la particularidad de las alas rotadas 15º para mayor comodidad de uso.

## Especificaciones Técnicas

- **Tipo de teclado:** 40% ortholineal, con desplazamiento vertical y ergonómico.
- **Switches soportados:** Mx hotswap 3,5 pines.
- **Materiales:** PCB, carcasa de resina impresa, compatible para cnc, PC o aluminio.
- **Conectividad:** USB-C, Bluetooth, inalámbrico.
- **Retroiluminación:** no tiene.
- **Firmware:** ZMK

## Galería

Previews del teclado:

![Vista superior](ruta/a/imagen2.jpg)
![Vista lateral](ruta/a/imagen3.jpg)

## Layout
A continuación muestras del layout de éste teclado:

[![Layout](ruta/a/layout.png)](https://imgur.com/a/yv3qFPl)

```json
[
  [{ "a": 7 }, "", "", "", "", "", "", { "x": 3 }, "", "", "", "", "", ""],
  ["", "", "", "", "", "", { "x": 3 }, "", "", "", "", "", ""],
  ["", "", "", "", "", "", { "x": 3 }, "", "", "", "", "", ""],
  [{ "x": 4 }, "", "", "", { "x": 1 }, "", "", ""]
]
```

## Instrucciones de Armado (Opcional)

1. Componentes necesarios para montar éste teclado:
- PCB Hero36 como base.
- Nice!Nano V2 como shield.
- 36x Choc V1-V2 switches.
- 36x Keycaps para Choc.
- Cable USB-C para conectarlo al PC.
- Impresora 3d para imprimir el case o un servicio cnc para ordenar la case.
- tornillos (xM2-3).


1. Pasos para armar el teclado.
2. Consejos para soldar o montar switches/keycaps.

## Instalación y Configuración

- Cómo cargar firmware.
- Cómo configurar las teclas (QMK, VIA, etc.).
- Requisitos de software/hardware.

## Créditos

Los teclados que referencian éste, son: mikefive y cornekeyboard, ZMK como práctica de software.

## Licencia

## Éste proyecto está licenciado, lee la [licencia aquí](LICENSE.md).
