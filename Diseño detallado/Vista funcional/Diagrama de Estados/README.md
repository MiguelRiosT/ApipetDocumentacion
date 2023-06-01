
## 1.2.1.4 Diagrama de estado

**Nombre:** Diagrama de estado - Reporte salud mascota

![Diagrama de estado - Reporte salud mascota](https://github.com/MiguelRiosT/ApipetDocumentacion/blob/main/Dise%C3%B1o%20detallado/Vista%20funcional/Diagrama%20de%20Estados/Diagrama%20de%20estados%20-%20Reporte%20salud%20mascota.drawio.png)

**Objetivo/motivación:**

Es una herramienta valiosa para comprender, diseñar y comunicar el comportamiento de un sistema. Ayuda a visualizar el flujo de control, identificar los estados y transiciones, capturar requisitos y reglas de negocio, detectar problemas y errores, y facilitar la comunicación efectiva entre los miembros del equipo. 

Los principales beneficios y ventajas de tener este diagrama son:

- Mejora la comprensión de un objeto o sistema y permite entender cómo éste se comporta.

- Descubrir falencias o aspectos que no se tomaron en cuenta en un inicio.

- Identificación de estados y transiciones.

- Detección de problemas o errores que se puedan presentar.

**Documentación elementos que lo conforman**

Este diagrama de estados se encarga de representar el flujo de un reporte, dicho reporte es sobre la salud de una mascota el cuál puede ser enferma, saludable, en terapia y en recuperación.

<br>

< Modelado estado Objeto/transaccion/ operacion N >

**Inicio** -> Estado Reporte salud mascota

1.2.1.4.1. < Salud mascota/seleccionar mascota/ Mascota seleccionada > 

1.2.1.4.2. < Salud mascota/Enviar reporte a revisión/ Mascota enviada a revisión >

1.2.1.4.2.1 < Salud mascota/Validar se encuentra bien/ Saludable >

1.2.1.4.2.1.1 < Salud mascota/Esta saludable/ Entregar reporte >

**Fin ->  Estado Reporte salud mascota**

