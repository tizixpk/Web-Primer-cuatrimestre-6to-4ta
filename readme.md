Qué tiene y cómo lo explicás en clase:
La web tiene 5 secciones, todas en un solo archivo HTML:
1. <nav> — Barra de navegación
Es el menú superior que siempre se ve mientras scrolleás (position: sticky). Tiene el logo y los links que llevan a cada sección de la misma página con href="#id".
2. .hero — Portada
La primera pantalla que ve el usuario. Tiene un título grande, una descripción y un botón que te lleva a los productos.
3. .categorias — Grilla de 4 categorías
Usa display: grid con grid-template-columns: repeat(4, 1fr) para dividir la pantalla en 4 columnas iguales automáticamente.
4. .productos — Grilla de 6 productos
Igual que las categorías pero con 3 columnas. Cada producto tiene imagen (emoji), nombre, precio y un botón.
5. footer — Pie de página
Con información del negocio, links y el copyright.
Conceptos que podés mencionar al explicar:

Variables CSS con --nombre para los colores (cambiás un color y cambia en toda la web)
display: flex para poner cosas una al lado de la otra
display: grid para hacer las grillas de productos
hover para los efectos cuando pasás el mouse
transition para que los efectos sean suaves
