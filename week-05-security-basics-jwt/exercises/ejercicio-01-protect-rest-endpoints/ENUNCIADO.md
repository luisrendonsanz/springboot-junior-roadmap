# Enunciado — Protect REST Endpoints

## Qué construir
Protege una API y distingue endpoints públicos de protegidos.

## Requisitos
- Configura SecurityFilterChain
- deja un endpoint público
- protege otro
- una petición sin autenticar debe ser rechazada
- explica el status observado.

## Restricciones
- Mantén un único flujo de autenticación simple.
- No añadas OAuth2, refresh tokens o arquitectura de microservicios.
- No subas secretos.
- No desactives seguridad globalmente solo para hacer pasar una petición.

## Criterios de aceptación
- Los accesos permitidos y rechazados son reproducibles.
- Puedes explicar por qué una respuesta es 401 o 403.
- La configuración es suficientemente pequeña para poder razonarla.
