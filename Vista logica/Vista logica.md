## 1.2.2.1 Diagrama de clases
![Diagrama de clases](https://github.com/federico1605/Software2/blob/main/Imagenes/Diagrama-Clases/DiagramaDeClases.png)

- Este diagrama de clases se creo con la necesidad de explicar cuales son las clases, metodos y atributos que tiene el proyecto de CarpoolingUCO, se muestra todos los metodos que cada clase puede crear, la comunicacion que se tienen entre las clases y cual son las clases que heredan, las clases que dependen de otras.

**Cliente**

Objeto que representa a un tipo de usuario, el cual es quien solicita el servicio de carro compartido. Es quien contacta con un conductor para llegar a un destino en común.

**Conductor**

Usuario encargadode realizar las rutas, es quien crea y da los detalles de cuando y por donde pasa, para así poder transportar a otros usuarios. El conductor tiene un vehiculo el cual dispone para compartir y trasportar a  otros usuarios.

**Calificación**

Objeto que representa cual es la calificacion conforme al servicio que recibio por parte del usuario, esta calificacion es general, toma en cuenta la actitud del conductor principalmente.

**Vehiculo**

Objeto que se encarga de identificar al vehiculo del conductor y a su vez la persina que lo registro en la aplicación.

**Ruta**

Objeto que nos representa cuales son las rutas que se da en un viaje, como la puede hacer, por donde pasa, quienes estuvieron en el viaje y hasta donde llegaron, se busca es guardar datos por seguridad de los usuarios.

**Solicitud ruta**

Objeto con el cual un cliente puede hacer una solicitud para guardar el cupo en una reuta especifica, con la cual un conductor puede ver cuales clientes acepta o no para compartir su ruta.

**Conductor vehiculo**

Objeto que tiene la funcion de especificar quien es el conductor de que vehiculo, facilitando a los clientes para tomar la decisión de que ruta y vehiculo usar.

**Categoria autorizada**

Objeto que tiene la funcion de especificar las categorias de licencias de conduccion que se pueden usar en la aplicación.

**Recorrido Ruta**

Objeto el cual guarda la posición de un conductor al momento de realizar una ruta, de forma que se guarda en tiempo real de cuales son las posicinoes del conductor buscando brindar mayor información a un pasajero.

**Mensaje**

Objeto que representa los mensajes que crea un usuario en el grupo chat de una ruta.

**Grupo chat Ruta**

Objeto que representa el chat que se genera al momento de crear una ruta y contiene los participantes de la ruta.

**Punto interes**

Objeto que tiene la funcion de especificar los diferentes puntos de interes que pueden haber en una ciudad.

**Ciudad**

Objeto que tiene la funcion de especificar que ciudades estan registradas en la apliacion.

**Departamento**

Objeto que tiene la funcion de especificar los departamentos que se registraron con sus respectivas ciudades.

**País**

Objeto que tiene la funcion de especificar los diferentes paises registrados en la aplicación.

![Diagrama entidad relación](https://github.com/federico1605/Software2/blob/main/Imagenes/Diagrama-Clases/MER.png)

- Las entidades son las mismas y mantiene la misma descripción.
- La motivación de hacer un MER es mostrar como es la estructura de la base de datos del proyecto, para poder analizar, mejorar y entender cuales son las relaciones, como se estructura la base de datos del proyecto Carpooling

[Volver](https://github.com/federico1605/Software2/blob/main/Carpooling-agenda.md)