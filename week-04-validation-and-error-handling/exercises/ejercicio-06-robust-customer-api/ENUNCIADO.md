# Enunciado — Robust Customer API

## Qué construir
Construye una API de customers robusta integrando la semana.

## Requisitos
- CRUD
- validación de entrada
- email duplicado -> 409
- id inexistente -> 404
- errores con formato uniforme
- happy path y casos límite.

## Restricciones
- No conviertas cualquier excepción en 400.
- No devuelvas stack traces al cliente.
- No mezcles mensajes internos sensibles con el contrato público.
- Mantén el formato de error simple y justificable.

## Criterios de aceptación
- Los casos inválidos producen el status esperado.
- El cliente recibe información suficiente para corregir la petición.
- La lógica de manejo de errores está centralizada cuando corresponde.
