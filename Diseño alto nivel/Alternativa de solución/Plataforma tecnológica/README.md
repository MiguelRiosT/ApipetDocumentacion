#  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🐶Software 2 - Apipet 🐱  #


## 1.1.3.4. Plataforma tecnológica


1.1.3.4.1  **FrontEnd** 


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![imagen angular](https://github.com/MiguelRiosT/ApipetDocumentacion/blob/main/Dise%C3%B1o%20alto%20nivel/Alternativa%20de%20soluci%C3%B3n/Plataforma%20tecnol%C3%B3gica/AngularLogo.png)

Angular es un framework de desarrollo web de código abierto y basado en JavaScript, creado por Google. Permite construir aplicaciones web de una sola página (SPA) de manera eficiente y escalable. Angular utiliza un enfoque basado en componentes para la construcción de aplicaciones, donde cada componente encapsula la lógica y la presentación de una parte específica de la interfaz de usuario. Además, Angular ofrece características como enlace de datos bidireccional, inyección de dependencias y manejo de eventos, lo que facilita el desarrollo de aplicaciones web interactivas y dinámicas.

¿Por qué Angular?

- Para el aplicativo se escoge angular principalmente porque el equipo de trabajo ya había escuchando y manejado a nivel básico este framework, lo cuál permite que se desarrolle y exista un mejor progreso.

- A diferencia de opcines como React o Vue.js, que también son frameworks, no se tiene tanta cercanía a estos mismos por lo cuál no se tomaron en cuenta.

- Angular puede brindar hasta cierto punto la implementación de un api para mapas de manera que se pueda trabajar mejor.

**Version:** Para el proyecto se esta usando la versión de Angular 16

<br>

1.1.3.4.2  **BackEnd**


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![imagen springboot](https://github.com/MiguelRiosT/ApipetDocumentacion/blob/main/Dise%C3%B1o%20alto%20nivel/Alternativa%20de%20soluci%C3%B3n/Plataforma%20tecnol%C3%B3gica/SpringBootLogo.png)

Spring Boot es un framework de desarrollo de aplicaciones basado en Java que facilita la creación de aplicaciones web y servicios REST de manera rápida y sencilla. Proporciona un enfoque simplificado para la configuración y el desarrollo, eliminando gran parte de la complejidad asociada con la configuración manual de una aplicación Spring tradicional.

¿Por qué SpringBoot?

- Es un framework para BackEnd el cuál ha sido el único que ha trabajado el equipo de desarrollo por lo que existe cierta familiaridad con este.

- El entorno de desarrollo empleado el cuál es Eclipse se adapta fácilmente a este framework lo que permite progresar sin muchos contratiempos en el desarrollo.

- Springboot principalmente maneja como lenguaje Java, el equipo de desarrollo tiene conocimiento y acermcamiento con este lenguaje por lo que es un motivo de peso para emplear SpringBoot.

**Version:** Se usa SpringBoot 3.0.6 o en su defecto la última versión más estable.

<br>

1.1.3.4.3  **Base de datos**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![imagen PostgreSQL](https://github.com/MiguelRiosT/ApipetDocumentacion/blob/main/Dise%C3%B1o%20alto%20nivel/Alternativa%20de%20soluci%C3%B3n/Plataforma%20tecnol%C3%B3gica/PostgreSQLLogo.png)

PostgreSQL es un sistema de gestión de bases de datos relacional de código abierto y altamente escalable. Es conocido por su confiabilidad, flexibilidad y capacidad para manejar grandes volúmenes de datos y cargas de trabajo intensivas. PostgreSQL es compatible con múltiples plataformas, lo que permite su ejecución en diversos sistemas operativos.

¿Por qué PostgreSQL?

- Para el aplicativo es requerido emplear bases de datos relacionales, el equipo de trabajo solo ha tenido acercamiento a MongoDB y PostgreSQL por lo que se empleará PostgreSQL en este caso.

- El uso de una interfaz gráfica de usuario para PostgreSQL como lo es pgAdmin es de una gran utilidad por su accesible nivel técnico y su capacidad para ayudar al equipo de desarrollo a interactuar con la base de datos.

**Version:** Usar en su defecto la última versión más estable.


<br>

1.1.3.4.4  **Notificaciones** 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![imagen SendGrid](https://github.com/MiguelRiosT/ApipetDocumentacion/blob/main/Dise%C3%B1o%20alto%20nivel/Alternativa%20de%20soluci%C3%B3n/Plataforma%20tecnol%C3%B3gica/SendGridLogo.png)

SendGrid es un servicio en la nube que facilita el envío de correos electrónicos a gran escala de manera confiable y segura. Proporciona una infraestructura robusta y escalable para el envío y la entrega de correos electrónicos transaccionales y de marketing.

¿Por qué SendGrid?

- Principalmente por su característica de fácil integración a los diversos tipos de proyectos en los que se requiera.

- Su "Free Trial" permite a los usuarios probar y utilizar el servicio de envío de correos electrónicos de forma limitada y gratuita durante un período de tiempo determinado. Esto para motivos de aprendizaje y implementación en el equipo de trabajo es un punto ganador.

**Version:** Usar en su defecto la última versión más estable.


<br>

1.1.3.4.5  **Proveedor de identidades**: Auth0 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![imagen Auth0](https://github.com/MiguelRiosT/ApipetDocumentacion/blob/main/Dise%C3%B1o%20alto%20nivel/Alternativa%20de%20soluci%C3%B3n/Plataforma%20tecnol%C3%B3gica/Auth0Logo.png)

Auth0 es un servicio de gestión de identidad y acceso (IAM) que proporciona soluciones de autenticación y autorización para aplicaciones y servicios web. Su objetivo es simplificar y asegurar el proceso de autenticación de usuarios, permitiendo a los desarrolladores agregar fácilmente funcionalidades de inicio de sesión y seguridad a sus aplicaciones.

¿Por qué Auth0?

- El equipo de desarrollo considera que para el aplicativo es parte importante para la seguridad de los usuarios como tal.

- Para el equipo de desarrollo se presenta como un reto técnico implementar Auth0 a su aplicativo pero será de mucho valor de aprendizaje el afrontar esta implementación.

**Version:** Usar en su defecto la última versión más estable.

<br>

1.1.3.4.6  **Administrador de claves**: KeyVault 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![imagen KeyVault](https://github.com/MiguelRiosT/ApipetDocumentacion/blob/main/Dise%C3%B1o%20alto%20nivel/Alternativa%20de%20soluci%C3%B3n/Plataforma%20tecnol%C3%B3gica/KeyVaultLogo.png)

 Su objetivo principal es ayudar a las aplicaciones a gestionar y proteger de forma segura sus claves de cifrado, secretos y certificados.

¿Por qué KeyVault?

- En complemento con Auth0 presenta una mejora significativa a la segurida de los usuarios.

- Para el equipo de desarrollo se presenta como una opción muy importante a tener en cuenta.

**Version:** Usar en su defecto la última versión más estable.

<br>

### Stack tecnológico resultante:

FrontEnd: Angular 

BackEnd: SpringBoot

Base de datos: PostgreSQL

Notificaciones: SendGrid

Proveedor de identidades: Auth0

Administrador de claves: KeyVault

WAF:

CDN:

API GATEWAY: 


