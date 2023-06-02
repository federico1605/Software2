# Modelado de dominio

- Motivacion/Objetivo: 
La motivación del modelado de dominio es representar los objetos, las comunicaciones que se presenta en la estructuracón a nivel de usuarios, lo que quiere decir que explica como se comunica los usuarios con los demas objetos que se presentan en la aplicaion, la motivacion es entender de forma más astracta y aalto nivel como se explica el comportamiento que se logra en la aplicación, objetivo es mostrar como es la interaccion entre los diferentes objetos que hay en el proyecto

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

**Estado**

Objeto que representa una etapa de estado generica para toda la aplicación de forma que representa los diferentes estados logicos en los cuales se puede presentar la aplicación

**Usuario**

Objeto que representa todas las personas que usan la aplicación de forma generica todas las personas que se registran en la aplicacion CarpoolingUCO

[Simulación de datos](https://docs.google.com/spreadsheets/d/1lQjOUfYR4ABYBbSv31pHxSKP-IOI-TKa/edit#gid=714655728)

**Modelo de dominio**

![Modelo de dominio](/Imagenes/Modelo-Dominio/ModeloDominio.png)


**Modelado de de dominio enriquesido**

![Modelo de dominio](/Imagenes/Modelo-Dominio/ModeloDominioEnriquesido.png)

[Volver](https://github.com/federico1605/Software2/blob/main/Carpooling-agenda.md)
