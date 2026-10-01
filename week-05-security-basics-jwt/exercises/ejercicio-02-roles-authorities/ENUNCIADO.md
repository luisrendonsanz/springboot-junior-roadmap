# Enunciado — Roles and Authorities

## Qué construir
Introduce dos niveles de acceso sencillos.

## Requisitos
- Define USER y ADMIN o authorities equivalentes
- un usuario autorizado accede
- otro autenticado pero sin permiso es rechazado
- distingue 401 y 403.

## Restricciones
- Mantén un único flujo de autenticación simple.
- No añadas OAuth2, refresh tokens o arquitectura de microservicios.
- No subas secretos.
- No desactives seguridad globalmente solo para hacer pasar una petición.

## Criterios de aceptación
- Los accesos permitidos y rechazados son reproducibles.
- Puedes explicar por qué una respuesta es 401 o 403.
- La configuración es suficientemente pequeña para poder razonarla.
