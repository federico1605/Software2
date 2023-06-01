## Diagrama de secuencias.

![Crear una ruta](https://github.com/federico1605/Software2/blob/main/Imagenes/Vista%20de%20procesos/Diagrama-Secuencia-Crear-Ruta.png)

- Caracteristicas: El diagrama de secuencia representa la linea de tiempo de la creación de una ruta por parte del back end, de forma que explica cual es el proceso que se genera internamente al momento de querer ingresar una ruta, cada capa las cuales son el frontennd, que es la interfaz grafica que los usuarios ven, la capa de controller la cual es quien revise los datos que vienen por parte del usuario, la capa de facade, la cual es la puerta que entrega o recibe y es una capa por la cual pasan todos los datos que fluyen en la aplicación, la capa de service es donde se validan las reglas de negocio, y se realiza la acción que un usario desea ya la capa de repository es la capa que se comunica con la base de datos de la aplicación.
