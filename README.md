# Web App Mis Videos Favoritos con Nodejs, Express y Mysql
Web app con nodejs, y javascript como lenguaje de programación backend y mysql como base de datos SQL. Puede crear, eliminar, actualizar, y listar los datos (videos).
Esta aplicación de NodeJS hace uso del motor de plantillas EJS, Bootstrap y librerías de express para conexión a mysql, en este ejemplo plantea la creación de un sitio 
con una navegación dinamica. Consta de un formulario diseñado con Bootstrap y funcionalidad de NodeJS con express, la estructura del proyecto separa las rutas de los partials(trozos de código que se pueden usar en cualquier parte del proyecto) y el funcionamiento (controllers).

La app muestra los vídeos favoritos en home ordenandolos por fecha de captura mas reciente,además tiene un filtro para categorizar los vídeos.
La captura se realiza en la ruta '/add' tomando los datos de el enlace del vídeo y su categoría,lo mustra en la pagina y lo agrega al darle clic al botón de aceptar.

# Navegación de la webapp
Desde la barra de navegación se puede acceder a las diferentes secciones de la página, en Add video se puede ingresar un nuevo video, se deben llenar los campos de nombre, link (este debe ser embebido), y categoría, al dar click en el  botón "Aceptar" se guarda en la BD y se reproduce automáticamente en está misma ruta. En la sección Home se listan los videos en la BD y con el botón editar o eliminar se pueden gestionar los registros. En esta misma sección está el apartado de mostrar por categoría, se trata de un select box con las opciones actualizadas de las categorías de la BD y al seleccionar una opción y dar click en el botón de "Mostrar" se listan los videos pertenecientes a dicha categoría.
En las secciones de Contacto y About son parte del esquema de la pagina de la practica MiPrimerPortalNode por lo que no tienen funcionalidad en la BD. 

# Express 
Express es un framework de NodeJS que nos ayuda simplificar la programación del lado del servidor con muchas menos líneas de código.

# Herramientas necesarias
Visual Studio Code, Node JS, Express, Zeit Now, Remote MYSQL
