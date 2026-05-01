---

#  Estructura de la Web Pirez Tiziano 6to 4ta

##  Qué tiene la página00

La web tiene **6 secciones principales**, todas dentro de un solo archivo HTML:

---

## 1. `<nav>` — Barra de navegación

Es el menú superior que se mantiene visible al hacer scroll (`position: sticky`).

 Contiene:

* Logo de la página (PiRez)
* Links de navegación interna (`href="#id"`)

 Función:
Permite moverse entre secciones sin cambiar de página.

---

## 2. `.hero` — Portada

Es la primera sección que ve el usuario.

 Contiene:

* Título grande
* Texto descriptivo
* Botón que lleva a productos

 Función:
Captar la atención y guiar al usuario.

---

## 3. `.categorias` — Grilla de categorías

Muestra 4 categorías principales.

 Usa:

```css
grid-template-columns: repeat(4, 1fr);
```

 Función:
Divide la pantalla en 4 columnas iguales automáticamente.

---

## 4. `.productos` — Productos destacados

Muestra productos en formato tarjeta.

 Características:

* Imagen
* Nombre
* Precio
* Botón "Agregar al carrito"

 Usa:

```css
display: grid;
grid-template-columns: repeat(3, 1fr);
```

---

## 5. `#oferta` — Banner + sección de ofertas

🔹 Tiene 2 partes:

### 🟣 Banner

* Texto promocional
* Botón de acción

###  Productos en oferta (dinámico)

* Se muestran automáticamente con JavaScript
* Solo aparecen los que tienen:

```html
<span class="badge badge-oferta">Oferta</span>
```

Función:
Destacar productos con descuento sin duplicar código.

---

## 6. `<footer>` — Pie de página

 Contiene:

* Información del negocio
* Links útiles
* Contacto

 Función:
Cerrar la página con info importante.

---


✔ Permite dividir en columnas automáticamente

---

##  `hover`

Efecto cuando pasás el mouse por encima.

 Ejemplo:

* Cambiar color
* Agrandar tarjeta

---

##  `transition`

Hace que los cambios sean suaves.

 Ejemplo:

```css
transition: 0.3s;
```

---

