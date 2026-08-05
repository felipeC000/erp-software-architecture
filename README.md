# Sistema ERP Empresarial

## Descripción del Proyecto

Este proyecto consiste en el diseño y documentación de un sistema **ERP (Enterprise Resource Planning)** orientado a la gestión integral de los procesos empresariales.

El sistema busca centralizar la información de diferentes áreas de la organización, permitiendo mejorar la eficiencia operativa, controlar procesos administrativos y facilitar la toma de decisiones mediante información confiable.

Los módulos principales contemplados en el sistema son:

* Módulo de Compras
* Módulo de Facturación
* Módulo Stock/Costos
* Módulo Activos Fijos
* Módulo Empleados
* Módulo EIS (Sistema de Información Ejecutiva)

---

# Módulo desarrollado: Compras

El Módulo de Compras permite gestionar el proceso de adquisición de productos y servicios dentro de la organización.

Sus principales funcionalidades son:

* Registro y gestión de proveedores.
* Registro y administración de productos.
* Creación de órdenes de compra.
* Recepción de mercancía.
* Consulta del historial de compras.

El objetivo es garantizar un proceso de compra organizado, trazable y eficiente.

---

# Arquitectura del Sistema

La arquitectura del sistema está documentada siguiendo el modelo **arc42**, incluyendo:

* Objetivos y requisitos del sistema.
* Restricciones arquitectónicas.
* Diagrama de contexto (C1).
* Diagrama de contenedores (C2).
* Vista de ejecución.
* Vista de despliegue.
* Glosario del dominio.

La documentación arquitectónica se encuentra en la carpeta:

```
docs/
```

---

# Tecnologías Utilizadas

## Backend

* Java
* Spring Boot

Responsabilidades:

* Implementar reglas de negocio.
* Exponer servicios mediante API.
* Gestionar operaciones del sistema.

## Frontend

* React

Responsabilidades:

* Proporcionar la interfaz de usuario.
* Permitir la interacción con los módulos del ERP.

## Base de Datos

* PostgreSQL

Responsabilidades:

* Almacenar información de usuarios, proveedores, productos y transacciones.

## Control de Versiones

* GitHub

Utilizado para gestionar:

* Código fuente.
* Documentación.
* Diagramas de arquitectura.

---

# Estructura del Proyecto

```
/
├── docs/
│   ├── images/
│   │   ├── c1_context.png
│   │   ├── c2_containers.png
│   │   ├── sequence_register_product.png
│   │   └── mer.png
│   │
│   ├── 01_introduction_and_goals.md
│   ├── 02_architecture_constraints.md
│   ├── 03_system_scope_and_context.md
│   ├── 05_building_block_view.md
│   ├── 06_runtime_view.md
│   ├── 07_deployment_view.md
│   └── 10_glossary.md
│
└── README.md
```

---

# Gestión del Proyecto

La planificación y seguimiento del trabajo se realizaron utilizando Jira/Notion.

## Épica principal

**Módulo de Compras**

Incluye las siguientes historias de usuario:

* Registro de proveedores.
* Registro de productos.
* Creación de órdenes de compra.
* Recepción de mercancía.
* Consulta del historial de compras.

Cada historia cuenta con:

* Descripción en formato:

  > Como <rol>, quiero <acción>, para que <beneficio>.

* Criterios de aceptación utilizando formato:

  > Dado - Cuando - Entonces.

* Priorización mediante técnica MoSCoW.

---

# Diagramas de Arquitectura

Los diagramas utilizados en la documentación se encuentran en:

```
docs/images/
```

Incluyen:

* Diagrama de Contexto (C1).
* Diagrama de Contenedores (C2).
* Diagrama de Secuencia.
* Modelo Entidad Relación (MER).

---

# Instalación y Ejecución

## Requisitos previos

* Java JDK instalado.
* Node.js instalado.
* PostgreSQL instalado.
* Git instalado.

## Backend

Clonar el repositorio:

```bash
git clone <url-del-repositorio>
```

Ingresar al proyecto backend y ejecutar:

```bash
./mvnw spring-boot:run
```

## Frontend

Instalar dependencias:

```bash
npm install
```

Ejecutar aplicación:

```bash
npm start
```

---

# Equipo de Desarrollo

Proyecto académico de diseño y documentación de un sistema ERP.

---

# Licencia

Proyecto desarrollado con fines educativos.
