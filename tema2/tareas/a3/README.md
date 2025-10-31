# Actividad 3. Web con imágenes optimizadas.

## Objetivo

Crea un mini sitio web de 3 secciones (Inicio, Galería y Contacto) que use diferentes técnicas de HTML, CSS y JavaScript para insertar, optimizar y adaptar imágenes según el dispositivo y la resolución de pantalla.

## Requisitos

- Página de Inicio

    - Colocar una imagen de fondo que cambie según la resolución usando @media o image-set.

    - Incluir un logo con la etiqueta <img> y atributos alt, width, height y float.

- Página Galería

    - Mostrar al menos 3 imágenes adaptables con <picture> y srcset (para móvil, tablet y escritorio).

    - Incluir una imagen con áreas clickables (<map> y <area>) que lleve a enlaces externos (ej: redes sociales, páginas de interés).

    - Usar el truco de cargar primero una miniatura y luego, con JavaScript, sustituirla por la imagen real.

- Optimización

    - Incluir en el <head> de la página al menos un ejemplo de preload y otro de prefetch de imágenes.

    - Aplicar buenas prácticas: incluir siempre alt y definir tamaños para evitar parpadeos al cargar.

- Página Contacto

    - Incluir una imagen decorativa con <picture>.

    - Añadir un fondo con CSS que cambie en pantallas de alta resolución.

## Entregable

Una carpeta con el sitio web completo (index.html, galeria.html, contacto.html, hoja de estilos style.css, script script.js y las imágenes usadas).

Un documento breve (1 página) explicando qué técnicas de optimización aplicaron.

### Explicación

Como técnicas de optimización he utilizado las requeridas en la tarea:

- Primero, se han usado imágenes diferentes para el fondo del index y la galería, según la resolución. En el contacto, se ha utilizado un color diferente dependiendo de la resolución. 
- Luego en galería, que es la página con más fotos, se ha utilizado el "preload" y "prefetch" para darle prioridad a la carga de la imagen de picture. A parte de esto, use el picture con 3 imágenes diferentes cargadas, para que dependiendo del tamaño se viese una u otra.
- Finalmente, se ha utilizado el truco explicado por la profesora, cargar primero una miniatura y luego con JavaScript sustituirla por la imagen real.