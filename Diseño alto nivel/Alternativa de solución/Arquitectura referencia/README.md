#  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🐶Software 2 - Apipet 🐱  #


## 1.1.3.2. Arquitectura referencia


1.1.3.2.1. Diagrama arquitectura referencia

![Diagrama arquitectura referencia](https://github.com/MiguelRiosT/ApipetDocumentacion/blob/main/Dise%C3%B1o%20alto%20nivel/Alternativa%20de%20soluci%C3%B3n/Arquitectura%20referencia/ArquitecturaReferencia.png)

1.1.3.2.2. Explicación diagrama de aquitectura referencia

- FrontEnd: Se encarga de mostrar la interfaz al usuario y enviar y recibir datos al BackEnd. Angular es un framework de desarrollo web que permite crear interfaces de usuario dinámicas y robustas.

- BackEnd: Se encarga del procesamiento de los datos y la lógica de negocio. SpringBoot es un framework de Java que facilita la creación de aplicaciones web y servicios. 

- Base de datos: Es donde se almacenan y gestionan los datos del aplicativo de manera estructurada. PostgreSQL  Permite almacenar, recuperar, modificar y eliminar datos de forma eficiente.

- Servicio de notificaciones: Utilizado para enviar notificaciones por correo electrónico o mensajes de texto a los usuarios del aplicativo. SenGrid es un servicio de envío de correos electrónico y mensajes de texto en tiempo real.

- Identity provider: Se encarga de gestionar la autenticación y autorización de los usuarios en el aplicativo. Con  Auth0 se asegura que solo los usuarios autorizados puedan acceder a los recursos y servicios del aplicativo.

POR DEFINIR CUÁL USAR:

- WAF (Web Application Firewall): Es un componente de seguridad. Su función principal es proteger el aplicativo contra ataques web comunes, como inyecciones SQL, ataques de denegación de servicio (DDoS), cross-site scripting (XSS), entre otros.

- API Gateway: Actúa como un punto de entrada centralizado para todas las solicitudes de API del aplicativo.

- CDN (Content Delivery Network): Es una red de servidores distribuidos geográficamente que almacena en caché el contenido estático del aplicativo, como imágenes, archivos CSS y JavaScript.

- Container Management: Gestión de contenedores, que son entornos virtualizados y ligeros que encapsulan aplicaciones y sus dependencias para garantizar la portabilidad y escalabilidad

- SPA (Single-Page Application): Aplicativo web en el que la interacción con el usuario ocurre en una sola página, sin recargar la página completa.


Conexión entre componentes de la arquitectura:

FrontEnd se encarga de mostrar la interfaz al usuario y enviar y recibir datos al BackEnd. El BackEnd procesa las solicitudes del FrontEnd, interactúa con la base de datos para almacenar y recuperar datos, utiliza el servicio de notificaciones para enviar notificaciones a los usuarios y se integra con el proveedor de identidad para gestionar la autenticación y autorización de los usuarios. Todos estos componentes trabajan en conjunto para brindar un aplicativo funcional y seguro.