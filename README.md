# ECommerce
### Actividad final para proyecto de All4Business

Hemos recibido el encargo de crear un e-commerce sobre gafas de sol y nuestro CTO decide que lo vamos a realizar utilizando Symfony 3.4, así que nuestro diseñador se pone manos a la marcha y  obtenemos las siguientes pantallas.

Nuestra home es la siguiente.
![alt_text](https://github.com/GeeksHubsAcademy/ProyectoEcommerce/blob/master/tienda%20primera%20p%C3%A1gina.jpg)

Podemos observar que tiene un header, footer, un menu lateral y una página principal donde ya aparecen un listado de gafas que se encuentra en la vista.

El detalle de cada producto se verá de la siguiente forma.
![alt_text](https://github.com/GeeksHubsAcademy/ProyectoEcommerce/blob/master/tienda%20geek%20ficha%20de%20producto.jpg)
 
 Donde obtendremos toda la información de la gafa.
 
Y por último tenemos nuestro carito de la compra:
![alt_text](https://github.com/GeeksHubsAcademy/ProyectoEcommerce/blob/master/tienda%20geek%20carrito%20de%20compra.jpg)
Aquí se encuentra toda la información y detalles de las gafas que hemos adquirido así como en la parte inferior debe aparecer un listado de otras gafas.

---

## Condiciones.
* Se realizará entéramente en Symfony.
* Se deberá implementar el :
  * Login.
  * Registro.
  * Perfil de personal.
  * Listado de productos.
  * Descripción de producto individual.
  
* Se realizará todas las conexiones de las bases de datos mediante la creación de migraciones y las correspondientes entidades utilizando Doctrine

---

### Características.
* Se utilizará COMPOSER para la instalación de dependencias.
* En la parte de admin podemos añadir y gestionar los productos.
* El usuario podrá comprobar su carrito.

### Otras Funcionalidades
* El proyecto debe estar subido en un contendor doker:
  * Debe disponer de un docker-compose con un stack que nos levante un servidor Ubuntu y otro con un MySql.
  * El contendor debe tener abierto el puerto 80 y apuntara internamente al puerto 80 donde tenemos apuntado nuestro servidor 
  * Debemos generar una nueva carpeta en nuestra estructura denominada log, donde se almacenará un log de los posibles errores que se produzcan en la aplicación.
* Podemos crear una api rest para poder dar servicio a otras aplicaciones.
