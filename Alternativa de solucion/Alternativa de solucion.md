## Arquitectura de referencia

![](https://github.com/federico1605/Software2/blob/main/Imagenes/Alternativa%20de%20solucion/Arquitectura%20de%20referencia.png)

-  Esta es la arquitectura la cual se propueso de referencia con la cual se va a contruir las bases para el proyecto CarpoolingUCO, la cual se orienta a una arquitectura en una plataforma web, la cual consta de todos los artefactos de seguridad y direccion logica la cual tomaria la aplicación.

## Arquetipo de solución
![](https://github.com/federico1605/Software2/blob/main/Imagenes/Alternativa%20de%20solucion/ArquetipoSolucion.png)

- El arquetipo que se planteo para solucionar las restricciones de la aplicación fue mantener la arquiterctura de referencia, pero añadiendo las tecnologias que van a solucionar las restricciones, como lo puede ser el uso de:
- ### AWS WAF:
    - El servicio de AWS WAF es uno de los servicios más utilizado al momento de hacer uso de un servicio waf, el servicio de aws no permite filtrar cuialquier tipo de peticion o intento de ingreso por parte de bots y como funciones adicionales, tambien tiene la capacidad de funcionar como balanceador de cargas mejorando el rendimiento de la aplicación.
    - La version a utilizar será AWS WAF 2.
- ### Angular:
    - Por parte del front end se utilizara del framework angular, el cual provee unas herramientas de que facilitaran y agilizaran el uso de la aplicación web.
    - La versión de angular será Angular 15
- ### Java:
    - Para realizar el desarrollo del backend y el web socket se utilizara el framework de java Spring boot, el cual es un servicio que es una tecnologia muy usada, la cual provee librerias y funcionalidades las cuales facilitaran, agilizaran y mejoraran el desarrollo de la aplicación web.
    - La versión de java sera java 20 
    - La versión de spring boot será 3.0.6
- ### Docker:
    - Se hara de uso del servicio Docker para realizar un despliegue continuo, facilitar la escalabilidad y la eficiencia en el uso de los recursos, se desea usar docker por las herramientas que este provee, la facilidad y fiabilidad al momento de implementarlo a una aplicación.
    - La versión a usar será 1.26.0
- ### Postgresql:
    - Se hara uso de una base de datos relacional la cual será postgresql la cual provee una fiabilidad en los datos, es muy eficiente al momento de realizar consultas.
    - La versión para usar en la versión 14.
- ### Auth0:
    - Se utilizara como servicio de seguridad Auth0, la cual es una herramienta muy usada, facil se instalar y adaptable a muchos tipos de aplicaciones, la cual provee un servicio web con el cual se facilita el uso y la forma de dar autorizaciones a los diferentes dipos de usuarios y provee servicios para poder aunteticar a usarios con diferentes plataformas, como lo son google, github o microsoft.
    - La version a usar será 3.4.0
- ### SendGrid:
    -Es el servicio que se va usar para generar mensajeria dentro y fuera de la aplicación, es un servicio de mensajeria, la cual es facil de integrar, permite multilenguaje, es muy eficiente en el uso de los recursos.
    - La version a utilizar será 4.9.2
## Plataforma Tecnológica:
- ### Front End:
- Se desea utilizar el framework de codigo abierto Angular, la cual es una herramienta que pemite manejar la capa visual de una aplicación web, Angular brinda un entorno de trabajo estructurado, lo cual facilitara la mantenibilidad del codigo, provee funcioalidades que agilizan el desarrollo de la aplicación y tambien es muy eficiente para el uso de los usuarios, permite crear paginas web reactivas las cuales mejoran el uso del aplicativo.

- Angular funcinoa con HTML, CSS y TypeScript.

- ### Back End:
- Toda la logica del proyecto se realizara en el lenguaje de programación Java haciendo uso del frame work Spring boot, la cual optimiza, mejora y provee herramientas las cuales agilizan el desarrollo de la aplicacion, como el uso por parte de los usuario e incorporando técnicas de código limpio las cuales permiten la mejora en la estructura y velocidad de la aplicación.

- ### Fuente de datos:
- Se utilizara una base de datos relacional se decidio utilizar este servicio como fuentes de datos, para garantizar la integridad de los datos, evitando la duplicidad de los datos que se creen, los cuales ayudaran al momento de de hacer uso del aplicatiovo.

- ### Provedor de identidades:
- Se desea utilizar un servicio de autenticación de usuarios, para garantizar la seguridad y la identidad de los usuarios, para poder garantizar esto, se penso en usar Auth0, el cual proporciona todas las herramientas, las cuales ayudaran a garantizar las credenciales de los usuarios.

[Volver](https://github.com/federico1605/Software2/blob/main/Carpooling-agenda.md)
