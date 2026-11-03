# Quami: guía de logo

**Idea:** el nombre de siempre, "quami", con una línea amarilla que se levanta en dos volcanes debajo de la "m".
Picos a 45°, el izquierdo más alto que el derecho.

## Archivos

| Archivo | Uso |
| --- | --- |
| `logo/quami-logo.svg` | Principal: texto tinta + línea queso, sobre fondos claros |
| `logo/quami-logo-reversed.svg` | Texto blanco + línea queso, sobre fondos oscuros |
| `logo/quami-logo-black.svg` / `-white.svg` | Un solo color (sellos, grabado, fax, documentos en B/N) |
| `logo/quami-logo-stacked.svg` | Apilado: ícono arriba, nombre abajo (espacios cuadrados) |
| `logo/quami-icon.svg` | Ícono: volcanes queso sobre cuadro tinta (redes, GitHub, npm, avatar) |
| `logo/quami-icon-small.svg` | Ícono con trazo más grueso, solo para 16–32 px (favicon) |
| `logo/quami-symbol.svg` | Volcanes solos en tinta, sin cuadro |
| `png/` | PNG 1200 px de las versiones principales; `quami-og-image.png` (1200×630) para compartir links |
| `web/` | favicon.ico/svg, apple-touch-icon, íconos PWA, `site.webmanifest`, `head-snippet.html` |

En el sitio, `src/components/Logo.astro` usa `currentColor` para el texto, así que cambia solo con el modo claro/oscuro.

## Color

| Nombre | HEX | RGB | CMYK (aprox.) | Uso |
| --- | --- | --- | --- | --- |
| Tinta | `#1A1A1A` | 26 26 26 | 0 0 0 90 | Texto del logo, fondo del ícono |
| Queso | `#F4C430` | 244 196 48 | 0 20 80 4 | Solo la línea de volcanes y acentos |

Pantone cercano: 7408 C; confirmar con una muestra impresa antes de imprimir.
El amarillo sobre blanco tiene poco contraste: **nunca** se usa para texto, solo para la línea.

## Reglas

- **Espacio libre:** alrededor del logo, como mínimo la altura del volcán izquierdo (≈ la altura de la "u").
- **Tamaño mínimo:** logo horizontal 64 px de ancho en pantalla / 20 mm impreso; por debajo de eso, usar el ícono.
- **Ícono:** 16–32 px usa `quami-icon-small.svg`; desde 48 px, `quami-icon.svg`.
- **Tipografía:** el texto es Geist ExtraBold (SIL Open Font License, permite uso en logo) convertido a trazados con
  tracking −3 %. No hay que reescribirlo con una fuente; usar siempre los archivos.

## No hacer

- Cambiar los colores, poner la línea en otro color que no sea queso o tinta.
- Mover los volcanes de debajo de la "m", invertir el orden de alturas o redondear los picos.
- Estirar, inclinar, añadir sombras, contornos o degradados.
- Poner el logo principal (texto tinta) sobre fondos oscuros: usar `-reversed`.
- Escribir "Quami" con mayúscula dentro del logo.

## Pendiente

- Búsqueda de marca registrada profesional antes de registrarlo.
