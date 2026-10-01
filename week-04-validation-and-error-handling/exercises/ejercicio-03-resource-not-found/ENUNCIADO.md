# Enunciado — Resource Not Found

## Qué construir
Modela de forma explícita el caso de recurso no encontrado.

## Requisitos
- Define una excepción propia
- service la lanza cuando corresponde
- controller no repite try/catch por endpoint
- resultado HTTP -> 404.

## Restricciones
- No conviertas cualquier excepción en 400.
- No devuelvas stack traces al cliente.
- No mezcles mensajes internos sensibles con el contrato público.
- Mantén el formato de error simple y justificable.

## Criterios de aceptación
- Los casos inválidos producen el status esperado.
- El cliente recibe información suficiente para corregir la petición.
- La lógica de manejo de errores está centralizada cuando corresponde.
