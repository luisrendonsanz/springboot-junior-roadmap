# Enunciado — Delete Products

## Qué construir
Implementa borrado por id.

## Requisitos
- DELETE /api/products/{id}
- existente -> 204 sin body
- inexistente -> 404
- el recurso desaparece.

## Restricciones
- Sin base de datos ni JPA.
- Sin copiar soluciones completas.
- Define tú las clases y organización interna.
- Mantén el alcance del ejercicio.

## Criterios de aceptación
- El comportamiento HTTP descrito es reproducible.
- Los errores no se esconden detrás de HTTP 200.
- Puedes justificar body, path/query params y status codes usados.
