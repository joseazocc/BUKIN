# BUKIN
Hola! Espero que estés muy bien. Este proyecto consta de una plataforma dedicada a la venta e intercambio de libros; una web desarrollada en Django que lleva el nombre de "Bukin". En esta versión de "Bukin" le permite a los usuarios registrarse en la plataforma y visualizar el listado de libros usados y nuevos publicados por el staff.

"Bukin" consta de los siguientes archivos:
- "apps": archivo que contiene los archivos 
      - "home" (funciones y templates del inicio de la web), 
      - "producto" (funciones y templates para listar los libros), 
      - y "venta" (funciones y templates para el historial de ventas del sitio).
 
- "config": archivo que contiene scripts para el funcionamiento de la plataforma.
- "media/avatars": imágenes que fueron usadas para distintas aristas de Bukin.

"Bukin" incluye las siguientes funcionalidades principales:

1. Registro de usuarios: Los usuarios pueden registrarse en la plataforma proporcionando su nombre y correo electrónico.
2. Inicio de sesión: Los usuarios pueden iniciar sesión dentro de la plataforma para acceder al contenido.
3. About/Sobre Mí: Apartado que data información sobre el creador de la plataforma.
5. Creación de libros: El staff de "Bukin" puede crear libros para ser publicados, ya sean usados o nuevos.
6. Listado de libros: Apartado que muestra que libros se encuentran disponibles, junto con los detalles del producto.
7. Generar ventas: Apartado que permite al staff de "Bukin" registrar las ventas que se han realizado.
8. Historial de ventas: Listado de las ventas que se han generado.

"Bukin" se ha desarrollado utilizando, principalmente, las siguientes tecnologías:

- Django: Framework de desarrollo web de alto nivel y en Python.
- HTML: Lenguaje de marcado utilizado para la estructura de las páginas web.
- CSS: Lenguaje utilizado para la presentación y estilización de las páginas web.

Para probar "Bukin" en un entorno local, debes seguir los siguientes pasos:

1. Clona este repositorio en tu PC.
2. Asegúrate de tener Python instalado en tu sistema.
3. Crea y activa un entorno virtual para el proyecto.
4. Instala las dependencias del proyecto ejecutando `pip install -r requirements.txt`.
6. Ejecuta las migraciones de la base de datos con el comando `python manage.py makemigrations' y luego 'python manage.py migrate'.
7. Inicia el servidor de desarrollo con `python manage.py runserver`.
8. Abre tu navegador y accede a `http://localhost:8000` para visualizar este proyecto.

A futuro, me gustaría que "Bukin" pudiera contener más funcionalidades, tales como una sección de reseñas creadas por los mismos usuarios y una opción crear clubs de lectura online, con el objetivo de crear una comunidad sólida de lectores en el mundo. En caso de cualquier comentario, propuesta y/o contribución que desees realizar, te dejo mi contacto para conversar sobre el proyecto "Bukin" o cualquier otra cosa relacionada a la programación. Muchas gracias! :-)

Nombre del desarrollador: José Azócar Berríos
Correo Electrónico: azocarberrios.j@gmail.com

Video explicativo: https://www.youtube.com/watch?v=q51CBaFPR0Y
