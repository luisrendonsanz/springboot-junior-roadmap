# Enunciado — Consistent Error Responses

## Qué construir
Diseña una respuesta de error consistente.

## Requisitos
- Incluye status, message y timestamp o campos equivalentes
- errores de validación muestran campos relevantes
- contrato consistente entre 400/404/409.

## Restricciones
- No conviertas cualquier excepción en 400.
- No devuelvas stack traces al cliente.
- No mezcles mensajes internos sensibles con el contrato público.
- Mantén el formato de error simple y justificable.

## Criterios de aceptación
- Los casos inválidos producen el status esperado.
- El cliente recibe información suficiente para corregir la petición.
- La lógica de manejo de errores está centralizada cuando corresponde.
