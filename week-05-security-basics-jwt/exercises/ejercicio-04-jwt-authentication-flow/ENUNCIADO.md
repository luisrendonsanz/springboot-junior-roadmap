# Enunciado — JWT Authentication Flow

## Qué construir
Implementa un flujo JWT mínimo y comprensible.

## Requisitos
- POST /api/auth/login valida credenciales
- devuelve token
- un endpoint protegido acepta Bearer token válido
- token ausente/inválido se rechaza
- no metas datos sensibles en claims.

## Restricciones
- Mantén un único flujo de autenticación simple.
- No añadas OAuth2, refresh tokens o arquitectura de microservicios.
- No subas secretos.
- No desactives seguridad globalmente solo para hacer pasar una petición.

## Criterios de aceptación
- Los accesos permitidos y rechazados son reproducibles.
- Puedes explicar por qué una respuesta es 401 o 403.
- La configuración es suficientemente pequeña para poder razonarla.
