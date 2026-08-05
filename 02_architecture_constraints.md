# Restricciones de Arquitectura

## Decisiones tecnológicas

Las principales decisiones tecnológicas para el desarrollo del sistema ERP son:

### Backend

Se utilizará Java con Spring Boot para el desarrollo del backend, debido a su robustez, escalabilidad y facilidad para construir servicios empresariales.

### Base de datos

La base de datos seleccionada será PostgreSQL, ya que permite manejar información transaccional de forma segura y eficiente.

### Frontend

El frontend será desarrollado como una SPA (Single Page Application) utilizando React, permitiendo una interfaz dinámica y una mejor experiencia para los usuarios.

### Arquitectura del sistema

El sistema seguirá una arquitectura basada en capas:

- Capa de presentación: interfaz web desarrollada en React.
- Capa de negocio: servicios y reglas del ERP implementados en Spring Boot.
- Capa de datos: almacenamiento y gestión de información mediante PostgreSQL.

### Control de versiones

El código fuente y la documentación serán administrados mediante GitHub.
