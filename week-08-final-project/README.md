# Semana 8 — Final Project: Order Management API

Esta semana no incluye scaffolding, solución ni proyecto generado. Tú creas el proyecto desde Spring Initializr.

## Objetivo

Construir una API REST que integre lo aprendido durante las siete semanas anteriores.

### Dominio mínimo

- Customer
- Product
- Order
- OrderItem

Relación conceptual:

```text
Customer
   |
   └── Order
         |
         └── OrderItem ─── Product
```

## Arquitectura objetivo

```text
HTTP
  |
Controller
  |
Service ----- DTO / Mapper
  |
Repository
  |
JPA / PostgreSQL
```

El diagrama marca responsabilidades, no una lista rígida de clases.

## Spring Initializr

Genera tú el proyecto:
- Maven
- Java 21
- Spring Boot 3.x estable
- Group: `com.luisrendonsanz`
- Artifact sugerido: `order-management-api`

Tú decides las dependencias necesarias y debes poder justificar cada una.

## Requisitos funcionales

- CRUD de customers.
- CRUD de products.
- Crear orders para un customer existente.
- Una order contiene uno o más order items.
- Cada item referencia un product y una quantity.
- Consultar order por id.
- Listar orders de un customer.
- Validar datos de entrada.
- Manejar recursos inexistentes y conflictos con errores consistentes.
- Persistir en PostgreSQL.
- Añadir autenticación/autorización con una estrategia sencilla que puedas explicar.
- Documentar la API con OpenAPI.
- Ejecutar aplicación + PostgreSQL con Docker Compose.
- Diseñar y escribir una estrategia de tests.

## Hitos

- [ ] 01 — Bootstrap y configuración
- [ ] 02 — Customers
- [ ] 03 — Products
- [ ] 04 — Orders
- [ ] 05 — Persistencia y relaciones
- [ ] 06 — Validación y manejo de errores
- [ ] 07 — Seguridad
- [ ] 08 — Testing
- [ ] 09 — OpenAPI y documentación
- [ ] 10 — Docker, Compose y CI

## Decisiones que debes documentar

1. ¿Qué expones como DTO y por qué?
2. ¿Qué relaciones JPA elegiste y quién es dueño de cada relación?
3. ¿Dónde viven las reglas de negocio?
4. ¿Qué pasa si una order referencia un customer o product inexistente?
5. ¿Cómo gestionas configuración y secretos?
6. ¿Qué pruebas son unitarias, slice e integración?
7. ¿Qué limitaciones conocidas tiene tu solución?
8. ¿Qué cambiarías si la aplicación tuviera tráfico real?

## Criterios de aceptación

Un tercero debe poder:
1. clonar el repositorio;
2. entender el contrato HTTP;
3. configurar variables necesarias;
4. levantar PostgreSQL y la aplicación;
5. ejecutar las pruebas;
6. explorar la API mediante OpenAPI.

## Regla

No empieces copiando la arquitectura de los ejercicios anteriores. Diseña primero y justifica tus decisiones en el PR de cada hito.
