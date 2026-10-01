# Enunciado — Validate Create Requests

## Qué construir
Añade validación declarativa a un endpoint de creación.

## Requisitos
- name obligatorio
- longitud mínima/máxima
- email válido donde aplique
- petición inválida -> 400
- no hagas ifs repetitivos para reglas simples.

## Restricciones
- No conviertas cualquier excepción en 400.
- No devuelvas stack traces al cliente.
- No mezcles mensajes internos sensibles con el contrato público.
- Mantén el formato de error simple y justificable.

## Criterios de aceptación
- Los casos inválidos producen el status esperado.
- El cliente recibe información suficiente para corregir la petición.
- La lógica de manejo de errores está centralizada cuando corresponde.
