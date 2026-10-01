# Semana 2 — Layered architecture

## Objetivo
Separar responsabilidades y usar el contenedor de Spring de forma consciente.

## Spring Initializr
Maven · Java 21 · Spring Boot 4.1.1 · Group `com.luisrendonsanz` · **Spring Web**.

## Documentación
- https://docs.spring.io/spring-framework/reference/core/beans/dependencies/factory-collaborators.html
- https://docs.spring.io/spring-framework/reference/core/beans/classpath-scanning.html

## Definition of Done
- [ ] Controller no contiene lógica de negocio relevante.
- [ ] Uso constructor injection.
- [ ] Distingo Service, Repository, DTO y Mapper.
- [ ] Puedo justificar qué dependencia conoce cada capa.

## Reto extra
Añade una segunda implementación de repository en memoria y cambia entre ambas sin modificar el controller.
