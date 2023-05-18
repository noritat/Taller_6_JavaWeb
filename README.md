
# Proyecto Respository pattern en Java.

Este proyecto consiste en realizar un Repository Pattern el cual nos proporcionar metodos como la CRUD (Crear, Consultar, Actualizar y Eliminar) ademas que su proposito principal es encapsular las operaciones de almacenamiento y recuperación de datos en un repositorio centralizado trabajando como interfaz:

# Respository Pattern :
![metodo2](https://github.com/noritat/Taller_6_JavaWeb/assets/128448216/81e7f94e-a5b4-4239-805e-90d5dafb0660)

Este proyecto tamnbien inlcuye una base de datos la cual la podemos crear por MYSQL Workbench:
# Script de la base de datos:
![base de datos](https://github.com/noritat/Taller_6_JavaWeb/assets/128448216/4a7ed1d0-44a6-4a86-a8b0-05836518858b)
# Consulta base de datos 
![Consulta-base de datos2](https://github.com/noritat/Taller_6_JavaWeb/assets/128448216/0824ad91-c246-44ef-9f1f-e6acd7a5ad65)


ademas de incluir lo anterior, tambien tendremos que hacer una conexion a base de datos denominada ConnectionPool:
# Conexion
![4 1](https://github.com/noritat/Taller_6_JavaWeb/assets/128448216/d1526adf-44cc-48df-a89c-bc354a3c43fd)

Por ultimo, tambien tendremos un login creado con diseño en la carpeta de la Vista(wwebapp).
![login](https://github.com/noritat/Taller_6_JavaWeb/assets/128448216/8366d3a8-ea83-4d39-8014-e727b6b2fee8)


# Requisitos

Para ejecutar este proyecto se necesitan los siguientes requisitos:
- Java 8 o superior
- Maven 2.9.0 o superior
- Una base de datos MySQL
- Widfly 27.0.1
- IntelliJ IDEA

# Configuración de la base de datos

Antes de ejecutar la aplicación, es necesario configurar la conexión a la base de datos en la carpeta Util dentro de las 4 clases presentadas anteriormente debe tener el siguiente contenido:

-  private static final String URL= "jdbcmysql://localhost:3306/my_app serverTimezone=America/Bogota";"
- private static final String USER ="El usuario que crees en mysql";
- private static final String PASS="la contraseña que quieras";

# Autor

Este proyecto fue creado por Angely Estrada.
Derechos reservados a Servicio Nacional de Aprendizaje (SENA).


![dependencias](https://github.com/noritat/Taller_6_JavaWeb/assets/128448216/167f2da2-e345-4bbc-9b19-6f310e73c819)




