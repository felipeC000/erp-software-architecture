# Vista de Despliegue

La arquitectura del sistema ERP puede desplegarse en un ambiente cliente-servidor.

## Componentes desplegados

### Cliente

Navegador web utilizado por los usuarios para acceder al sistema.

### Servidor Frontend

Aloja la aplicación desarrollada en React y proporciona la interfaz de usuario.

### Servidor Backend

Ejecuta la API desarrollada con Spring Boot y contiene la lógica del negocio.

### Servidor de Base de Datos

Ejecuta PostgreSQL y almacena la información del ERP.

## Esquema de despliegue

Usuario
↓
Frontend React
↓
API Spring Boot
↓
Base de Datos PostgreSQL
