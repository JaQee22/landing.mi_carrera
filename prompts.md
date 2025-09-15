# Bitácora de Prompts

Este archivo registra los prompts utilizados durante la creación del mini-sitio web "Mi Carrera en 4 Páginas" con ayuda de IA.

| Objetivo | Prompt | Respuesta Breve Obtenida | Aplicación |
|----------|--------|--------------------------|------------|
| Redactar descripción breve personal | "Ayúdame a redactar mi descripción: 30 años, madre de una hija de 10, trabajo en dropoff de residuos orgánicos y estudio Ingeniería Informática" | Texto profesional y cercano que describe vida personal, trabajo y estudios | Se colocó en `index.html` dentro de `<p>` como descripción breve |
| Redactar logros académicos | "Redacta logros académicos con: Arquitectura Cloud, Full Stack, Aplicaciones Básicas, Bases de Datos, Diseño Ágil, Soporte Computacional" | Texto estructurado y profesional detallando cada logro | Se colocó en `logros.html` en una lista `<ul>` con `<li>` |
| Redactar habilidades y competencias | "Redacta habilidades y competencias de una Ingeniera Informática basándote en los logros académicos previos y experiencia laboral" | Lista clara de habilidades técnicas y blandas | Se colocó en `habilidades.html` con lista `<ul>` y checkmarks en CSS |
| Redactar gustos personales | "Redacta un texto fluido y cercano sobre mis gustos: música, cine, computación, familia y amigas" | Texto amigable y profesional | Se colocó en `gustos.html` dentro de `<p>` |
| Crear footer con ola SVG, copyright y redes sociales | "Genera HTML y CSS para un footer con ola SVG decorativa y redes sociales centradas" | Código funcional que integra la ola SVG, iconos de Font Awesome y copyright | Se implementó en `footer` de todas las páginas |
| Centrar foto y párrafo | "Cómo centrar la foto de perfil y el párrafo de descripción en HTML y CSS" | Código CSS usando `margin: 0 auto` y `text-align: center` | Se aplicó en `index.html` y `styles.css` |
| Hacer sitio responsivo | "Hacer mini-sitio web responsive mobile-first" | CSS con media queries para menú hamburguesa y adaptación de imágenes | Se aplicó en `styles.css` con menú toggle y `meta viewport` |
| Agregar iconos de redes sociales | "Agregar iconos de redes con Font Awesome en HTML y CSS" | Código HTML `<i class="fab fa-...">` y estilos CSS para hover | Se implementó en footer y sección de inicio |
| Agregar checks a lista de habilidades | "Agregar check verde a cada habilidad en la lista usando CSS" | Código CSS con pseudo-elemento `::before` y contenido ✔ | Se aplicó en `habilidades.html` con clase `.habilidades` |
