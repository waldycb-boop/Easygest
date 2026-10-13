# Easygest

## Descripción del sistema
Easygest es un sistema digital de gestión diseñado para facilitar y organizar diferentes procesos dentro de una empresa. El sistema busca centralizar la información y permitir que los usuarios realicen sus tareas de una manera más organizada, rápida y segura.

## Objetivo
El objetivo de Easygest es mejorar la gestión de las operaciones de la empresa mediante una herramienta digital que permita registrar, consultar y controlar la información necesaria para el desarrollo de sus actividades.

## Problema que resuelve
Easygest surge como respuesta a los problemas que pueden presentarse cuando la información se maneja de forma manual o poco organizada. Esta situación puede provocar pérdida de información, errores en los registros, dificultad para consultar datos y retrasos en las actividades.
El sistema busca reducir estos inconvenientes mediante la centralización de la información y la automatización de los principales procesos de gestión.

## Funcionalidades principales
- Registrar y consultar información.
- Gestionar pedidos.
- Consultar y controlar productos disponibles.
- Gestionar el inventario y las operaciones del almacén.
- Registrar la recepción de productos.
- Realizar procesos de facturación.
- Mantener organizada la información utilizada por los diferentes usuarios.
- Facilitar el seguimiento de las operaciones realizadas en el sistema.

## Arquitectura seleccionada
Para Easygest se seleccionó una arquitectura por capas. Esta arquitectura permite dividir el sistema según las responsabilidades de cada componente, facilitando su organización, mantenimiento y crecimiento.

Las capas principales consideradas son:

- Capa de presentación: permite la interacción entre los usuarios y el sistema.
- Capa de lógica de negocio: procesa las reglas y operaciones principales de Easygest.
- Capa de servicios: facilita la comunicación y ejecución de servicios necesarios para las operaciones del sistema.
- Capa de acceso a datos: se encarga de consultar, registrar y modificar la información almacenada.
- Base de datos: almacena de manera organizada la información utilizada por Easygest.

## Organización Frontend y Backend

### Frontend
El frontend corresponde a la parte del sistema con la que interactúa directamente el usuario. Su responsabilidad sería mostrar las diferentes pantallas, formularios, botones, menús y resultados necesarios para realizar las operaciones de Easygest.
Por medio del frontend, usuarios como el recepcionista y el encargado de almacén podrían registrar información, consultar productos, gestionar pedidos y realizar las demás operaciones permitidas según sus funciones.

### Backend
El backend se encargaría de procesar las solicitudes realizadas desde el frontend, aplicar las reglas de negocio, validar la información y comunicarse con la base de datos.
También sería responsable de operaciones como guardar registros, consultar información, actualizar datos y controlar que las acciones solicitadas por los usuarios se realicen correctamente.

### Comunicación entre Frontend y Backend
El frontend enviaría las solicitudes realizadas por el usuario al backend. El backend recibiría estas solicitudes, procesaría la información y, cuando sea necesario, consultaría o modificaría los datos almacenados en la base de datos.
Después de procesar la solicitud, el backend enviaría una respuesta al frontend para mostrar el resultado al usuario. De esta manera, ambas partes trabajarían de forma separada pero coordinada para garantizar el funcionamiento de Easygest.

## Herramientas utilizadas
- GitHub: almacenamiento y control de la documentación del proyecto.
- GitHub Projects: organización y seguimiento de las tareas.
- GitHub Issues: registro y seguimiento de tareas, mejoras, incidencias y riesgos.
- Visual Paradigm Online: elaboración de modelos UML y representación de la arquitectura del sistema.

## Estado actual del proyecto
Actualmente, Easygest cuenta con la definición de sus requisitos principales, modelos UML, arquitectura inicial y organización de las tareas del proyecto. También se han utilizado GitHub Projects e Issues para controlar y dar seguimiento al trabajo realizado.
El proyecto se encuentra en una versión inicial documentada, quedando pendientes futuras etapas de implementación, pruebas y mejoras antes de disponer de una versión completamente funcional.
