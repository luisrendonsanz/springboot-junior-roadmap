# Enunciado — PostgreSQL Migration

## Qué construir
Migra un ejercicio anterior para ejecutar contra PostgreSQL.

## Requisitos
- Añade driver PostgreSQL
- externaliza URL/user/password
- conserva una configuración cómoda para desarrollo
- verifica CRUD en PostgreSQL
- no subas credenciales.

## Restricciones
- No introduzcas patrones avanzados por anticipado.
- No uses `ddl-auto=create-drop` sin entender qué implica.
- No subas contraseñas reales.
- Mantén el dominio pequeño para concentrarte en persistencia.

## Criterios de aceptación
- Los datos se leen/escriben como exige el ejercicio.
- El repository no contiene lógica de negocio.
- Puedes explicar qué parte hace Spring Data y qué parte hace JPA/Hibernate.
