# Enunciado — Repository Abstraction

## Qué construir
Introduce una abstracción de repository en memoria para separar acceso a datos.

## Requisitos
- Controller no conoce detalles de almacenamiento
- Service usa Repository
- Repository gestiona la colección
- sin JPA todavía.

## Restricciones
- Sin JPA ni base de datos.
- Sin Lombok como sustituto de entender constructores/objetos.
- Sin MapStruct/ModelMapper en esta semana.
- No copies una arquitectura completa de otro proyecto.

## Criterios de aceptación
- Las responsabilidades se pueden explicar sin ambigüedad.
- El controller se centra en HTTP.
- La lógica principal no depende de detalles de presentación.
