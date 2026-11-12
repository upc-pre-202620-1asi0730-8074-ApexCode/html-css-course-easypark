# Curso de HTML y CSS para principiantes: Mi Perfil Gamer

## Resumen del curso

Este curso está dirigido a estudiantes de secundaria que quieren aprender a crear páginas web desde cero. A lo largo de las lecciones construiremos "Mi Perfil Gamer": una tarjeta web personal con nuestro nombre, una foto, nuestros juegos o hobbies favoritos y un enlace a nuestras redes. Comenzaremos mostrando el contenido más simple y, poco a poco, incorporaremos imágenes, listas, enlaces y estilo propio hasta tener una tarjeta completa.

Los ejemplos se trabajan directamente en el navegador, usando [CodePen](https://codepen.io). Cada lección incluye una práctica con el código inicial y una versión resuelta para comparar los resultados. Puedes detenerte, modificar los datos y volver a ejecutar la página mientras sigues la explicación.

- **Público objetivo.** Estudiantes de 12 a 17 años sin experiencia previa en programación.
- **Prerrequisitos.** Manejo básico del navegador y del teclado.
- **Herramientas necesarias.** Un navegador web, conexión a internet y una cuenta en [CodePen](https://codepen.io). No es necesario instalar nada.

El código del curso y las actividades están disponibles en el repositorio del equipo. [Repositorio de GitHub](https://github.com/upc-pre-202620-1asi0730-8074-ApexCode/html-css-course-easypark).

## Secuencia de lecciones

### Lección 1 · ¿Qué es el desarrollo web?

**Descripción.** Aprende qué es un sitio web y por qué HTML y CSS son los dos bloques básicos para construirlo: HTML pone el contenido (texto, imágenes, enlaces) y CSS le da el estilo (colores, fuentes, diseño). Verás una comparación entre una página sin estilo y la misma página con estilo, para entender a dónde vamos a llegar a lo largo del curso.

- **Conclusiones clave.** Un sitio web = Contenido (HTML) + Estilo (CSS). A lo largo del curso vamos a construir una sola tarjeta de perfil, lección a lección.
- **Ponlo en práctica.** Antes de seguir, piensa qué nombre o apodo, qué foto y qué 3 juegos o hobbies favoritos vas a usar en tu propio perfil — los necesitarás desde la próxima lección.
- **Enlace al video.** [Ver la lección](https://youtu.be/0fDSfKxArlk)

---

### Lección 2 · Introducción a HTML

**Descripción.** Aprende las etiquetas HTML básicas (`html`, `head`, `body`, `h1`, `p`) armando el esqueleto de "Mi Perfil Gamer": tu nombre y una frase de presentación.

- **Conclusiones clave.** Toda página HTML tiene `<html>`, `<head>` y `<body>`. `<h1>` es un encabezado grande y `<p>` es un párrafo de texto. Cada etiqueta que se abre se debe cerrar.
- **Ponlo en práctica.** Completa el título de la pestaña y la etiqueta del cuerpo donde dice `[COMPLETAR]`, y cambia el nombre y la frase de ejemplo por los tuyos.
- **Enlace al video.** [Ver la lección](https://youtu.be/u4O0H_u1J2I)

---

### Lección 3 · Añadir más elementos HTML

**Descripción.** Aprende a agregar una imagen de perfil con `<img>`, una lista de tus juegos o hobbies favoritos con `<ul>`/`<li>`, y un enlace a tus redes con `<a>`.

- **Conclusiones clave.** `<img>` necesita `src` (de dónde viene la imagen) y `alt` (una descripción). `<ul>` agrupa una lista y cada `<li>` es un elemento de la lista. `<a href="...">` convierte un texto en un enlace clicable.
- **Ponlo en práctica.** Completa la URL y la descripción de la imagen, agrega tus 3 juegos o hobbies favoritos a la lista, y pon el enlace a tu red social favorita.
- **Enlace al video.** [Ver la lección](https://youtu.be/_hMGW54FCFw)

---

### Lección 4 · Introducción a CSS

**Descripción.** Aprende a dar estilo a tu perfil con CSS: selectores de etiqueta (como `body` y `h1`) y selectores de clase (como `.lista-juegos`), cambiando colores, tipografía y espaciado.

- **Conclusiones clave.** CSS se escribe dentro de `<style>` en el `<head>`. Un selector de etiqueta (`h1 { }`) afecta a todos los elementos de ese tipo; un selector de clase (`.lista-juegos { }`) solo afecta a los elementos que tengan ese `class`.
- **Ponlo en práctica.** Completa la fuente, el color de fondo y el color de texto del `body`, dale un color distinto a tu `<h1>`, y ajusta el espaciado de tu lista de juegos.
- **Enlace al video.** [Ver la lección](https://youtu.be/f3CbdSvGKl8)

---

### Lección 5 · Proyecto final: la tarjeta completa

**Descripción.** Integra todo lo aprendido para terminar "Mi Perfil Gamer" en forma de tarjeta centrada en la pantalla, con bordes redondeados, sombra e imagen de perfil circular.

- **Conclusiones clave.** `display: flex` + `justify-content: center` centran la tarjeta. `border-radius` redondea esquinas (y en 50% vuelve una imagen un círculo). `box-shadow` agrega una sombra que da sensación de profundidad. Un `<div>` agrupa elementos para darles estilo en conjunto.
- **Ponlo en práctica.** Completa el `justify-content`, el ancho máximo, el `border-radius` y el `box-shadow` de la tarjeta, y reemplaza todos los datos de ejemplo por los tuyos.
- **Enlace al video.** [Ver la lección](https://youtu.be/qhP2pV9tGwI)

---

### Lección 6 · Consejos y próximos pasos

**Descripción.** Revisa los errores más comunes de un principiante (etiquetas sin cerrar, llaves `{ }` de CSS sin cerrar, atributos mal escritos), cómo revisar el código cuando algo no se ve bien, y dónde seguir aprendiendo después del curso.

- **Conclusiones clave.** Si la página se ve rota, revisa primero que cada etiqueta HTML esté cerrada y cada bloque de CSS tenga su `}`. Prueba los cambios de a poco en vez de escribir todo de un tirón.
- **Ponlo en práctica.** Provoca a propósito un error (borra una `}` de tu CSS) y observa qué pasa con el estilo de la página; luego corrígelo.
- **Enlace al video.** [Ver la lección](https://youtu.be/qhP2pV9tGwI)

---

## Cómo utilizar las prácticas

Abre [CodePen](https://codepen.io) y copia el código de `starter-files` de la lección que estés siguiendo. Escribe tus cambios y observa el resultado en el panel de vista previa del navegador. Compara tu resultado con el archivo correspondiente en `completed-examples`.

## Para seguir practicando

Cuando termines tu tarjeta, cambia la paleta de colores completa, agrega un cuarto juego o hobby a la lista, y prueba agregar un segundo enlace a otra red social. Estas pequeñas modificaciones te ayudarán a comprobar qué parte del código controla cada resultado.

## Elaboración

- **Universidad y carrera:** Universidad Peruana de Ciencias Aplicadas, Ingeniería de Software
- **Curso:** Aplicaciones Web (1ASI0730), período 202620, NRC 8074
- **Equipo:** ApexCode

- Evangelista Ygnacio, Sergio Joaquin — U202211295
- Negrón Muñoz, Cayo Manuel Stefano — U202517482
- Martin Farro, Alexis Sebastian — U202515871
- Córdova, Alvar Lucas — U202324461
- Saravia Huaricancha, Arturo Axel — U202312447