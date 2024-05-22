## Prueba Técnica Python

**Descripción:**

Este proyecto consiste en dos microservicios: uno de reservas y otro de pasajeros. El microservicio de pasajeros solo tendrá el modelo de pasajero, y el de reservaciones el modelo de pasajero y el de reserva. Se requiere que cuando se haga un update en uno, el otro servicio escuche el evento y lo actualice. Además, se requiere que el servicio de pasajeros pueda cargar más de 7000 registros, y que liste estos 7000 registros en menos de 400 ms.

**Requisitos:**

* Lenguaje de programación: Python
* Framework/Librería: Flask o FastAPI de preferencia
* Base de datos: Postgresql
* Herramienta de comunicación entre microservicios: A elegir

**Implementación:**

1. **Microservicio de pasajeros:**
    * Crear el modelo de pasajero.
    * Implementar la funcionalidad para cargar más de 7000 registros en menos de 400 ms. 
    * Implementar la funcionalidad para escuchar eventos del microservicio de reservas y actualizar la información del pasajero correspondiente.
2. **Microservicio de reservas:**
    * Crear el modelo de pasajero y el modelo de reserva.
    * Implementar la funcionalidad para crear, leer, actualizar y eliminar reservas.
    * Implementar la funcionalidad para enviar eventos al microservicio de pasajeros cuando se actualiza la información de un pasajero.

**Consideraciones:**

* Los microservicios deben ser escalables y tolerantes a fallos.
* La comunicación entre microservicios debe ser asíncrona.
* Se deben implementar pruebas unitarias y de integración para ambos microservicios.
* Se debe documentar el código de forma clara y concisa.

**Evaluación:**

La evaluación se basará en los siguientes criterios:

* Completitud de la implementación
* Corrección funcional
* Diseño del código
* Calidad de la documentación
* Rendimiento

**Entrega:**

Se deberá entregar el código fuente de los microservicios, así como la documentación correspondiente.

**Notas:**

* Esta es solo una descripción general de la prueba técnica. Los detalles específicos pueden variar.
* Se recomienda que se familiarice con las tecnologías requeridas antes de comenzar la prueba técnica.
* Si tiene alguna pregunta, no dude en contactarnos.

**¡Buena suerte!**
