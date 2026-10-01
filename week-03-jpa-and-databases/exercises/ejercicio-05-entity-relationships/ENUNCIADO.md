# Enunciado — Entity Relationships

## Qué construir
Modela authors y books con una relación coherente.

## Requisitos
- Un author puede tener varios books
- cada book pertenece a un author
- crea/consulta datos
- evita serialización recursiva accidental
- justifica ownership.

## Restricciones
- No introduzcas patrones avanzados por anticipado.
- No uses `ddl-auto=create-drop` sin entender qué implica.
- No subas contraseñas reales.
- Mantén el dominio pequeño para concentrarte en persistencia.

## Criterios de aceptación
- Los datos se leen/escriben como exige el ejercicio.
- El repository no contiene lógica de negocio.
- Puedes explicar qué parte hace Spring Data y qué parte hace JPA/Hibernate.
