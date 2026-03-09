Vila-real SportFest 2026
https://CAPTURAS/captura-home.png

Este es el repositorio del sitio web del Vila-real SportFest 2026, el evento deportivo que este año vuelve a las instalaciones municipales de Vila-real con más fuerza que nunca.

Descripción del proyecto
He creado una página web informativa para el Vila-real SportFest 2026, un evento organizado por el Ayuntamiento de Vila-real que se celebrará los días 10, 11 y 12 de abril de 2026.

La web está pensada para que la gente pueda enterarse bien de qué va el evento, qué deportes hay, los horarios y cómo contactar con la organización. Me he centrado en que sea clara, que se vea bien tanto en el móvil como en el ordenador, y que tenga un diseño llamativo pero sin ser demasiado recargada.

Para maquetarla he usado Bootstrap 5, que me ha ayudado mucho a hacerla responsive sin tener que escribir demasiado CSS desde cero.

Secciones y columnas de Bootstrap
Aquí explico cómo he organizado cada sección de la página y cómo he usado el sistema de columnas de Bootstrap en cada una:

Navbar
Barra de navegación superior fija. Ocupa todo el ancho (12 columnas) y se colapsa en móvil.

Hero
Cabecera principal con título grande y botón. También ocupa las 12 columnas.

Qué es
Texto explicativo a la izquierda (col-md-6) e imagen a la derecha (col-md-6).

Modalidades
Aquí he usado columnas responsivas: 1 en móvil (col-12), 2 en tablet (col-sm-6) y 3 en escritorio (col-lg-4) para mostrar las cards de cada deporte.

Programa e info
Columna única (col-12) con una lista del horario y una tarjeta con información práctica.

Contacto
Formulario centrado ocupando 8 columnas en pantallas medianas (col-md-8 mx-auto).

Footer
Dividido en dos mitades: copyright a la izquierda (col-md-6) y redes sociales a la derecha (col-md-6).

Componentes de Bootstrap que he usado
He intentado aprovechar los componentes que trae Bootstrap para ahorrar trabajo y darle un aspecto más profesional:

Navbar → Para el menú de navegación, con el típico menú hamburguesa en móvil.

Grid system → Para maquetar todas las secciones, sobre todo en "Qué es" y "Modalidades".

Cards → En la sección de deportes, cada modalidad va dentro de una card con borde redondeado y sombra.

Botones → Para los llamados a la acción (inscribirse, enviar formulario, etc.).

List group → En el programa, para mostrar los horarios de forma ordenada.

Badges → Los he puesto en la lista del programa para marcar cosas como "gratuito" o "plazas limitadas".

Utilities → Clases como mt-5, p-3, text-center, etc., para ajustar márgenes y alineaciones rápidamente.

Historial de commits y mejoras
He ido subiendo los cambios poco a poco para que se vea la evolución del proyecto. También he creado una rama aparte para trabajar una mejora concreta y luego la he fusionado con pull request.

Rama principal: main
feat: estructura inicial del proyecto
Primer commit con el esqueleto básico: archivo index.html, carpeta para css, carpeta para imágenes, y enlaces a Bootstrap puestos.

feat: seccion "que-es" con grid de 2 columnas
Añadida la sección que explica el evento, con texto a un lado y foto al otro usando las columnas de Bootstrap.

feat: seccion "programa" con list-group y badges
Creada la parte del horario. Usé list-group para los días y badges para destacar información importante.

Rama secundaria: feature/mejora-modalidades
Me creé esta rama para tocar la sección de deportes sin miedo a romper lo que ya funcionaba:

feat: crear rama feature/mejora-modalidades
Primero creé la rama nueva desde GitHub y luego la bajé a mi ordenador.

style: mejorar diseño de las cards en modalidades
Aquí retoqué las cards: les puse sombra suave y un efecto hover para que se levanten un poco al pasar el ratón.

feat: añadir iconos a las cards de deportes
Busqué iconos de Bootstrap Icons para cada deporte (fútbol, basket, carrera, pádel, fitness) y los metí dentro de las cards.

fix: ajustar espaciado en movil para seccion modalidades
Me di cuenta de que en móvil las cards quedaban muy separadas, así que ajusté los márgenes para que se viera mejor.

Fusión a main
Merge pull request #1 from feature/mejora-modalidades
Cuando terminé los cambios en la rama secundaria, hice un pull request desde GitHub para fusionarlo con la rama principal y lo acepté después de comprobar que todo iba bien.

La mayor dificultad que encontré y cómo la solucioné
Lo que más me costó fue ajustar el navbar y las columnas para que se comportaran bien en todos los tamaños de pantalla.

Al principio, cuando reducía la ventana, el menú se me montaba encima del contenido de la página, y en la sección de modalidades las cards no se recolocaban bien, dejando espacios raros.

Cómo lo solucioné:
Me puse a trastear con las herramientas de desarrollador del navegador (F12) para ver qué clases de Bootstrap estaban actuando en cada momento. Así fui probando diferentes combinaciones de columnas (col-sm, col-md, col-lg) hasta que entendí cómo funcionaban los puntos de ruptura. También tuve que meter algo de CSS personalizado para que el navbar cambiara de color al hacer scroll sin perder su funcionalidad responsive.

Al final, con paciencia y probando mucho, conseguí que quedara bien en móvil, tablet y escritorio.

Capturas de pantalla
En la carpeta CAPTURAS/ he dejado varias fotos del resultado final:

captura-home.png → Vista general de la página en ordenador.

captura-modalidades.png → La sección de deportes con las cards mejoradas y los iconos.

captura-movil.png → Cómo se ve la web en un móvil, para comprobar que es responsive.
