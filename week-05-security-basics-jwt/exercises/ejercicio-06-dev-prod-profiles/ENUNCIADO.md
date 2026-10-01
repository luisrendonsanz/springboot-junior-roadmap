# Enunciado — Dev and Prod Profiles

## Qué construir
Separa configuración de desarrollo y producción.

## Requisitos
- Crea perfiles dev/prod
- dev puede usar configuración local cómoda
- prod depende de variables externas
- activa perfiles conscientemente
- documenta diferencias.

## Restricciones
- Mantén un único flujo de autenticación simple.
- No añadas OAuth2, refresh tokens o arquitectura de microservicios.
- No subas secretos.
- No desactives seguridad globalmente solo para hacer pasar una petición.

## Criterios de aceptación
- Los accesos permitidos y rechazados son reproducibles.
- Puedes explicar por qué una respuesta es 401 o 403.
- La configuración es suficientemente pequeña para poder razonarla.
