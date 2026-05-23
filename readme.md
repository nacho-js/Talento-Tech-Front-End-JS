# Proyecto Front-End JS Talento Tech 26126

Consiste en el desarrollo Front-End de un E-Commerce. En este caso elegí un pet-shop.
Podes encontrar el proyecto en [mi pagina de GitHub Pages](https://nacho-js.github.io/Talento-Tech-Front-End-JS/HTML/index.html)

## Tecnologías Utilizadas

- HTML.
- CSS (_FlexBox_).
  > De momento no fue necesario utilizar `Media Queries` ya que el `flexbox` esta resolviendo bien el resizing.

## Tecnologías pendientes de implementación

- JS.
- SQL.
- Frameworks.

## Próximas mejoras

### `index.html`

1. Spacing entre `header` y `details`
2. Spacing entre `details` y `table`.
   > Probablemente implemente un `display:flex` con `flex-direction:column`
3. Imágenes para los elementos `summary`.

### `contact.html`

1. Spacing entre `header` y `div`.
2. Centrado interno de los `div`'s que componen el contenedor flexbox.

## En desarrollo

### Sección de productos

Falta desarrollar las cartas y el `flexbox` con los productos.
Mi idea es utilizar los atributos de id en el href de cada sección para enviarlos a los productos de la mascota seleccionada.

### Sección de servicios

La idea seria integrar un calendario para poder reservar turnos de peluquería canina.
También un carrusel de fotos de mascotas que ya pasaron por la peluquería.

### Sección de sobre nosotros

- Breve texto contando los inicios de la empresa.
- Algún video de presentación.
- Fotos del local.
- `iframe` con google maps embebido.

### Búsqueda de productos

Por lo que ví FormSpree no permite realizar peticiones get con su version free, por lo que quedara pendiente para el momento de integrar la base de datos.
