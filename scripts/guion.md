# Mi Perfil Gamer — Guion de curso en video

Fundamentos de HTML y CSS · Trabajo complementario — Curso 1ASI0730 Aplicaciones Web
Periodo académico 202620 · Universidad Peruana de Ciencias Aplicadas (UPC)

## Reparto de lecciones (5 integrantes)

- Lección 1 — ¿Qué es el desarrollo web?
- Lección 2 — Introducción a HTML
- Lección 3 — Añadir más elementos HTML
- Lección 4 — Introducción a CSS
- Lección 5 y 6 — Proyecto final, consejos y cierre del curso

---

## LECCIÓN 1 — ¿Qué es el desarrollo web?

Hola, bienvenidos a "Mi Perfil Gamer" — un curso donde van a aprender a crear su propia página web, una tarjeta de perfil personal, como las que usan los gamers para presentarse. ¿Qué es un sitio web? Es simplemente un documento que tu navegador sabe leer y mostrar. Para construirlo usamos dos lenguajes: HTML, que pone el contenido — el texto, las imágenes, los enlaces — y CSS, que le da el estilo — los colores, las fuentes, el diseño. Piensen en HTML como el esqueleto de una casa, y CSS como la pintura, los muebles y la decoración.

Miren la diferencia: esto de acá es solo HTML, sin ningún estilo. Y esto otro es exactamente el mismo contenido, pero con CSS aplicado. A eso vamos a llegar juntos, lección a lección. Durante este curso van a construir su propia tarjeta: con su nombre o apodo, una foto, sus juegos o hobbies favoritos, y un enlace a sus redes. Todo esto corriendo en el navegador, sin instalar nada. Dale play a la siguiente lección y empecemos.

---

## LECCIÓN 2 — Introducción a HTML

En la lección pasada vimos qué es un sitio web. Ahora vamos a escribir nuestro primer HTML. Todo documento HTML empieza igual: una etiqueta html que envuelve todo, un head donde va información que no se ve en pantalla (como el título de la pestaña), y un body, que es donde va todo lo que sí se ve: textos, imágenes, botones.

Fíjense: h1 es un encabezado grande — lo usamos para el nombre o apodo de nuestra mascota... digo, de nuestro perfil. Y p es un párrafo normal, para texto corrido. Noten que cada etiqueta que abrimos la cerramos con una barra. Si se olvidan de cerrar una etiqueta, el navegador se puede confundir y el resultado se ve raro — así que ojo con eso.

Con solo estas etiquetas ya tenemos el esqueleto de nuestro perfil: un título y una frase de presentación. Abajo tienen el link a CodePen ya con esta plantilla — cambien el nombre y la frase por los suyos antes de pasar a la siguiente lección.

---

## LECCIÓN 3 — Añadir más elementos HTML

Ya tenemos el nombre y la presentación. Ahora vamos a darle más vida a nuestro perfil: una imagen, una lista de nuestros juegos o hobbies favoritos, y un enlace a nuestras redes.

La etiqueta img muestra una imagen — src es de dónde la trae, y alt es una descripción por si la imagen no carga, o para que la puedan "leer" personas con problemas de visión usando un lector de pantalla. Siempre hay que poner un alt. Para la lista usamos ul (lista con viñetas) y adentro un li por cada elemento. Y a href es un enlace: todo lo que esté entre la etiqueta de apertura y cierre se vuelve clicable.

Con imagen, lista y enlace, nuestro perfil ya cuenta mucho más sobre nosotros. Practiquen en el link de abajo: cambien la imagen, agreguen sus propios juegos o hobbies, y pongan el enlace a su red social favorita.

---

## LECCIÓN 4 — Introducción a CSS

Tenemos todo el contenido, pero se ve bastante simple — texto negro sobre blanco. Ahora toca la parte divertida: darle estilo con CSS. CSS funciona con selectores y propiedades: le decimos QUÉ elemento queremos cambiar, y QUÉ propiedad de ese elemento queremos modificar.

body selecciona toda la página y le cambia la fuente, el color de fondo y el color del texto. h1 selecciona solo los encabezados grandes — ahí le damos un color distinto a nuestro nombre. Y la clase lista-juegos es un selector de clase: para usarlo, le agregamos esa clase a nuestra etiqueta ul en el HTML, y así le damos estilo solo a esa lista, sin afectar el resto de la página.

Con unas pocas líneas de CSS, el mismo contenido ahora se ve completamente distinto. Prueben cambiar los colores y la fuente en el link de abajo, y vean qué combinaciones les gustan más para su propio perfil.

---

## LECCIÓN 5 y 6 — Proyecto final, consejos y cierre

Esta es la lección más importante: vamos a convertir nuestro perfil en una verdadera tarjeta — centrada en la pantalla, con bordes redondeados y una sombra, como las tarjetas de presentación que ven en apps y videojuegos.

Display flex y justify-content center centran nuestra tarjeta en medio de la pantalla. Border-radius redondea las esquinas — y si lo ponemos en 50% sobre la imagen, la vuelve un círculo perfecto, como una foto de perfil real. Y box-shadow agrega una sombra suave, para que la tarjeta parezca que "flota" sobre el fondo.

Para que todo este estilo se aplique junto, envolvemos nuestro contenido — la imagen, el nombre, la bio, la lista y el enlace — dentro de un div. Un div es como una caja invisible que agrupa elementos para poder darles estilo en conjunto.

¡Miren eso! Esto ya se ve como un perfil de verdad: foto circular, nombre destacado, lista de juegos y un enlace — todo centrado, con bordes redondeados y sombra. Esto es HTML y CSS trabajando juntos.

Antes de cerrar, un consejo rápido: si alguna vez su página se ve rota o el estilo no se aplica, revisen que cada etiqueta HTML esté cerrada y que cada bloque de CSS tenga su llave de cierre — ese es el error más común de principiante. Otro tip: siempre prueben los cambios de a poco, guardando y mirando el resultado, en vez de escribir todo de un tirón.

Y con esto llegamos al final del curso. En estas lecciones pasaron de no saber qué era HTML a construir su propia tarjeta de perfil, con contenido, estilo y diseño propio. El link de abajo tiene el código completo — anímense a personalizarlo con sus propios colores, su foto y sus juegos o hobbies favoritos. ¡Gracias por aprender con nosotros!