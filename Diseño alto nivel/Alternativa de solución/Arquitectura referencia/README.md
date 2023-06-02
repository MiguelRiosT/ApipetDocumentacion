#  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🐶Software 2 - Apipet 🐱  #


## 1.1.3.2. Arquitectura referencia


1.1.3.2.1. Diagrama 

![Diagrama arquitectura referencia](https://github.com/MiguelRiosT/ApipetDocumentacion/blob/main/Dise%C3%B1o%20alto%20nivel/Alternativa%20de%20soluci%C3%B3n/Arquitectura%20referencia/ArquitecturaReferencia.png)


**Objetivo/motivación:**

Para el proyecto es de suma importancia tener este diagrama al ser una base conceptual sólida, con la cuál se puede observar los componentes que se están desarrollando para brindar un resultado aceptado.

Motiva mucho en el aspecto de ver cómo en el proyecto se requieren ciertos componentes para funcionar correctamente y cómo estos se relacionan o dependen unos de otros.


<br>

1.1.3.2.2. **Documentación elementos que lo conforman**

- FrontEnd: Se encarga de mostrar la interfaz al usuario y enviar y recibir datos al BackEnd. 

- BackEnd: Se encarga del procesamiento de los datos y la lógica de negocio.

- Base de datos: Es donde se almacenan y gestionan los datos del aplicativo de manera estructurada.

- Servicio de notificaciones: Utilizado para enviar notificaciones por correo electrónico o mensajes de texto a los usuarios del aplicativo. 

- Identity provider: Se encarga de gestionar la autenticación y autorización de los usuarios en el aplicativo.

- WAF (Web Application Firewall): Es un componente de seguridad. Su función principal es proteger el aplicativo contra ataques web comunes, como inyecciones SQL, ataques de denegación de servicio (DDoS), cross-site scripting (XSS), entre otros.

- API Gateway: Actúa como un punto de entrada centralizado para todas las solicitudes de API del aplicativo.

- CDN (Content Delivery Network): Es una red de servidores distribuidos geográficamente que almacena en caché el contenido estático del aplicativo, como imágenes, archivos CSS y JavaScript.

- Container Management: Gestión de contenedores, que son entornos virtualizados y ligeros que encapsulan aplicaciones y sus dependencias para garantizar la portabilidad y escalabilidad

- SPA (Single-Page Application): Aplicativo web en el que la interacción con el usuario ocurre en una sola página, sin recargar la página completa.

