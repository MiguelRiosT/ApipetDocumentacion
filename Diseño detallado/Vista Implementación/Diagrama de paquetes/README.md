#  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;🐶Software 2 - Apipet 🐱  #


## 1.2.3.1. Diagramas de paquetes

1.2.3.1.1 **Diagrama de paquetes para BackEnd:**

**Objetivo/motivación:**

<br>

![BackEnd](https://github.com/MiguelRiosT/ApipetDocumentacion/blob/main/Dise%C3%B1o%20detallado/Vista%20Implementaci%C3%B3n/Diagrama%20de%20paquetes/DiagramaDePaquetesBackEnd.drawio.png)

<br>

1.2.3.1.2 **Documentación elementos que lo conforman**


<br>

<br>

1.2.3.1.3 **Diagrama de paquetes para FrontEnd:**

![FrontEnd](https://github.com/MiguelRiosT/ApipetDocumentacion/blob/main/Dise%C3%B1o%20detallado/Vista%20Implementaci%C3%B3n/Diagrama%20de%20paquetes/DiagramaDePaquetesFrontEnd.drawio.png)

<br>

1.2.3.1.4 **Documentación elementos que lo conforman**

- **src:** Esta es la carpeta raíz del proyecto y contiene todos los archivos y carpetas relacionadas al aplicativo. 

    **src --> assets, environments y app.**

    <br>
    
    - **environments:** Se utiliza para almacenar los archivos de configuración de entorno de la aplicación.Estos archivos contienen variables y configuraciones específicas para diferentes entornos, como desarrollo, producción, pruebas.

    - **assets:** Se utiliza para almacenar recursos estáticos de la aplicación. Puede tener imágenes, archivos de estilo css, archivos de datos, fuentes, videos, dichos archivos estáticos se utilizarán en la interfaz de usuario. 

        **assets --> fonts, images y styles.**

    <br>

    - **app:** Esta carpeta contiene los archivos principales de la aplicación apipet.

      **app --> guards, modules, service, pipes, models, components y dircetives**

      - Guards: 
      
        Se utiliza para almacenar los "guards" en Angular. 

        Los "guards" son clases que implementan una interfaz específica y se utilizan para proteger las rutas de la aplicación.  

        Controlan el acceso a las rutas  y permiten o deniegan el acceso basándose en ciertas condiciones, como la autenticación del usuario o permisos específicos.

      - Modules: 
      
        En esta se organizan los modulos de la aplicación

        Los módulos en Angular son bloques de construcción que agrupan componentes, servicios, directivas y otros artefactos relacionados. Cada módulo tiene su propio contexto y funcionalidad específica. Los módulos ayudan a modularizar y organizar el código de la aplicación, permitiendo una mejor reutilización y mantenimiento.

      - Services: 
      
        Los servicios en Angular son clases que se utilizan para encapsular la lógica y las funcionalidades compartidas entre los componentes. Los servicios proporcionan métodos y funcionalidades que pueden ser utilizados por varios componentes, lo que ayuda a mantener un código más limpio y modular.
       
      - Pipes: 
      
        Los pipes son transformaciones que se aplican a los datos en las plantillas HTML para formatear, filtrar o modificar su presentación. Los pipes son funciones que aceptan un valor de entrada y devuelven un valor transformado que se muestra en la interfaz de usuario.

      - Models: 
      
        Los modelos se utilizan para definir la estructura de los objetos de datos y proporcionar una tipificación fuerte en el desarrollo de Angular.

      - Components: 
      
        Los componentes son la unidad básica de construcción de la interfaz de usuario en Angular. 

        Representan diferentes partes de la aplicación y encapsulan la lógica y la presentación relacionadas con esa parte específica. 
      
        Los componentes se componen de plantillas HTML, estilos CSS y archivos TypeScript.

      - Directives: 
      
        Las directivas son atributos, elementos o clases que se utilizan para modificar el comportamiento o la apariencia de los elementos en el DOM. Las directivas personalizadas se crean para agregar funcionalidades específicas a los elementos de la interfaz de usuario y se pueden reutilizar en diferentes partes de la aplicación.










