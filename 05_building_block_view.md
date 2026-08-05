# Vista de Bloques de Construcción

## Diagrama de Contenedores (C2)

El diagrama de contenedores muestra los componentes principales del sistema ERP y la responsabilidad de cada uno.

<img width="260" height="862" alt="image" src="https://github.com/user-attachments/assets/ef0f14fc-9bed-496a-a261-53e36e31de7a" />

## Contenedores del sistema

### Frontend Web (React)

Responsabilidad:
- Proporcionar la interfaz gráfica para los usuarios.
- Permitir la gestión de proveedores, productos y órdenes de compra.
- Mostrar información y resultados de las operaciones.

### Backend API (Spring Boot)

Responsabilidad:
- Gestionar la lógica de negocio.
- Validar información ingresada por los usuarios.
- Procesar las solicitudes del frontend.
- Comunicarse con la base de datos.

### Base de Datos PostgreSQL

Responsabilidad:
- Almacenar información de proveedores.
- Guardar productos registrados.
- Registrar órdenes de compra.
- Mantener la información histórica del sistema.

