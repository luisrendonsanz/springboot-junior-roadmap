# Semana 4 — Validation and error handling

## Objetivo
Construir APIs que fallen de forma predecible y comuniquen errores útiles al cliente.

## Spring Initializr
Base: Maven, Java 21, Spring Boot 4.1.1, **Spring Web** y **Validation**. Puedes añadir JPA si reutilizas persistencia de la semana anterior, pero no es el foco.

## Documentación
- https://docs.spring.io/spring-framework/reference/core/validation/beanvalidation.html
- https://docs.spring.io/spring-framework/reference/web/webmvc/mvc-controller/ann-exceptionhandler.html

## Definition of Done
- [ ] Uso Bean Validation para reglas de entrada adecuadas.
- [ ] Los recursos inexistentes producen 404.
- [ ] Centralizo el manejo de excepciones.
- [ ] Los errores JSON tienen un contrato consistente.
- [ ] No uso try/catch repetido en todos los controllers.

## Reto extra
Distingue errores de sintaxis JSON, validación de campos y reglas de negocio en respuestas diferentes pero coherentes.
