 #  Modelo de Componentes #


![Modelo de componentes](https://github.com/MiguelRiosT/ApipetDocumentacion/blob/main/Modelo%20de%20Componentes/ModeloComponentesApipet.drawio.png)

 ## _Documentación_ ##

### Significado de color de los componentes: ###

**Azul**: Componentes externos de la aplicación

**Componente externo:** Hace referencia a un elemento o parte de la aplicación que no es desarrollado propiamente por el equipo de trabajo, este mismo se adquiere de fuentes externas.

Por lo tanto, un componente externo es aquel que se integra en el aplicativo pero no se desarrolla internamente.


**Amarillo**: Componentes propios de la aplicación Apipet.

**Componente propio del aplicativo:** Hace referencia a los elementos o partes de la aplicación que son desarrollados propiamente e internamente por el equipo de trabajo del aplicativo.

### Componentes definidos ###

### Java project: ### 

- **ApipetDTO:** Componente que ofrece los objetos de transferencia de datos para poder intercambiar información entre el componente de API y el componente Service.

- **ApipetCrossCutting:** Componente que ofrece características aspectuales que pueden ser utilizadas de forma general por cualquier componente de la aplicación Apipet.

- **ApipetEntity:** Componente que tiene todas las entidades de acceso a datos que serán utilizadas por el componente de repositorio para llevar a cabo las operaciones de acceso a datos.

- **ApipetRepository:** Componente que ofrece los mecanismos de acceso a datos para el proyecto Apipet.

- **ApipetService:** Componente encargado de garantizar el cumplimiento de toda la lógica de negocio de la aplicación, asegurando que el dominio esté protegido de accesos no autorizados en la aplicación Apipet.


### Spring Boot: ###

- **ApipetApi:** Componente encargado de publicar Apis relacionados con los servicios de negocio ofrecidos por la aplicación Apipet. 


### Componentes y su respectivo color ###

- **Azul**(Componentes externos)
  - SpringBoot 3.0.6
  - Java 20
  
- **Amarillo**(Componentes propios del aplicativo)

  - ApipetDTO
  - ApipetCrossCutting
  - ApipetEntity
  - ApipetRepository
  - ApipetService
  - ApipetApi

