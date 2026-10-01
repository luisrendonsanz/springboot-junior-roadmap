# Enunciado — First Persistent Entity

## Qué construir
Crea una API mínima que persista books en H2.

## Requisitos
- Define una entity
- usa id generado
- persiste y recupera datos
- configura H2
- comprueba qué ocurre al reiniciar según tu configuración.

## Restricciones
- No introduzcas patrones avanzados por anticipado.
- No uses `ddl-auto=create-drop` sin entender qué implica.
- No subas contraseñas reales.
- Mantén el dominio pequeño para concentrarte en persistencia.

## Criterios de aceptación
- Los datos se leen/escriben como exige el ejercicio.
- El repository no contiene lógica de negocio.
- Puedes explicar qué parte hace Spring Data y qué parte hace JPA/Hibernate.
