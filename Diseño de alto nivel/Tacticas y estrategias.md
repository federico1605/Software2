## Seguridad:

- Tactica: Se requiere que la aplicación que la aplicación presente un sistema de seguridad fiable, que provea servicios de login seguros, que presente incriptación de datos.

- Estrategia:

- Proteccion contra acceso no autorizados: Para garantizar el correcto login a la aplicación se decidio usar Auth0, la cual provee servicios de autorización y atenticación.

- Seguridad de los datos: Para garantizar la seguridad de los datos de los usuarios enviar todas las peticiones web en formato HTTPS, la cual incripta los datos que viajan en las diferentes peticiones.

- Auditoria y seguimiento: Para garantizar la seguridad y la correcta auditoria, se requiere implementar una arquitectura que permita el uso de telemetría, enfocado en un diseño que guarde por medio de logs las transacciones que se realizan en la aplicación.

- Practicas de codigo seguro: Para garantizar la correcta construcción de todos los requerimientos que tiene la aplicacion en seguridad se debe aplicar las correctas practicas de seguiridad.

## Disponibilidad:

- Tactica: Se requiere que la aplicación este disponible para el correcto uso de cada uno de los usuarios, que responda de forma correcta y que presente una disponibilidad mayor al 85% del año.

- Estrategia:

- Escalabilidad y carga del trabajo: Para garantizar la disponibilidad de la aplicación se require implementar servicios de balanceo de cargas con el cual se mejore el desgaste que no se presente solo en un servidor, para esto se puede usar el AWS WAF que no solo funciona como firewall sino que tambien como un balanceador de cargas el cual nos ayuda a balancear las cargas.

- Continuidad del negocio: Para garantizar la continuidad del negocio se puede implemetar una aplicacion orientada a la nube, nubes que puede ser Google clound o AWS, las cuales proveen servicios muy similares, aparte te garantizas tener las maquinas necesarias para poder procesar todas las transacciones que lleguen.

- Tolerancia a los fallos: Para garantizar que la aplicación se mantenga disponible se puede integrar una arquitectura que sea orientado a fallos, como lo es un sistema en paralelo el cual se levanta al mometo que el servidor principal falle, se puede tambien ingregar servicios que detecten en que momentos la aplicacion falla de forma que cuando se cae automaticamento lo intenta levantar.

## Fiabilidad:

- Tactica: Se requiere que la aplicación presente una alta fiabilidad, al momento de usarla darle esa fiabilidad a los usuarios, para garantizar la satisfacción del usuario.

- Estrategia:

- Experiencia de usuario: Para garantizar que la aplicación sea fiable para los usuarios se requiere que la aplicacion cuente con una buena experiencia de usuario la cual, eso se puede garantizar con unas buenas practicas de codificación, se garantiza con tolerancia a fallos, siendo una plataforma amigable con los usuarios, que tenga ayudas para las personas, mantenga una alta disponibilidad y presente una buena seguiridad, esto se logra con una buena arquitectura integral y la mejor para la solución.

- Auto escalabilidad: Para garantizar la auto escalabilidad se puede conseguir con una arquitectura auto escalable, la cual se presenta con una buena linea base y un buen diseño de alto nivel, tambien se puede garantizar con una arquitectura orientado a la nube, la cual te permite que el crecimiento y el decrecimiento que se necesite.

- Mantenimiento eficiente: Para garantizar el matenimiento eficiente, se base en buenas praticas de desarrollo, una buena arquitectura y linea base, con patrones de diseños bien aplicados sin llegar a caer en anti patrones.

[Volver](https://github.com/federico1605/Software2/blob/main/Carpooling-agenda.md)
