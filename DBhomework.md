# DBhomework

# Definicion de relaciones
Las relaciones entre tablas como su nombre indica, es como se van a relacionar las distinta tablas dentro de la base de datos,para esto se utiliza un sistema de claves donde la clave de una tabla apunta a la tabla relacionada, dependiendo de la cardinalidad es el tipo de clave que se comparte entre tablas

Cardinalidad uno a uno
Ejemplos

Personas |--| Dni
Viajeros |--| Pasaporte
Paises |--| Presidente
Taxi |--| Licencia
Motores |--| Numero de motor

Cardinalidad uno a muchos

Marca |--< Modelo
Paises |--< Provincias
Codigo area |--< Celulares
Empresa |--< Empleados
Escritor |--< Libros

Cardinalidad muchos a muchos

Carrera >--< Materias
Viajeros >--< Paises visitados
Vehiculos >--< Colores
Zapatillas >--< Talles
Personas >--< Hobbies

# Que es un SGBD
Es un sistema gestor de base de datos, es un software encargado de procesar toda la funcionalidad de la base de datos. Por ejemplo agregar/modificar/eliminar registros, acceder a la informacion de las tablas.
Cumpliria la funciond interfaz entre los usuarios y los datos almacenados en la DB

SGBD mas conocidos
SQL Server
MySQL
MongoDB
Oracle Database
Db2

# Diferencias entre relacionales y lo relacionales
Las DB relacionales se caracterizan por la division de sus datos en pequeñas entidades, relacionando estas mismas mediante un sistemas de claves compartidas. Se debe contar desde un principio con un diagrama de la base de datos ya que pequeños cambios afectan a todas las relaciones.
Las DB no relacionales no tienen un sistema de relaciones por lo cual son mas sencillas de utilizar cuando uno no tiene en claro el diseño de la base de datos, con gran cantidad de datos se pueden volver poco eficientes
