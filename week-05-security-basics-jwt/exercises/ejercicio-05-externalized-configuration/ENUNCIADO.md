# Enunciado — Externalized Configuration

## Qué construir
Saca configuración sensible y variable fuera del código.

## Requisitos
- Externaliza al menos secreto JWT y configuración de base de datos
- usa properties/yaml y variables de entorno
- incluye valores de ejemplo no sensibles
- repo sin secretos.

## Restricciones
- Mantén un único flujo de autenticación simple.
- No añadas OAuth2, refresh tokens o arquitectura de microservicios.
- No subas secretos.
- No desactives seguridad globalmente solo para hacer pasar una petición.

## Criterios de aceptación
- Los accesos permitidos y rechazados son reproducibles.
- Puedes explicar por qué una respuesta es 401 o 403.
- La configuración es suficientemente pequeña para poder razonarla.
