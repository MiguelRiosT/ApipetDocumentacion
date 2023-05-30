#  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🐶Software 2 - Apipet 🐱  #


## 1.1.2.1. Atributos de calidad

Para muchos de los items aquí presentes se tomó de base el siguiente documento: [MiniQAW](https://github.com/MiguelRiosT/ApipetDocumentacion/blob/main/Dise%C3%B1o%20alto%20nivel/Restricciones%20del%20dise%C3%B1o/Atributos%20de%20calidad/documentos/Mini-QAW.xlsx)

<br>

&nbsp;&nbsp;1.1.2.1. Atributos de calidad

Los atributos de calidad empleados fueron:

- Seguridad
- Escalabilidad
- Rendimiento
- Disponibilidad
- Flexibilidad
- Accesibilidad
- Internacionalización
- Interoperabilidad
- Usabilidad
- Capacidad para ser administrado
- Capacidad

<br>

&nbsp;&nbsp;1.1.2.1.1. Mapa de empatía

**Importancia**

El mapa de empatía nos ayuda a comprender desde loas atributos de calidad seleccionados, la importancia que cada actor le brinda a cada uno de ellos, esto con el fin de plasmar en el aplicativo aquellos aspectos que deben tener más prioridad.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![](https://github.com/MiguelRiosT/ApipetDocumentacion/blob/main/Dise%C3%B1o%20alto%20nivel/Restricciones%20del%20dise%C3%B1o/Atributos%20de%20calidad/imagenes/Mapa%20Empatia/MapaEmpatia.png)

Como podemos observar en el mapa de empatía los actores tienen diferentes preferencias hacia los atributos de calidad.

En el caso de los ***dueños*** se observa que se van más por atributos de calidad como lo son: Seguridad, Disponibilidad, interoperabilidad y usabilidad.

En el caso de los ***Administradores de sistema*** se van por atributos más técnicos como lo son: Escalabilidad, Capacidad para ser administrados y interoperabilidad.

<br>

&nbsp;&nbsp;1.1.2.1.2. Características


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.1.2.1.2.1 Seguridad

<br>

| Característica de seguridad |
|------------|
| El sistema debe enviar un correo electrónico al registrar un usuario donde autentifique su identidad     |
| El sistema debe autenticar el usuario para brimdarle acceso a las personas que quieran usar Apipet, para de esta manera llevar el control de los ingresosy el manejo de la aplicación.    |

<br>


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.1.2.1.2.2 Escalabilidad

<br>

| Característica de escalabilidad |
|------------|
| El sistema debe tener un crecimiento respecto a la cantidad de usuarios y mascotas que se hayan registrado en cuestión de base de datos    |

<br>


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.1.2.1.2.3 Disponibilidad

<br>

| Característica de disponibilidad |
|------------|
| El sistema debe enviar recordatorios a los usuarios de los cuidados que se hayan registrado, teniendo en cuenta la mascota a la cual va ligado el cuidado y también los tiempos que se considera pertinentes para realizar el cuidado de nuevo   |

<br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.1.2.1.2.4 Flexibilidad

<br>

| Característica de flexibilidad |
|------------|
| Permiteme escoger los días de antelación en la que quiere recibir un recordatorio especial antes de que ocurra una fecha, estos días los podré escoger entre 1,3 y 4 días antes |
| El sistema debe permitir registrar un cuidado para las mascotas que ya se encuentren registradas dentro de la aplicación |
| El sistema debe permitir que un usuario registre más de una mascota |

<br>


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.1.2.1.2.5 Accesibilidad

<br>

| Característica de accesibilidad |
|------------|
| El sistema debe permitir a los usuarios registrarse por medio de una cuenta de terceros como lo es google, facebook o twitter |
|El sistema debe mostrar las ubicaciones de los lugares de interés dentro del mapa |
| El aplicativo debe funcionar tanto en dispositivos móviles como en la web |
| El aplicativo debe ser responsivo con la pantalla del usuario |

<br>


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.1.2.1.2.6 Internacionalización

<br>

| Característica de internacionalización |
|------------|
| El aplicativo debe mostrarle información de interés al usuario dependiendo de la raza de la mascota que se haya ingresado |

<br>



&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.1.2.1.2.7 Usabilidad

<br>

| Característica de usabilidad |
|------------|
| La aplicación debe mostrarme de forma bonita la edad de mi mascota |
| La aplicación debe decirme si mi mascota esta obesa o desnutrida según el peso, altura y su raza |
| El sistema debe permitir a los usuarios registrar sus mascotas |
| El icono debe ser bonito |
| Recordarme mediante notificación frecuentemente frases tipo: "la mascota ve el mundo como tu se lo quieras hacer ver, JUEGA CON ELLA" |
| Cuando un usuario se esté registrando con un correo o cuenta ya existente, el sistema debe avisar que la cuenta ya se ha registrado |
| El sistema debe mostrar los cuidados básicos sugeridos dependiendo de la mascota que se haya registrado usando como criterio la especie |
| El sistema debe notificarme recurrentemente en caso de olvidar una fecha importante, con cada día de olvido deberá ser más intenso el recordatorio |
| El sistema debe permitir agregar la información de los lugares que se han registrado dentro del mapa interactivo, como la hora de apertura y cierre, servicios que ofrecén y una breve descripción del establecimiento |
| El mapa interactivo debe tener iconos alusivos a los lugares como las centros comerciales, veterinarias y centros de adopción para que resalte en el mapa |
| Si un usuario olvida su contraseña debe poder recuperarla por medio del correo electrónico que haya registrado dentro de Apipet |
| La aplicacion debe permitir visualizar el historial de higiene y salud |
| Un usuario puede poner una foto de su mascota en el momento del registro |
| La aplicación debe contener botones que guien al usuario dentro de las diferentes páginas, como mis mascotas, el mapa y los sitios de interés que se encuentran cerca del usuario |
| El sistema debe verificar que se hayan llenado los campos necesarios para poder agregar una mascota dentro de la aplicación, no se pueden dejar campos vacíos |
| El sistema debe permitir a los usuarios que agreguen los cuidados recientes que le han practicado a sus mascotas como por ejemplo el último baño con su fecha o la ultima desparacitación |
| El aplicativo debe permitirme escoger un avatar o subir una foto de perfil |
| La letra y el color de la aplicación debe seguir el branding que se ha entregado en los mockups |
| El aplicativo debe recordar la fecha de cumpleaños del dueño y añadirle una frase de cumpleaños |
| El sistema debe verificar que la fecha de los cuidados sea una fecha que no haya pasado hace más de 8 días para poder llevar un control acertado de las sugerencias de los cuidados que se deben tomar con la mascota |
| La aplicación debe estar en capacidad de mostrarme información de la raza de mi mascota, como su temperamento, historia, caracteristicas |
| El aplicativo en la pantalla principal debe decirme buenos días, tardes o noches dependiendo la hora del día al iniciar la app |
| Las tarjetas principales de la pantalal principal mis mascotas, cuidados básicos y mapa deben tener una descripción |
| El aplicativo debe recordar la fecha de cumpleaños de la mascota y añadirle una frase de cumpleaños |
| El aplicativo debe ser solo de perros y gatos |

<br>


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.1.2.1.2.8 Capacidad para ser administrado

<br>

| Característica de capacidad para ser administrado |
|------------|
| El sistema debe permitir resgistrar los lugares de interés como centros de adopción, centros comerciales y veterinarias para que luego los usuarios puedan encontrarlos y tenerlos en cuenta al momento de una visita |

<br>


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.1.2.1.2.2 Priorización


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Priorización**


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![](https://github.com/MiguelRiosT/ApipetDocumentacion/blob/main/Dise%C3%B1o%20alto%20nivel/Restricciones%20del%20dise%C3%B1o/Atributos%20de%20calidad/imagenes/Priorizaci%C3%B3n/Priorizacion.png)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
**Votación**


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![](https://github.com/MiguelRiosT/ApipetDocumentacion/blob/main/Dise%C3%B1o%20alto%20nivel/Restricciones%20del%20dise%C3%B1o/Atributos%20de%20calidad/imagenes/Priorizaci%C3%B3n/votacion.png)


<br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.1.2.1.3. Escenarios de calidad


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.1.2.1.3.1. Seguridad

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
**Escenario Seguridad 1**

|  |  |
|-----------|-----------|
|   **Escenario**        | El sistema debe implementar un proceso seguro y confiable de autenticación de usuarios, a fin de garantizar que solo aquellos que han sido autorizados puedan acceder a la aplicación Apipet y realizar acciones en ella. Esto permitirá llevar un registro completo de los ingresos y del uso que se hace de la aplicación, asegurando así una gestión adecuada y transparente de la misma.          |
|   **Atributo**        |   Seguridad        |
|     **Característica**      |   El sistema debe autenticar el usuario para brindarle acceso a las personas que quieran usar Apipet, para de esta manera llevar el control de los ingresos y el manejo de la aplicación.		        |



|  **Fuente Estímulo**   | **Estímulo**     | **Ambiente**     | **Artefacto**     | **Respuesta**     | **Medida Respuesta**    |
|-----------|-----------|-----------|-----------|-----------|-----------|
| Administrador del sistema          |  Ingresar a la aplicación         |   Normal        |    Modulo de autenticación       |   Cuando se ingrese en el sistema de información se deben mostrar en pantalla las opciones correctas para el admin dashboard        |   Se pueden hacer uso sólo de las acciones correspondientes a un administrador del sistema        |

<br>

<br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Escenario Seguridad 2**

|  |  |
|-----------|-----------|
|   **Escenario**        | El sistema debe implementar un proceso seguro y confiable de autenticación de usuarios, a fin de garantizar que solo aquellos que han sido autorizados puedan acceder a la aplicación Apipet y realizar acciones en ella. Esto permitirá llevar un registro completo de los ingresos y del uso que se hace de la aplicación, asegurando así una gestión adecuada y transparente de la misma.         |
|   **Atributo**        |   Seguridad        |
|     **Característica**      |   El sistema debe autenticar el usuario para brindarle acceso a las personas que quieran usar Apipet, para de esta manera llevar el control de los ingresos y el manejo de la aplicación		        |



|  **Fuente Estímulo**   | **Estímulo**     | **Ambiente**     | **Artefacto**     | **Respuesta**     | **Medida Respuesta**    |
|-----------|-----------|-----------|-----------|-----------|-----------|
| Usuario ( Dueño )          |  Ingresar a la aplicación         |   Normal        |    Modulo de autenticación       |   Cuando se ingrese en el sistema de información se deben mostrar en pantalla las opciones de owner dashboard, el manejo de sus mascotas, el mapa interactivo y los cuidados pertinentes para la mascota        |   Se pueden hacer uso sólo de las acciones correspondientes a un usuario        |

<br>

<br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Escenario Seguridad 3**

|  |  |
|-----------|-----------|
|   **Escenario**        | El sistema debe enviar un correo electrónico de bienvenida al usuario después de que se haya registrado en la aplicación, con un enlace para confirmar y autenticar su identidad. El enlace enviado en el correo electrónico debe llevar al usuario a una página de confirmación en la que se le solicite que ingrese información adicional, como su dirección de correo electrónico y su contraseña. Esto permitirá al sistema verificar la identidad del usuario y garantizar que solo los usuarios autorizados tengan acceso a la aplicación. Además, la página de confirmación debe ser fácil de usar y proporcionar una experiencia de usuario intuitiva, para asegurar que el proceso de autenticación sea rápido y sencillo para el usuario.         |
|   **Atributo**        |   Seguridad        |
|     **Característica**      |   El sistema debe enviar un correo electronico al registrar un usuario donde autentifique su identidad 	        |



|  **Fuente Estímulo**   | **Estímulo**     | **Ambiente**     | **Artefacto**     | **Respuesta**     | **Medida Respuesta**    |
|-----------|-----------|-----------|-----------|-----------|-----------|
| Administrador del sistema          |  Se envia correo electronico de autentificación al usuario para validar su identidad        |   Normal        |    Modulo de autenticación       |   El sistema debe enviarle al usuario una url donde valide el token de acceso       |  Le llega al usuario el correo |

<br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.1.2.1.3.2. Accesibilidad


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Escenario Accesibilidad 1**

|  |  |
|-----------|-----------|
|   **Escenario**        | El sistema debe contar con una funcionalidad de visualización de mapas, en la que se muestren las ubicaciones de los lugares de interés relevantes para los usuarios, como clínicas veterinarias, tiendas de mascotas, parques para perros, entre otros. Estas ubicaciones deben ser fácilmente identificables y accesibles a través del mapa, lo que permitirá a los usuarios encontrar rápidamente los servicios que necesiten para sus mascotas. Además, la funcionalidad de mapa debe ser interactiva, permitiendo a los usuarios ver las calles y avenidas, buscar direcciones específicas y obtener indicaciones precisas para llegar a los lugares de interés.         |
|   **Atributo**        |   Accesibilidad        |
|     **Característica**      |   El sistema debe mostrar las ubicaciones de los lugares de interés dentro del mapa		        |


|  **Fuente Estímulo**   | **Estímulo**     | **Ambiente**     | **Artefacto**     | **Respuesta**     | **Medida Respuesta**    |
|-----------|-----------|-----------|-----------|-----------|-----------|
| Sistema         |  Mostrar las ubicaciones dentro del mapa interactivo         |   Normal        |    Modulo del mapa       |   El sistema debe mostrar a los usuarios un mapa interactivo con los lugares de interés que se encuentren cerca de la persona en el momento de la apertura      |   Cuando se abra el mapa interactivo se deben mostrar todos los lugares de interés que se hayan registrado cerca de la ubicación del usuario       |

<br>

<br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Escenario Accesibilidad 2**

|  |  |
|-----------|-----------|
|   **Escenario**        | El sistema debe permitir a los usuarios registrarse en la aplicación utilizando sus cuentas de redes sociales, como Google, Facebook o Twitter. Esto facilitará el proceso de registro y eliminara la necesidad de que los usuarios tengan que proporcionar información adicional, ya que la aplicación podrá obtener la información relevante de sus perfiles de redes sociales. Además, la integración con estas plataformas de terceros mejorará la experiencia del usuario y aumentará la confianza en la seguridad de la aplicación, ya que los usuarios estarán utilizando cuentas que ya han sido verificadas y autenticadas por estas plataformas. Sin embargo, es importante tener en cuenta las políticas de privacidad y seguridad de estas plataformas y asegurarse de cumplir con todas las regulaciones y estándares de seguridad para proteger los datos de los usuarios.         |
|   **Atributo**        |   Accesibilidad        |
|     **Característica**      |   El sistema debe permitir a los usuarios registrarse por medio de una cuenta de terceros como lo es Google, Facebook ó twitter	        |


|  **Fuente Estímulo**   | **Estímulo**     | **Ambiente**     | **Artefacto**     | **Respuesta**     | **Medida Respuesta**    |
|-----------|-----------|-----------|-----------|-----------|-----------|
| Dueño         |  Ingresar por medio de cuenta de redes sociales        |   Normal        |    Modulo de autenticación       |   El sistema debe verificar las credenciales del usuario antes de condecer el acceso al aplicativo  |   El sistema debe permitir seleccionar las opciones de ingrreso por cuentas de redes sociales      |

<br>

<br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.1.2.1.3.3. Capacidad de ser administrado

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Escenario capacidad de ser administrado 1**

|  |  |
|-----------|-----------|
|   **Escenario**        |El sistema debe permitir a los administradores del sistema y a los dueños de establecimientos agregar nuevos lugares de interés relevantes para la comunidad de mascotas, como centros de adopción, centros comerciales y clínicas veterinarias. Estos lugares deben ser fácilmente registrados por los actores, proporcionando información importante como el nombre, la ubicación, los horarios de atención, los servicios que se ofrecen. Además, una vez que se hayan registrado estos lugares, el sistema debe hacerlos disponibles en la funcionalidad de visualización de mapas, permitiendo a los usuarios encontrarlos fácilmente y tenerlos en cuenta al momento de planificar una visita o buscar servicios para sus mascotas.         |
|   **Atributo**        |   Capacidad para ser administrado        |
|     **Característica**      |   El sistema debe permitir registrar los lugares de interés como centros de adopción, centros comerciales y veterinarias para que luego los usuarios puedan encontrarlos y tenerlos en cuenta al momento de una visita			        |


|  **Fuente Estímulo**   | **Estímulo**     | **Ambiente**     | **Artefacto**     | **Respuesta**     | **Medida Respuesta**    |
|-----------|-----------|-----------|-----------|-----------|-----------|
| Administrador del sistema        |  Registrar un nuevo lugar dentro del mapa interactivo       |   Normal        |   Modulo del mapa    |   Una vez se registren los nuevos lugares dentro del mapa, una vez un usuario ingrese dentro del mapa usando la aplicación debe poder ver la nueva información que se ha agregado |   Cuando se consulte el mapa interactivo y se de un vistazo dentro de la ubicación del nuevo lugar, tanto administradores como usuarios deben tener la capacidad de verlo      |

<br>

<br>


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.1.2.1.3.4. Disponibilidad


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Escenario disponibilidad 1**

|  |  |
|-----------|-----------|
|   **Escenario**        |El sistema debe contar con una función de recordatorios automatizados, que permita a los usuarios programar y recibir notificaciones en la aplicación sobre los cuidados que requieren sus mascotas. Estos recordatorios deben tener en cuenta la mascota a la que corresponde el cuidado y los tiempos recomendados para llevarlo a cabo de nuevo, según la información registrada previamente. De esta manera, los usuarios podrán estar al tanto de las necesidades específicas de cada mascota y asegurarse de proporcionarles los cuidados adecuados en el momento adecuado.       |
|   **Atributo**        |   Disponibilidad       |
|     **Característica**      |  El sistema debe enviar recordatorios a los usuarios de los cuidados que se hayan registrado, teniendo en cuenta la mascota a la cual va ligado el cuidado y también los tiempos que se consideran pertinentes para realizar el cuidado de nuevo					        |


|  **Fuente Estímulo**   | **Estímulo**     | **Ambiente**     | **Artefacto**     | **Respuesta**     | **Medida Respuesta**    |
|-----------|-----------|-----------|-----------|-----------|-----------|
| Tiempo      |  Enviar una notificación correspondiente a un cuidado    |   Normal        |   Modulo de notificaciones    |   El sistema debe mostrar en pantalla un recordatorio con el cuidado que es pertinente practicar a la mascota respecto al tiempo que ha pasado desde la última vez que se ha realizado este cuidado |   En la pantalla del usuario se debe mostrar una notificación de un cuidado que se haya registrado con antelación y la app identifique como necesario    |

<br>

<br>



&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.1.2.1.3.5. Escalabilidad

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Escenario escalabilidad 1**

|  |  |
|-----------|-----------|
|   **Escenario**        |El sistema debe contar con una arquitectura escalable y una base de datos optimizada para soportar un crecimiento exponencial en el número de usuarios y mascotas registradas. Esto permitirá que la aplicación pueda manejar eficientemente un gran volumen de datos y proporcionar una experiencia de usuario fluida y sin interrupciones, incluso cuando se agreguen nuevos usuarios y mascotas. Además, el sistema debe contar con un monitoreo constante del rendimiento y la capacidad, a fin de detectar y resolver de manera proactiva cualquier problema que pueda surgir con el crecimiento de la base de datos y asegurar que la aplicación funcione sin problemas para todos los usuarios. |
|   **Atributo**        |  Escalabilidad      |
|     **Característica**      |  El sistema debe tener un crecimiento respecto a la cantidad de usuarios y mascotas que se hayan registrado en cuestión de base de datos			        |


|  **Fuente Estímulo**   | **Estímulo**     | **Ambiente**     | **Artefacto**     | **Respuesta**     | **Medida Respuesta**    |
|-----------|-----------|-----------|-----------|-----------|-----------|
| Administrador del sistema      |  Crecer en capacidad para albergar más información  |   Normal        |  Modulo de bases de datos   | Conforme vayan creciendo la cantidad de usuarios dentro de la plataforma el sistema debe asignar más capacidad de almacenamiento, debe ser una relación directamenete proporcional para poder llevar un control acertado del mismo y hacer un manejo de los costos adecuados |   Cuando se ingrese un nuevo usuario, una nueva mascota, un nuevo cuidado o cualquier elemento que necesite un crecimiento de base de datos debe ser registrado correctamenete y luego debe poder ser verificado una vez el usuario ingrese dentro del sistema de información, pudiendo ver los nuevos ingresos de información    |

<br>

<br>




&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.1.2.1.3.6. Flexibilidad

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Escenario flexibilidad 1**

|  |  |
|-----------|-----------|
|   **Escenario**        |La aplicación debe permitir al usuario elegir con cuántos días de anticipación quiere recibir un recordatorio especial antes de una fecha importante, como un cumpleaños o un evento de vacunación para su mascota. El usuario debe poder seleccionar entre diferentes opciones de anticipación, como 1, 3 o 5 días antes de la fecha en cuestión. Esto permitirá que el usuario tenga un tiempo adecuado para prepararse y tomar las medidas necesarias antes de la fecha, lo que a su vez mejorará la experiencia del usuario y aumentará la satisfacción con la aplicación. Además, la aplicación debe enviar recordatorios precisos y oportunos, para asegurar que el usuario no se pierda ninguna fecha importante relacionada con su mascota. |
|   **Atributo**        |  Flexibilidad      |
|     **Característica**      |  Permiteme escoger los días de antelación en la que quiere recibir un recordatorio especial antes de que ocurra una fecha, estos días los podré escoger entre 1, 3 y 5 días antes 			        |


|  **Fuente Estímulo**   | **Estímulo**     | **Ambiente**     | **Artefacto**     | **Respuesta**     | **Medida Respuesta**    |
|-----------|-----------|-----------|-----------|-----------|-----------|
| Administrador del sistema, dueño      |  Elegir una de las fechas de recordatorio disponibles  |   Normal        |  Modulo cuidados basicos | El sistema debe mostrar que se configuro correctamente la fecha de recordatorio |   Al cumplir los tiempos establecidos debe generar en recordatorio.   |

<br>

<br>



&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.1.2.1.3.7. Internacionalización

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Escenario internacionalización 1**

|  |  |
|-----------|-----------|
|   **Escenario**        |La aplicación debe proporcionar información útil y relevante al usuario basada en la raza de su mascota. Para lograr esto, la aplicación debe contar con una base de datos actualizada de razas de mascotas y sus características específicas, incluyendo su dieta, su nivel de actividad física recomendado, sus necesidades de atención médica, entre otras. Al ingresar la raza de su mascota en la aplicación, el usuario recibirá recomendaciones personalizadas y consejos útiles, como información sobre nutrición y cuidado específicos para su raza, ejercicios y actividades recomendados para mantener a su mascota saludable y feliz, y también recomendaciones de productos y servicios relacionados con su mascota. Esto proporcionará una experiencia de usuario personalizada y mejorará la satisfacción y fidelidad del usuario.|
|   **Atributo**        |  Internacionalización      |
|     **Característica**      |  La aplicación debe mostrarle información de interés al usuario dependiendo de La raza de La mascota que se haya ingresado        |


|  **Fuente Estímulo**   | **Estímulo**     | **Ambiente**     | **Artefacto**     | **Respuesta**     | **Medida Respuesta**    |
|-----------|-----------|-----------|-----------|-----------|-----------|
| Administrador del sistema, dueño      | Mostrar información de interes al usuario respecto a la raza |   Normal        |  Modulo de mascotas | El sistema le muestra correctamente la infomacion de la mascota segun su raza |   Información sobre raza subministrada correctamente, información veridica   |

<br>

<br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.1.2.1.3.8. Usabilidad

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Escenario usabilidad 1**

|  |  |
|-----------|-----------|
|   **Escenario**        |El sistema debe ofrecer una funcionalidad para que los usuarios puedan registrar de manera sencilla y rápida a sus mascotas en la aplicación, proporcionando información relevante como el nombre, la especie, la raza, la edad, el género, el historial médico, entre otros datos importantes. Esto permitirá a los usuarios llevar un control más detallado sobre la salud y el bienestar de sus mascotas, y les proporcionará una herramienta práctica y útil para el cuidado de sus animales de compañía.|
|   **Atributo**        |  Usabilidad      |
|     **Característica**      |  El sistema debe permitir a los usuarios registrar sus mascotas		  |


|  **Fuente Estímulo**   | **Estímulo**     | **Ambiente**     | **Artefacto**     | **Respuesta**     | **Medida Respuesta**    |
|-----------|-----------|-----------|-----------|-----------|-----------|
| Dueño      | Registrar una mascota |   Normal        |  Modulo de mascotas | El sistema debe mostrar en la pantalla que se ha agregado la mascota correctamente |   Cuando el usuario ingresa dentro del apartado de mascotas se debe mostrar la mascota que se ha agregado recientemente sin importar la cantidad de mascotas que se hayan registrado   |

<br>

<br>



<br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.1.2.1.4. Tácticas y estrategias

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Seguridad**

Táctica:

Estrategia: 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Escalabilidad**

Táctica:

Estrategia: 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Disponibilidad**

Táctica:

Estrategia: 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Flexibilidad**

Táctica:

Estrategia: 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Accesibilidad**

Táctica:

Estrategia: 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Internacionalización**

Táctica:

Estrategia: 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Usabilidad**

Táctica:

Estrategia: 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Capacidad para ser administrado**

Táctica:

Estrategia: 






