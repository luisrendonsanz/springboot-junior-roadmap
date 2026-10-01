# Enunciado — Product Catalog Queries

## Qué construir
Construye un endpoint de consulta de productos en memoria con filtros opcionales por categoría y límite.

## Requisitos
- GET /api/products
- GET /api/products?category=books
- GET /api/products?limit=2
- filtros combinables
- limit inválido debe producir 400.

## Restricciones
- Sin base de datos ni JPA.
- Sin copiar soluciones completas.
- Define tú las clases y organización interna.
- Mantén el alcance del ejercicio.

## Criterios de aceptación
- El comportamiento HTTP descrito es reproducible.
- Los errores no se esconden detrás de HTTP 200.
- Puedes justificar body, path/query params y status codes usados.
