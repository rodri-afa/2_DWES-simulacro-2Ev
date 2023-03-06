# DWES | Simulacro 2ªEvalucación

## Enunciados:

### 1_PDO: Bases de datos

**(4 pts)** Crea una base de datos importando el fichero sql dado. Realizar todo el ejercicio en la carpeta `1_PDO`

1. **(1 pts)** Crea un arhcivo `1_conexion.php` con una conexión PDO y realiza una consulta que devuelva el listado de películas _dirigidas por Tarantino_

2. **(1,5 pts)** En un archivo `2_vista.php`, importa la conexión y muestra el listado de películas anterior con todos sus detalles.

3. **(1 pts)** Utiliza bootstrap para mostrar las películas en un formato de tarjeta teniendo en cuenta el responsive:

   - 3 tarjetas por fila en dispositivos grandes

   - 2 tarjetas en medianos

   - 1 tarjeta en dispositivos pequeños

4. **(0,5 pts)** Cuida los estilos, el formato, la jerarquía de contenido, etc…

### 2_Laravel

**(6pts)** Crea un proyecto de Laravel llamado `2_Laravel-Libros` para una webapp que mostrará un listado de libros(titulo, autor, fecha y estado) en la que se podrán crear nuevos libros o borrar ya existentes:

1. **(0,5 pts)** Configura y crea una BBDD llamada 201_DWES-Nombre_Apellido, (donde Nombre será sustituido por tu nombre y Apellido por tu primer apellido)

1. **(1 pts)** Utiliza las rutas y funciones de un controlador para poder añadir, borrar y mostrar todos los libros.

1. **(1 pts)** Una vista que muestre todos los libros, permita añadir nuevos libros

1. **(1pts)** Añadir un selector de estado en cada libro (“pendiente” o “leído”) y un filtro de búsqueda que permita mostrar sólo los pendientes, sólo los leídos o todos.

1. **(1 pts)** Utiliza un layout general que contenga el header de la aplicación con el título de esta (Ej. “Mis libros”) y el apartado de añadir libros y el listado de libros en secciones aparte.

1. **(0,5 pts)** Crea los factories, migraciones y seeders correspondientes

1. **(0,5 pts)** Utiliza Bootstrap

1. **(0,5 pts)** Cuida los estilos, el formato, la jerarquía de contenido, etc…
