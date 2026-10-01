# Enunciado — Extract a Service Layer

## Qué construir
Refactoriza una API pequeña para sacar la lógica de negocio del controller.

## Requisitos
- Crea un service
- el controller delega
- el comportamiento HTTP no cambia
- evita métodos estáticos como sustituto de DI.

## Restricciones
- Sin JPA ni base de datos.
- Sin Lombok como sustituto de entender constructores/objetos.
- Sin MapStruct/ModelMapper en esta semana.
- No copies una arquitectura completa de otro proyecto.

## Criterios de aceptación
- Las responsabilidades se pueden explicar sin ambigüedad.
- El controller se centra en HTTP.
- La lógica principal no depende de detalles de presentación.
