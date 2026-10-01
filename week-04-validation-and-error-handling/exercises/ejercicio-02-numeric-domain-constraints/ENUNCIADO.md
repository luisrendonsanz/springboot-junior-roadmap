# Enunciado — Numeric and Domain Constraints

## Qué construir
Valida precios, cantidades y otros valores numéricos.

## Requisitos
- price positivo
- quantity dentro de rango razonable
- combina constraints
- distingue formato inválido de regla de dominio.

## Restricciones
- No conviertas cualquier excepción en 400.
- No devuelvas stack traces al cliente.
- No mezcles mensajes internos sensibles con el contrato público.
- Mantén el formato de error simple y justificable.

## Criterios de aceptación
- Los casos inválidos producen el status esperado.
- El cliente recibe información suficiente para corregir la petición.
- La lógica de manejo de errores está centralizada cuando corresponde.
