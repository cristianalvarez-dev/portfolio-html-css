# Proyecto 1: HTML + CSS — Portfolio personal

Portfolio personal de **Cristian Álvarez**, desarrollado como primer proyecto entregable del Máster en Programación (thePower Education / Prometeo, alineado con FP Superior DAW).

Construido únicamente con **HTML5 semántico** y **CSS3**, sin frameworks ni JavaScript.

## Estructura del proyecto

```
portfolio-html-css/
├── index.html
├── styles.css
├── img/
│   ├── katas-javascript.webp
│   ├── katas-python.webp
│   ├── bases-de-datos.webp
│   └── nosql.webp
└── README.md
```

## Contenido

- **Header:** navegación fija con Flexbox.
- **Hero:** presentación del proyecto y del propósito del portfolio.
- **Bio:** sección "Sobre mí".
- **Proyectos:** galería en CSS Grid con los 4 trabajos del Máster (Katas JavaScript, Katas Python, Bases de Datos, noSQL), cada uno con su estado y enlace al repositorio correspondiente.
- **Contacto:** formulario y datos de contacto (email, GitHub, LinkedIn).
- **Footer:** enlaces a redes.

## Técnicas aplicadas

- HTML5 semántico (`header`, `nav`, `main`, `section`, `article`, `footer`).
- Variables CSS (`:root`) con prefijo `--at-` para centralizar colores, tipografías y medidas.
- Flexbox en header, tarjetas de proyecto y sección de contacto.
- CSS Grid en la galería de proyectos, con `repeat(auto-fill, minmax(240px, 1fr))` y `grid-auto-rows: minmax(200px, auto)` para adaptar el número de columnas al ancho disponible y dejar espacio flexible a las descripciones.
- Diseño responsive con media queries en 700px y 480px, y salvaguardas (`box-sizing: border-box`, `overflow-x: hidden` en `html`, `max-width: 100%` en imágenes) para evitar scroll horizontal.
- Comentarios en HTML y CSS documentando las decisiones tomadas en cada bloque.
