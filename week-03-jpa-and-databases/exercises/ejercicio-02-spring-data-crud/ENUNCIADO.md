# Enunciado — Spring Data CRUD Repository

## Qué construir
Sustituye almacenamiento manual por Spring Data JPA.

## Requisitos
- Crea un repository que extienda JpaRepository
- implementa CRUD desde service/controller
- evita reimplementar métodos que Spring Data ya ofrece.

## Restricciones
- No introduzcas patrones avanzados por anticipado.
- No uses `ddl-auto=create-drop` sin entender qué implica.
- No subas contraseñas reales.
- Mantén el dominio pequeño para concentrarte en persistencia.

## Criterios de aceptación
- Los datos se leen/escriben como exige el ejercicio.
- El repository no contiene lógica de negocio.
- Puedes explicar qué parte hace Spring Data y qué parte hace JPA/Hibernate.
