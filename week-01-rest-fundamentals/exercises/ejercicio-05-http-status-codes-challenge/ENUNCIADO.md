# Enunciado — REST Status Codes Challenge

## Qué construir
Crea una API pequeña de usernames únicos y usa status codes coherentes.

## Requisitos
- POST /api/users
- duplicado -> 409
- petición inválida -> 400
- creación -> 201
- GET por id inexistente -> 404.

## Restricciones
- Sin base de datos ni JPA.
- Sin copiar soluciones completas.
- Define tú las clases y organización interna.
- Mantén el alcance del ejercicio.

## Criterios de aceptación
- El comportamiento HTTP descrito es reproducible.
- Los errores no se esconden detrás de HTTP 200.
- Puedes justificar body, path/query params y status codes usados.
