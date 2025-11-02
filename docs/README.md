# Práctica: Replica tu perfil de Instagram (HTML + CSS + SASS)

Bootcamp – Sprint 1  
Alumno: Tu Nombre

## Objetivo
Replicar la vista “feed” de tu propio perfil de Instagram utilizando únicamente HTML y CSS, aplicando el pre-procesador SASS para organizar los estilos.

## Tecnologías
- HTML5 semántico
- CSS3 / Flexbox
- SASS (estructura 7-1 o simple `/scss → main.scss → style.css`)

## Estructura del proyecto

instagram-replica/
├─ index.html
├─ css/
│  └─ style.css      (generado)
├─ scss/
│  ├─ main.scss
│  ├─ _variables.scss
│  ├─ _header.scss
│  ├─ _profile.scss
│  ├─ _gallery.scss
│  └─ _reset.scss
├─ assets/
│  └─ img/           (fotos, iconos, svg)
└─ README.md

## Decisiones de diseño
- Mobile-first: breakpoint 768 px para escritorio  
- Paleta de colores exacta a Instagram (extraída con color-picker)  
- Iconos en SVG inline para evitar peticiones extra  
- Galería de fotos con grid responsive (minmax + auto-fill)

## Pendientes / mejoras
- Añadir animación hover en las fotos  
- Implementar modo oscuro con variables CSS

## Autor
KevDeveloperfront – (https://github.com/KevDeveloperfront)