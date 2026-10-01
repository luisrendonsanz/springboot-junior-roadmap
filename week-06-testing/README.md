# Semana 6 — Testing

## Objetivo
Dejar de ser consumidor de tests y aprender a diseñarlos: qué probar, en qué nivel y con qué coste.

## Spring Initializr
Base: Maven, Java 21, Spring Boot 4.1.1. Usa **Spring Boot Test** (incluido habitualmente en proyectos Initializr), Spring Web/JPA según cada ejercicio.

## Documentación
- https://docs.spring.io/spring-boot/reference/testing/
- https://junit.org/junit5/docs/current/user-guide/
- https://javadoc.io/doc/org.mockito/mockito-core/latest/org.mockito/org/mockito/Mockito.html

## Definition of Done
- [ ] Distingo unit, slice e integration tests.
- [ ] No uso @SpringBootTest para todo.
- [ ] Sé usar mocks sin convertir el test en una copia de la implementación.
- [ ] Mis tests expresan comportamiento observable.
- [ ] Puedo justificar qué no estoy probando.

## Reto extra
Revisa un ejercicio anterior y elimina tests redundantes o frágiles justificando el cambio en el PR.
