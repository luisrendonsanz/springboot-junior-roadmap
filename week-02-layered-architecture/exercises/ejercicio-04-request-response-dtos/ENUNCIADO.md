# Enunciado — Request and Response DTOs

## Qué construir
Separa el contrato HTTP del modelo interno.

## Requisitos
- Define request DTO y response DTO
- no expongas directamente el modelo interno
- decide qué campos acepta el cliente y cuáles devuelve la API.

## Restricciones
- Sin JPA ni base de datos.
- Sin Lombok como sustituto de entender constructores/objetos.
- Sin MapStruct/ModelMapper en esta semana.
- No copies una arquitectura completa de otro proyecto.

## Criterios de aceptación
- Las responsabilidades se pueden explicar sin ambigüedad.
- El controller se centra en HTTP.
- La lógica principal no depende de detalles de presentación.
