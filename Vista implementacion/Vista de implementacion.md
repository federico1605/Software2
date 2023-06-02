## 1.2.2.3. Diagrama de paquetes:
![](https://github.com/federico1605/Software2/blob/main/Imagenes/Vista%20implementacion/Diagrama%20de%20paquetes.png)

- Este diagrama representa la estructura general del proyecto CarpoolingUCO, representa cuales paquetes se conecta con otros, como es la direccion de llamados y cuales son todos los paquetes que hay dentro del proyecto.
- La motivación y objetivo de este diagrama es poder mostrar a las personas que participaran en el proyecto cual es la estrucura de las carpetas que compone el proyecto, como son las relaciones que componen el backend del proyecto.

- repository:

Este paquete contiene las clases las cuales son encargadas de comunicarse con la base de datos que se usa para la aplicacion.

dto:

En este paquete se presenta las clases que se transfieren los datos de todos los objetos necesarios para la aplicación en las diferentes paquetes de la aplicacion.

entity:

Este paquete contiene todas las representaciones de la base de datos en tablas, en esta clase es donde se comunica con el repository y es la encargada de mantener la estructura de la aplicación.

service:

Este paquete es donde se presentan todas las clases, interfaces que se encargan de aplicar las funcionalidades y las reglas de negocios que se deben aplicar para el correcto funcionamiento de la aplicación.

api:

Este paquete contiene todos los controaldores, el init que es el ejecutable de la aplicacion, es donde se contiene la comunicación con las diferentes apis o con el frontend, es quien accede alos recursos necesarios para ejecutar las acciones que les piden por parte de la comunicacion de api.

crosscutting:

En este paquete esta encargado de contener funcionalidades y utilidades basicas y repiten a lo largo de la aplicación.

[Volver](https://github.com/federico1605/Software2/blob/main/Carpooling-agenda.md)
