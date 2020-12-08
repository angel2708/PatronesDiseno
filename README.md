# PatronesDiseno
Este el proyecto de patrones de diseño

*modelo crearproducto-----hace llamada desde un objeto a una funcion creada en productos para crearlo en base de datos borrarprodcuto--hace llamada desde un objeto a una funcion creada en productos para borrarlos en base de datos resgistro------pagina donde se hace el registro requiriendo funciones de usuarios *vista templates- footer header ,head index---pagina de incio donde inicias sesion , ves los productos , te registras cliente.php-----pagina a la que se llega cuando se inicia sesion como cliente empleados.php------pagina que se accede cuando se inicia como un empleado mensajecorrecto------mensaje cuando accion de productos funciona mensajecorrectoindex-cuando no se completa el registro mensajeerroneo------mensaje cuando accion de productos va mal mensajeerroneoindex-cuando no se completa el registro

*controlador iniciarsesion---pag donde se inicia sesion y redirecciona segun sea empleado o cliente cerrarsesiom----cierra sesion con un mensaje de confirmacion previo

*clases.php-aqui se encuentran todas las clases
conexion.php - hecha con el patron singleton que lo instancia una sola vez productos-objeto productos , con las funciones para insertarlos , borrarlos de la base de datos usuarios -objeto usuarios , con sus funciones() super.php--clase super y sus funciones

El patron de diseño que vamos a utilizar es el factory y el singleton y el *decorator - para mostrar datos pero de forma distinta *singleton - este patron consiste en que solo se puede instanciar una vez un objeto , en nuestro caso la conexion de base de datos , que lo que hace es que si no esta creado lo crea y si esta creado no hace nada *adapter - Este patron sirve para crear dos objetos de una instancia que solo se diferencian en algo en concreto. En nuestro caso será para crear usuarios que se diferencian entre clientes y empleados

este el el link de nuestra pagina https://markblazquez.informaticailiberis.com/practica%20de%20grupo/vista/index.php
