# Quiz 0

**Name**: Julian Gonzalez
**Student ID**: A00315288

## Answers

1. Estrategias que me permiten escalar a los equipos de desarrollo que trabajan en un mismo producto: 

     - Proponer una arquitectura correcta (escalado y disponibilidad)
     - Microservicios
     - Utilizar herramientas seguras
     - Transaccion de devop
     
Ventajas y desventajas de emplear esa estrategia para escalamiento:

Ventajas

- Escalable
- Unidades independientes mas pequeñas.
- QoS
- Servicios desacoplados e independientes.
- Facilidad para desarrollar sistemas eficientes.

Desventajas

- Descentralizado 
- Se debe dividir el problema
- Dominio y contexto limitado
- Mucha complejidad

2. La infraestructura como código permite a las instancias gestionarse de manera programada. Esto elimina la necesidad de realizar, por ejemplo, configuraciones de los distintos componentes que declaremos. Esto hace que la infraestructura sea “elástica”, es decir, escalable y replicable. Una sola persona puede implementar y gestionar una infraestructura compleja con 600 instancias utilizando el mismo bloque de código, y utilizando distintos cloud providers. Con esta práctica, conseguimos velocidad, ahorro de costes y reducción del riesgo a la hora de implantar nuestra infraestructura. Los scripts no tienen la elasticidad para tareas mas complejas.

¿Cómo ayudan las tecnologías de microservicios en la escala de los equipos de desarrollo?

- Mejor aislamiento de fallos. Si un microservicio falla, el otro continuará funcionando
- Fácil integración e implementación automática; utilizando herramientas de integración continua de código abierto como Jenkins, etc.
- Escalabilidad y reutilización, así como también eficiencia. Fácil de escalar e integrar con servicios de terceros

## Referencias

1. https://www.beeva.com/beeva-view/desarrollo/infraestructura-codigo-primeros-pasos-terraform/
2. https://www.youtube.com/watch?v=XjMTDb20O7M
3. https://apiumhub.com/es/tech-blog-barcelona/los-microservicios/

