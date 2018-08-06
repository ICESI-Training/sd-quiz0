# Quiz 0

**Name**: Nicolas Recalde Miranda  
**Student ID**: A00065888

## Questions

1.  ¿Cómo es posible escalar los equipos de desarrollo que están trabajando en un sólo producto? Ventajas y desventajas de escalar el servicio haciendo uso de esa estrategia.

## Answers
1. Es posible escalar los equipos de desarrollo escalando los servicios del producto a microservicios. De esta manera, se hacen equipos multidisciplinares y autónomos que realizan tareas de forma individual y sin depender de otros grupos. De la misma manera se aplican distintas prácticas y tecnologías como Continous Integration, Continous Delivery, Logging and Monitoring, Debugging y Pipelines.
   
  Ventajas: las principales ventaja de esta estrategia es poder automatizar procesos, tener mayor agilidad, y menor dependencia en la entrega de los productos. Los grupos de trabajo son  capaces de construir sus módulos sin depender de otro grupo y así poder añadir valor al producto en menor tiempo. Se automatizan procesos de pruebas y despliegue; así se verifica el correcto funcionamiento de la aplicación antes de ser desplegada en producción.

  Desventajas: se necesitan muchas personas para poder hacer a un equipo autónomo. Para manejar una arquitectura basada en microservicios se necesita alcanzar una madurez como empresa bastante alta para poder implementar todas las técnicas y practicas que se requiren. Esto debido a que se trabajan en múltiples lenguajes de programación, frameworks, herramientas y servicios de manejo de información. Debuggear es más complejo debido a que no se tiene el rastreo total del proceso, ya que muchos servicios se encuentran alojados en la nube, muchos más casos de prueba, si se comete un error todo el servicio y las instancias en la nube podrían caer. También se debe escoger las tecnologías con las que se va a trabajar de una manera cuidadosa, esto puede significar más o menos trabajo necesario para poder integrar y desplegar el producto.

## References
1. https://martinfowler.com/articles/microservices.html 
1. https://www.youtube.com/watch?v=XjMTDb20O7M
