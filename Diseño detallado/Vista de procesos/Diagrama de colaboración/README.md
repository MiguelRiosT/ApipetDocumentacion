
## 1.2.4.2 Diagrama de colaboración

**Objetivo/motivación:**

 Representar de manera clara y concisa cómo los diferentes componentes del sistema interactúan entre sí para lograr un objetivo común.

 Ventajas:

 - Obtener una visión menos abstracta de las interacciones entre los componentes.

 - Mejor entendimiento del proyecto a nivel de equipo de desarrollo.

 - Sirve como documentación de como funcionan las interacciones. 


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


**Nombre:** Colaboración de una transacción de actualización

![Diagrama ](https://github.com/MiguelRiosT/ApipetDocumentacion/blob/main/Dise%C3%B1o%20detallado/Vista%20de%20procesos/Diagrama%20de%20colaboraci%C3%B3n/Colaboraci%C3%B3n%20de%20una%20transacci%C3%B3n%20de%20actualizaci%C3%B3n.drawio.png)


**Documentación elementos que lo conforman**

1. doAction(json):

    Una solicitud enviada por el FrontEnd al controller con el fin de realizar una acción en específico empleando los datos proporcionados en formato JSON.

2. doAction(dto): 

     Representa una solicitud enviada por el controller al facade para llevar a cabo una acción específica utilizando un objeto de transferencia de datos.

3. doAction(domain):

    Representa una solicitud enviada por el facade al service para llevar a cabo una acción específica utilizando un objeto del dominio (domain) como parámetro.

4. validateRule(domain):

     Se encarga de realizar la validación de una regla específica aplicada al objeto del dominio proporcionado

5. requestData(entity):
    
    Representa una solicitud enviada desde el service al repository para obtener datos relacionados con una entidad específica.

6. setData(entity):

    Representa una solicitud enviada desde el service al repository para guardar o actualizar los datos de una entidad específica.

7.1 commit():

Representa una solicitud enviada desde el facade al repository para confirmar y persistir los cambios realizados en las operaciones anteriores.

7.2 rollback():

Representa una solicitud enviada desde el facade al repository para deshacer los cambios realizados en las operaciones anteriores y restaurar el estado anterior.

<br>
<br>

**Nombre:** Colaboración de una transacción de consulta

![Diagrama ](https://github.com/MiguelRiosT/ApipetDocumentacion/blob/main/Dise%C3%B1o%20detallado/Vista%20de%20procesos/Diagrama%20de%20colaboraci%C3%B3n/Colaboraci%C3%B3n%20de%20una%20transacci%C3%B3n%20de%20consulta.drawio.png)


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