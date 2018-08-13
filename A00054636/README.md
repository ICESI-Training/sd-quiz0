# Quiz 0

**Name**: Ruben Dario Ceballos Muriel  
**Student ID**: A00054636

## Question  
1. ¿Cómo es posible escalar los equipos de desarrollo que están trabajando en un sólo producto? Ventajas y desventajas de escalar el servicio haciendo uso de esa estrategia?

2. ¿Cuáles son las razones para infrastructure as a code (IAAC) en lugar de scripts?


## Answers

1. Es posible mejorar el trabajo que hacen los equipos de desarrollo cuando tienen un sólo producto muy denso o complejo, como Netflix, haciendo uso de los microsservicios y todas las tecnologías y prácticas que estos implican como: Integración y despliegue contínuo, monitoreo y logging, pruebas unitarias y de integración, pípelines, repositorios (versionamiento), entre otros.  

Las ventajas de usar esta herramienta se basan en que se va a tener mayor apropiación sobre los módulos y servicios que constituyen la aplicación debido a que se crean grupos especializados para cada uno de estos. Esto permite agilizar el desarrollo del proceso y mejorar su calidad, añadiendo valor al producto. Adicionalmente, se garantiza el desarrollo correcto de cada proceso desde desarrollo, pruebas, monitoreo y despliegue (producción).  

Las desventajas se constituyen en la complejidad que implica implementar microservicios, todas las tecnologías y herramientas nuevas que se tienen que integrar, las dependencias entre los microservicios (realizar cambios puede resultar en problemas de incompatibilidad), debuggear se torna más complejo debido a que las pruebas unitarias pierden efectividad. Por otro lado, es necesario contar con profesionales que sepan integrar todas las tecnologías necesarios y que puedan apropiarse del proceso como equipo.  
  
2. Existen herramientas como chef, ansible o puppet, que permiten una automatización del despliegue, configuración y actualización de infraestructuras. Esto permite evitar hacer tareas monótonas y repetitivas, como generar y ejecutar scripts de infraestructura, generando un agilismo sobre el proceso y una dedicación a otras tareas más relevantes o importantes para el equipo de trabajo. Adicionalmente, estas herramientas cuentan con funcionalidades que permiten tener un mayor control sobre la infraestructura en la que se trabaja, permitiendo ver a tiempo real el estado de la misma.  
  

## References

1. https://www.youtube.com/watch?v=XjMTDb20O7M
2. https://docs.chef.io/chef_overview.html
3. https://www.chef.io/ansible/
