# Quiz 0

**Name**: {Tom}  
**Student ID**: {A00054616}
#Qué estrategias usaría para hacer un producto escalable, ventajas y desventajas

## Answers

1.  
Es posible mejorar el trabajo que hacen los equipos de desarrollo cuando tienen un sólo producto muy denso o complejo, como Netflix, haciendo uso de los micros servicios y todas las tecnologías y prácticas que estos implican como: Integración contínua, monitoreo, pruebas de integración, pípelines, repositorios (versionamiento), entre otros.


Las ventajas de usar esta herramienta se basan en que se va a tener un mejor control sobre los módulos que constituyen la aplicación: development, integration, testing, monitoring y deployment (production).Esto permite agilizar el desarrollo del proceso y mejorar su calidad, añadiendo valor al producto. Adicionalmente, permite conformar equipos más especializados según los microservicios, generando apropiación por parte de los ingenieros.

Las desventajas se constituyen en la complejidad que implica implementar microservicios, todas las tecnologías y herramientas nuevas que se tienen que integrar, las dependencias entre los microservicios (realizar cambios puede resultar en problemas de incompatibilidad), debuggear se torna más complejo debido a que las pruebas unitarias pierden efectividad.

2. 
Siempre puedes curiosear con lo existente en la configuración...
git config --global --list
 
Primero, elimina el usuario actual (nombre y correo).


git config --global --unset-all user.name
git config --global --unset-all user.email
 
Luego, vuelve a configurar las propiedades con tus datos.


git config --global --add user.name "El nuevo usuario"
git config --global --add user.email "nuevo@correo.com"
