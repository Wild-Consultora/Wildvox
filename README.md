# Wild Vox · presentación web

Página de presentación de los servicios de la alianza **Wild Consultora + Vox Estrategias de Comunicación**
("La comunicación como activo estratégico").

Fuente del texto: [Google Doc](https://docs.google.com/document/d/19PG1ojV7Vab23Zu9DcyVUga2vEX6RgVvTi7dQ0rZyeo/edit).

## Archivos

- `index.html`: toda la página (textos, estilos y la pequeña interacción de las tarjetas).
- `img/wild.png`, `img/vox.png`: logos recortados de los manuales de marca.

## Cómo editar los textos

1. Abrí `index.html` (en GitHub: botón del lápiz ✏️).
2. Los textos están en orden de aparición. Cada sección empieza con un comentario así:
   `<!-- ===================== POR QUÉ ===================== -->`
3. Cambiá solo el texto entre las etiquetas (`<p>…</p>`, `<li>…</li>`, `<h3>…</h3>`). No borres las etiquetas.
4. Guardá con un mensaje corto ("Cambio bajada del producto 3").

### Partes de la página

| Sección | Qué contiene |
|---|---|
| PORTADA | Logos, nombre, slogan y bajada |
| POR QUÉ | Las 4 tarjetas BANI (se dan vuelta al tocarlas) y la frase de contexto |
| QUÉ HACEMOS | Activo estratégico, problemas (silos) y los 3 objetivos |
| CÓMO LO HACEMOS | Los 6 productos. Cada uno es un bloque `<details class="product">` |
| CIERRE | Frase final y logos |

### Productos

- Lo que está dentro de `<summary>` se ve siempre: número, título, frase corta y la etiqueta de formato (`chip`).
- Lo que está dentro de `<div class="product-body">` aparece al hacer clic.
- Para agregar un ítem a una lista, copiá una línea `<li>…</li>` y cambiá el texto.
- Para sumar un producto, copiá un bloque completo desde `<!-- ===== PRODUCTO N ===== -->` hasta su `</details>`.

## Colores (de los dos manuales)

| Token | Color | Marca |
|---|---|---|
| `--ink` | `#003731` dark green | Wild (≈ verde `#054F44` de Vox) |
| `--green` | `#376A62` myrtle green | Wild |
| `--mint` | `#B7DECE` tiffany blue | Wild |
| `--wisteria` | `#D3AAE0` (asterisco) | Wild |
| `--paper-2` | `#FEE9DD` champagne pink | Wild |
| `--coral` | `#E95132` | Vox |
| `--blush` | `#F5B1B2` | Vox |
| `--brick` | `#991915` | Vox |

Tipografías (Google Fonts, sustitutos libres de las de marca):
**Archivo** (cercana a Archivo Black de Vox y a Trade Gothic Extended de Wild) y
**Young Serif** (en lugar de Regards, para slogan y frases destacadas).

## Publicación

Dirección pública: https://wild-consultora.github.io/wildvox/

La página se publica gratis con **GitHub Pages** desde la rama `main` (carpeta raíz).
Cada cambio guardado en `main` se ve en la web en 1 o 2 minutos.

## Ver la página en tu compu

Abrí `index.html` con doble clic en el navegador.
