## Diagrama de componentes.

![](https://github.com/federico1605/Software2/blob/main/Imagenes/Vista%20implementacion/DiagramaDeComponentes.png)

- Caracteristica: El diagrama de componentes representa cuales nos modela la vista estetica del sistema de Carpooling se deseo realizar porque con el entendemos como es la secuencia de pasos, quien se coneca con quien.

## Componentes:

- CarpoolingucoCrossCutting: Es el proyecto que se encarga de contener todos los utilitarios que a aplicación necesita para realizar funciones generales.

- CarpoolingucoApi: Es el proyecto que se encarga de contener los controlladores, los cuales se encargan de conectarse con el frontend y recibe la informacion por puertos.

- CarpoolingucoDTO: Es el proyecto que se encarga de guardar todos los objetos en un unico sitio con todos los atributos y constructores.

- CarpoolingucoEntity: Es el proyecto se encarga de representar representar la base datos es quien representa las tablas de la base de datos.

- CarpoolingucoRepository: Es el proyecto se encarga de conectar el backend con la base de datos, es por donde se manda y se reciben datos de la base de datos.

- CarpoolingucoService: Es el proyecto se encarga de hacer todas las funcionalidades, aplica reglas para que se cumplan las reglas de negocio.
