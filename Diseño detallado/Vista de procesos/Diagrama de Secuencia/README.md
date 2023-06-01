
## 1.2.4.1 Diagrama de secuencia

**Objetivo/motivación:**

El objetivo principal de un diagrama de secuencia es visualizar y describir la secuencia de interacciones entre los objetos y componentes del sistema durante la ejecución de un escenario o una transacción específica.

Ventajas:

- Ánalisis del flujo de ejecución:  

    Comprendiendo cómo se lleva a cabo una transacción o escenario en particular, identificando las interacciones entre los objetos y el orden en el que ocurren.

- Identificación de problemas

- Depuración y pruebas

- Sirve como documentación

**Elementos que comparten ambos diagramas**

- FrontEnd: 

    Es responsable de la interfaz de usuario, la interacción con el usuario y la presentación de los datos.

- Controller: 

    Es una parte del patrón de diseño Modelo-Vista-Controlador (MVC). Se encarga de recibir las solicitudes del usuario, procesarlas y coordinar las acciones apropiadas, como invocar los servicios y gestionar los datos necesarios para responder a la solicitud.

- Facade:

     Proporciona una interfaz simplificada para un conjunto de interfaces más complejas o subsistemas. Actúa como una capa intermedia entre los clientes y los componentes internos del sistema, proporcionando una interfaz única y unificada.

- Service:

    Capa lógica o componente que contiene la lógica de negocio de una aplicación. Proporciona servicios y funcionalidades específicas para cumplir con los requisitos del sistema.

- Repository:

    Responsable de la persistencia y el acceso a los datos. Proporciona una interfaz para interactuar con la capa de almacenamiento de datos, como una base de datos, ocultando los detalles de implementación y proporcionando métodos para recuperar y almacenar datos.



**Nombre:** Secuencia de una transacción de actualización

![Diagrama ](https://github.com/MiguelRiosT/ApipetDocumentacion/blob/main/Dise%C3%B1o%20detallado/Vista%20de%20procesos/Diagrama%20de%20Secuencia/Secuencia%20de%20una%20transacci%C3%B3n%20de%20actualizaci%C3%B3n.drawio.png)


**Documentación elementos que lo conforman**



<br>
<br>

**Nombre:** Secuencia de una transacción de consulta

![Diagrama ](https://github.com/MiguelRiosT/ApipetDocumentacion/blob/main/Dise%C3%B1o%20detallado/Vista%20de%20procesos/Diagrama%20de%20Secuencia/Secuencia%20de%20una%20transacci%C3%B3n%20de%20consulta.drawio.png)


**Documentación elementos que lo conforman**


1. getData(json):

    En esta interacción, el FrontEnd envía una solicitud al Controller para obtener datos mediante el envío de un objeto JSON como parámetro.

2. getData(dto):

    Representa una llamada que se realiza desde el Controller al Facade, con el propósito de obtener datos utilizando un objeto DTO (Data Transfer Object) como parámetro.

3. getData(domain):

    Representa una llamada que se realiza desde el Facade al Service con el objetivo de obtener datos utilizando un objeto de dominio (domain) como parámetro.

4. getData(entity):

    Llamada que se realiza desde el Service hacia el Repository con el objetivo de obtener datos utilizando un objeto de entidad (entity) como parámetro.
    
5. return List< entity > :

    Devolución de una lista de objetos de entidad (entity) desde el Repository al Service.

6. return List< domain > :

    Devolución de una lista de objetos de dominio desde el Service al Facade.

7. return List< dto > :

    Representa la devolución de una lista de objetos DTO (Data Transfer Object) desde el Facade al Controller.

8. return List< json > :

    Representa la devolución de una lista de objetos JSON desde el Controller al FrontEnd. En esta interacción, el Controller ha procesado la lógica de control y ha obtenido una lista de objetos JSON como resultado.


