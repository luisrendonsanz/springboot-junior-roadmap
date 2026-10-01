# Spring Boot Junior Roadmap

Plan práctico de 8 semanas para consolidar competencias de Java/Spring Boot orientadas a un puesto junior.

> Este repositorio documenta mi progreso real. Los ejercicios contienen requisitos y criterios de aceptación; las implementaciones las desarrollo yo.

## Stack

- Java 21
- Spring Boot 3.x
- Maven
- Spring Web / Spring Data JPA / Validation / Security
- H2 y PostgreSQL
- JUnit 5 / Mockito / MockMvc
- Docker / Docker Compose
- OpenAPI

## Roadmap

| Semana | Tema | Estado | Evidencia | Tecnologías |
|---|---|---|---|---|
| 01 | REST fundamentals | ⬜ Not started | [week-01](./week-01-rest-fundamentals/) | Spring MVC, HTTP |
| 02 | Layered architecture | ⬜ Not started | [week-02](./week-02-layered-architecture/) | DI, DTOs, services |
| 03 | JPA and databases | ⬜ Not started | [week-03](./week-03-jpa-and-databases/) | JPA, H2, PostgreSQL |
| 04 | Validation and errors | ⬜ Not started | [week-04](./week-04-validation-and-error-handling/) | Bean Validation, ControllerAdvice |
| 05 | Security basics + JWT | ⬜ Not started | [week-05](./week-05-security-basics-jwt/) | Spring Security, JWT, profiles |
| 06 | Testing | ⬜ Not started | [week-06](./week-06-testing/) | JUnit 5, Mockito, test slices |
| 07 | Docker and deploy | ⬜ Not started | [week-07](./week-07-docker-and-deploy/) | Docker, Compose, OpenAPI, CI |
| 08 | Final project | ⬜ Not started | [week-08](./week-08-final-project/) | Full REST stack |

## Cómo trabajar

1. Elige el siguiente ejercicio.
2. Entra en su carpeta.
3. Lee `README.md` y `ENUNCIADO.md`.
4. Genera el proyecto en [Spring Initializr](https://start.spring.io/) con Java 21, Maven y Spring Boot 3.x estable.
5. Descomprime el proyecto **dentro de la carpeta del ejercicio**.
6. Trabaja en una rama `feat/week-XX-ex-YY`.
7. Haz commits pequeños siguiendo Conventional Commits.
8. Abre un PR hacia `main`.
9. Completa tus notas y marca el progreso.

Consulta [CONTRIBUTING.md](./CONTRIBUTING.md) para el flujo completo.

## Regla del repositorio

Los enunciados y la documentación sirven de guía. La implementación, configuración del proyecto y pruebas de solución deben reflejar mi propio trabajo.
