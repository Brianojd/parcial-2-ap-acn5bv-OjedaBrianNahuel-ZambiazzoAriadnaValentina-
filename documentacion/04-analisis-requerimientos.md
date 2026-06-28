# Análisis de Requerimientos

## Alcance funcional del MVP

### Dentro del MVP

- Creación y gestión de obras.
- Alta, baja y modificación de empleados.
- Asignación de empleados a obras activas.
- Creación y gestión de tareas por obra.
- Asignación de tareas a empleados

### Fuera del MVP

- Generación de reportes operativos.
- Integración con sistemas externos.
- Gestión financiera completa (costos, facturación avanzada).

---

## Requerimientos funcionales

- **RF01:** El sistema debe permitir registrar, editar y eliminar empleados.
- **RF02:** El sistema debe permitir registrar, editar y eliminar obras.
- **RF03:** El sistema debe permitir asignar empleados a obras.
- **RF04:** El sistema debe permitir visualizar lps empleados por obra.
- **RF05:** El sistema debe permitir registrar tareas a obras.
- **RF06:** El sistema debe permitir asignar tareas a empleados asociados a esa obra.
- **RF07:** El sistema debe permitir visualizar el estado de avance de las tareas.
- **RF08:** El sistema debe permitir consultar el estado de avance de una obra.

---

## Requerimientos no funcionales

- **RNF01:** El sistema deberá requerir autenticación para acceder a la información. Garantizar que únicamente usuarios autorizados puedan utilizar la plataforma.
- **RNF02:** El sistema debe responder a las acciones del usuario en menos de 2 segundos.
- **RNF03:** El sistema debe ser escalable para futuras funcionalidades.

---

# Historias de Usuario basadas en Stakeholders

---

## 1: Dueño de la Empresa Constructora

###  HU01 - Visualización general del sistema
**Como** dueño de la empresa constructora,  
**quiero** visualizar el estado general de todas las obras,  
**para** poder tomar decisiones estratégicas basadas en información actualizada.

---

## 2: Encargado de Obra

### HU02 - Asignación de empleados
**Como** encargado de obra,  
**quiero** asignar empleados a distintas obras,  
**para** organizar correctamente el trabajo diario.

### HU03 - Gestión de tareas
**Como** encargado de obra,  
**quiero** registrar y actualizar tareas dentro de cada obra,  
**para** controlar el avance operativo del proyecto.

---

## 3: Empleados de Obra

### HU04 - Consulta de obras
**Como** empleado de obra,  
**quiero** consultar la información de la obra en la que trabajo,  
**para** entender el contexto de mis tareas.

### HU05 - Consulta de tareas
**Como** empleado de obra,  
**quiero** ver mis tareas asignadas,  
**para** saber qué actividades debo realizar.

### HU06 - Reporte de actividades
**Como** empleado de obra,  
**quiero** informar el estado de mis tareas,  
**para** mantener actualizado el progreso del proyecto.

---

## 4: Área Administrativa

### HU07 - Registrar Empleados
**Como** área administrativa,  
**quiero** registrar empleados en el sistema,  
**para** poder asignarlos posteriormente a las distintas obras de construcción.

### HU08 - Registrar Obras
**Como** área administrativa,  
**quiero** registrar obras en el sistema,  
**para** gestionar los proyectos de construcción de forma centralizada.

### HU09 - Generación de reportes
**Como** área administrativa,  
**quiero** consultar resúmenes del estado de las obras,  
**para** apoyar tareas de seguimiento y control.
