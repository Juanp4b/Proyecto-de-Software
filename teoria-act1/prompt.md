Vas a armar un sitio web estático (sin scripts) con HTML, CSS y WCAG. El tema es anunciar mascotas perdidas.
Elementos que deben estar:

- Tema principal del sitio: verde azulado (color de acento) y blanco crema. Fuente: Arial 15px. El sitio debe ser responsivo.

- Página principal: "Mascotas Perdidas". Debe haber un listado de mascotas, en forma de galería (cuadrícula) centrado en la página. Cada ítem es una carta cuadrada con bordes redondeados y sombra. Está compuesto por: 1 foto cuadrada (200px) (en caso de no serlo, forzarlo a ser cuadrada), el nombre de la mascota y un botón "+ Info" (con forma de píldora) debajo del nombre y la foto. TODOS los ítems tienen el mismo borde (color de acento oscuro 3px), mismo padding (20px) y margin (12px). Los datos (fotos e info) van a ser guardados en dos carpetas distintas: "imagenes" (archivos png o jpeg con nombre "gato_2" o "perro_1", es decir, "{categoria}_{id}") e "info" (archivos pdf con el mismo nombre que el archivo imagen; el mismo va a ser abierto al hacer clic en "+ Info"). La galería tiene, encima suyo, dos pestañas centradas que corresponden a las categorías: "Perros" y "Gatos"; por ende, solo se van a mostrar los ítems de la categoría seleccionada (por defecto, se muestran Perros). Cada ítem con su imagen e info va a estar obtenido de los archivos existentes, es decir, lee las fotos y pdf para determinar cuáles mostrar (si hay coincidencias de id).

- Página de contacto: "Contacto". Se muestra un formulario con las siguientes preguntas: "Nombre y Apellido", "Teléfono", "Correo electrónico", "Dirección", "¿Qué mascota está interesado en adoptar?" (desplegable con todas las mascotas a elegir), "¿Por qué está interesado en adoptar?", "¿Por qué usted es la mejor opción para adoptar?". Por último, un botón de "Enviar" (en forma de píldora y con color de acento), que muestre un mensaje de que éxito. El botón se deshabilita si hay algúna pregunta sin completar. Todo el formulario debe estar centrado.

- Página de administración: "Administración". Solo se muestra texto de las personas que mantienen el sitio. En este caso, mostrar: "Administrador - Juan Pablo Agnusdei - Estudiante de Licenciatura en Informática".

- Barra de navegación (color de acento) en la parte superior con: Logo (un hueso), Mascotas Perdidas, Contacto, Administración. Los botones se mezclan con la barra de navegación, y solo son distinguibles (color más oscuro, cuadrados encajando la altura de la barra) al pasar el mouse por encima. Los botones redirijen a la página de tal nombre. Los botones están centrados en la página. La barra hacela sombreada.

- El archivo CSS debe ser llamado "estilosIA.css".

- Generá 3 imagenes de mascotas (perros y/o gatos) junto con sus pdf correspondientes. Inventá la información de adentro para un caso de mascota perdida en general (se usa de ejemplo).

- Todo el sitio debe ser accesible por teclado (tabulador) y poder ser leído por lectores externos (añadir texto alternativo a las imágenes de los ítems, que lean el "Foto de {nombre}").
