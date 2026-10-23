# Electrocar — E-commerce con CSS Media Queries

Catálogo de vehículos desarrollado como ejercicio del **Módulo de CSS Avanzado (Media Queries)** de mi formación en Desarrollo Web Front-End con Desafío Latam.

Este proyecto es la **octava pieza de mi portafolio**, después de `01-curriculum-futbolista` (HTML básico), `02-curriculum-vitae-jferro` (Bootstrap 5), `03-pizzeria-ramos` (CSS), `04-flexbox-iguana` (Flexbox), `05-bootstrap-cuppon` (Bootstrap 5), `06-flexbox-chat` (Flexbox) y `07-css-grid-ecommerce` (CSS Grid).
Aquí profundicé en el diseño **responsive**, adaptando la interfaz a móvil, tablet y escritorio.

---

## 🎯 Objetivo

Practicar el uso de CSS Media Queries en un layout real de e-commerce:

- **Enfoque mobile-first** o adaptación progresiva del layout
- **Cambio de estructuras de Grid** según el tamaño de la pantalla
- **Ocultar/mostrar elementos** (menú de hamburguesa) según el dispositivo
- **Ajuste de columnas** automático para las tarjetas de productos
- **Diseño adaptativo** de la barra de filtros y navegación

---

## 🛠️ Tecnologías usadas

- **HTML5** — estructura semántica
- **CSS3** — estilos, Grid, Flexbox, responsive
- **CSS Grid** — layout principal (header, aside, main, footer)
- **Flexbox** — componentes internos
- **Media Queries** — 2 breakpoints principales (768px y 992px)
- **Font Awesome** — iconografía (menú hamburguesa y redes sociales)

---

## 📁 Estructura del proyecto

```text
08-css-media-queries/
├── index.html
├── README.md
├── .gitignore
├── .nojekyll
└── assets/
    ├── css/
    │   └── style.css       ← estilos propios
    └── image/
        ├── carro1.jpg
        ├── carro2.jpg
        ├── carro3.jpg
        ├── carro4.jpg
        ├── carro5.jpg
        ├── carro6.jpg
        ├── carro7.jpg
        ├── carro8.jpg
        └── logo-car.png
```

---

## 🎨 Secciones del sitio

1. **Header (superior en móvil / lateral en desktop)**
   - Logo de la marca "electrocar"
   - Menú de navegación (oculto en móvil, visible en desktop)
   - Ícono de hamburguesa para versión móvil
2. **Aside — Filtro (superior en móvil / superior derecho en desktop)**
   - Selector para "Ordenar por"
3. **Main — Catálogo (centro)**
   - Grilla responsive de 8 vehículos
   - Cada tarjeta incluye: imagen, título, precio y botón "Ver más"
   - Paginación inferior
4. **Footer (inferior)**
   - Redes sociales y copyright

---

## 🧠 Aprendizajes

- **Media Queries en profundidad:**
  - Uso de `@media screen and (min-width: 768px)` para el cambio de layout general.
  - Reorganización de `grid-template-areas` para mutar de una vista de 1 columna a una vista de 2 columnas (sidebar + main).
  - Ocultamiento de elementos (`display: none`) y reemplazo visual con el ícono de hamburguesa en pantallas pequeñas.

- **Layout híbrido (Grid + Flexbox):**
  - Grid para la estructura macro (contenedor principal con `grid-template-areas`).
  - Flexbox para alinear los elementos internos del menú, el logo y la paginación.
  - `display: grid` anidado para que las tarjetas de autos se reacomoden automáticamente (`repeat(auto-fill, minmax(...))`).

- **Estilos coherentes:**
  - Paleta de colores corporativa (azul `#00579c` y celeste).
  - Efectos hover suaves en botones y enlaces.
  - Uso de `object-fit: contain` en las imágenes para que los autos no se deformen y se vean completos.

- **Buenas prácticas:**
  - Estructura HTML semántica (`header`, `aside`, `main`, `footer`).
  - Uso correcto de entidades HTML (`&lt;&lt;` y `&gt;&gt;`) para la paginación.
  - Uso de `box-sizing: border-box` en el reset global.
  - Nombres de imágenes sin espacios ni mayúsculas.

---

## 📅 Línea de tiempo

- **2024** — Ejercicio original del Módulo de CSS Avanzado (Media Queries) en Desafío Latam
- **Octubre 2026** — Revisión profunda, corrección de errores estructurales y de responsive
- **Octubre 2026** — Publicado en GitHub como pieza de portafolio

---

## 👤 Autor

**Joaquín Ferro Vasco**
- 🎨 Diseñador Gráfico | Desarrollador Front-End en formación
- 📧 [joaquin.ferro@gmail.com](mailto:joaquin.ferro@gmail.com)
- 🐙 [GitHub](https://github.com/JoaquinFerro)
- 💼 [LinkedIn](https://www.linkedin.com/in/joaquin-felipe-ferro-vasco-b5a77046)
- 🌐 [Portafolio personal](https://joaquinferro.github.io/02-curriculum-vitae-jferro/)

---

*Este proyecto forma parte de mi proceso de aprendizaje en desarrollo front-end. Agradezco cualquier comentario o sugerencia.*