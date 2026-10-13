# Arquitectura del sistema Easygest

## Estilo arquitectónico
Para el sistema Easygest se seleccionó una arquitectura por capas, debido a que permite organizar los diferentes componentes del sistema según sus responsabilidades.
Esta separación facilita el mantenimiento, las futuras modificaciones y el crecimiento del sistema.

## Organización de la arquitectura

### 1. Capa de presentación
Es la parte encargada de la interacción con los usuarios. Contiene las interfaces, formularios, menús y demás elementos visuales utilizados para acceder a las funcionalidades de Easygest.

### 2. Capa de lógica de negocio
Se encarga de procesar las operaciones principales del sistema y aplicar las reglas necesarias para gestionar pedidos, productos, inventario, recepción y facturación.

### 3. Capa de servicios
Facilita la comunicación entre los diferentes componentes del sistema y permite ejecutar los servicios necesarios para las operaciones de Easygest.

### 4. Capa de acceso a datos
Se encarga de realizar las operaciones necesarias para consultar, registrar, modificar y recuperar la información almacenada.

### 5. Base de datos
Almacena de manera organizada la información utilizada por Easygest, como productos, pedidos, usuarios, movimientos de inventario y otros registros necesarios.

## Comunicación entre las capas
Las solicitudes comienzan en la capa de presentación cuando el usuario realiza una acción. Luego son enviadas a la lógica de negocio para ser procesadas.
Cuando se necesita consultar o guardar información, la lógica utiliza los servicios y el acceso a datos para comunicarse con la base de datos. Finalmente, el resultado regresa hasta la capa de presentación para mostrarse al usuario.

## Ventaja de la arquitectura seleccionada
La arquitectura por capas permite mantener separadas las responsabilidades del sistema. De esta forma, un cambio realizado en una parte de Easygest puede ser gestionado con menor impacto sobre los demás componentes.

## Riesgo o limitación
Una posible limitación es que la separación en varias capas puede aumentar la cantidad de componentes y la complejidad inicial del desarrollo. Sin embargo, esta organización facilita el mantenimiento y crecimiento futuro del sistema.
