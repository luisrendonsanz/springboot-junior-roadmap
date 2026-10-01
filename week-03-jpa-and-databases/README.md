# Semana 3 — JPA and databases

## Objetivo
Persistir datos con Spring Data JPA y comprender qué responsabilidades pertenecen a JPA, Hibernate, Spring Data y la base de datos.

## Spring Initializr
Base: Maven, Java 21, Spring Boot 3.x estable, Group `com.luisrendonsanz`.
Dependencias habituales: **Spring Web**, **Spring Data JPA**, **H2 Database**. El ejercicio 06 añade **PostgreSQL Driver**.

## Documentación
- https://docs.spring.io/spring-data/jpa/reference/
- https://jakarta.ee/specifications/persistence/
- https://www.postgresql.org/docs/

## Definition of Done
- [ ] Sé crear entities y repositories sencillos.
- [ ] Puedo explicar JPA vs Hibernate vs Spring Data.
- [ ] Sé cuándo una derived query es suficiente y cuándo usar @Query.
- [ ] Puedo modelar una relación simple sin ocultar sus implicaciones.
- [ ] Puedo cambiar H2 por PostgreSQL sin hardcodear secretos.

## Reto extra
Investiga y explica el problema N+1 usando un ejemplo pequeño. No lo “soluciones” añadiendo EAGER a todo.
