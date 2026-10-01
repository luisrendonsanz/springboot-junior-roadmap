# Enunciado — Global Exception Handler

## Qué construir
Centraliza la traducción de excepciones a respuestas HTTP.

## Requisitos
- Usa @ControllerAdvice/@ExceptionHandler
- maneja not found
- maneja validación
- evita capturar Exception de forma indiscriminada.

## Restricciones
- No conviertas cualquier excepción en 400.
- No devuelvas stack traces al cliente.
- No mezcles mensajes internos sensibles con el contrato público.
- Mantén el formato de error simple y justificable.

## Criterios de aceptación
- Los casos inválidos producen el status esperado.
- El cliente recibe información suficiente para corregir la petición.
- La lógica de manejo de errores está centralizada cuando corresponde.
