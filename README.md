# Ejercicio 2_ Formulario + BDD (SIN IA)

**Autora:** Macarena Morales Toledo  
**Proyecto:** Estudio de eficiencia de la IA  
**Tecnología:** Liferay 7.4 – MVC Portlet 

# Formulario + BDD con Liferay Objects.

Liferay Object es una herramienta *low-code* que permite crear estructuras de datos personalizadas desde la interfaz de usuario. Al definir un objeto, la plataforma
genera **automáticamente las tablas en la base de datos**, las API REST para las intregaciones, las vistas administrativas, integrándolas nativamente con el sistema de permisos, flujos de trabajo y **formularios** de Liferay.

La aplicación permite:

- ✅ Listado paginado de Tickets
- ✅ Un formulario para crear un objeto Ticket.

  ## Setup & Instalación

  1. **Requisitos Previos**:
    - Liferay DXP / Portal 7.4
    - Java JDK 11/17/21
    - Blade CLI o Gradle instalado
 
  2. **Clonar y Desplegar**:
     ```
     git clone https://github.com/MacarenaStNTTDATA/ejercicio2
     ```
     ```
     cd ejercicio-form
     ```
     ```
     blade sever start
     ```

     **Log in**
     ```
     test@liferay.com
     ```
     ```
     test1
     ```

     ## Decisiones Técnicas:

     He seguido la arquitectura que ofrece el propio Liferay.
     
     - Uso de Picklist para el selector de la Categoría.
     
     - Uso de Expression Builder para las validicaciones extras cómo la prioridad y el email.

     ## Limitaciones Documentadas:
     
     - No he encontrado forma de hacer un estado de "Enviando..."
    
     ## Apoyo en la documentación:
- [Objects](https://learn.liferay.com/w/dxp/low-code/objects)
- [Expression Builder](https://learn.liferay.com/w/dxp/low-code/objects/creating-and-managing-objects/validations/expression-builder-validations-reference)

     ## Video Demo
