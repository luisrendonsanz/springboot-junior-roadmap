# Enunciado — Password Encoding

## Qué construir
Gestiona contraseñas sin almacenarlas en texto plano.

## Requisitos
- Configura PasswordEncoder
- almacena hash
- verifica credenciales usando el encoder
- nunca registres password en logs
- explica por qué hashing no es cifrado.

## Restricciones
- Mantén un único flujo de autenticación simple.
- No añadas OAuth2, refresh tokens o arquitectura de microservicios.
- No subas secretos.
- No desactives seguridad globalmente solo para hacer pasar una petición.

## Criterios de aceptación
- Los accesos permitidos y rechazados son reproducibles.
- Puedes explicar por qué una respuesta es 401 o 403.
- La configuración es suficientemente pequeña para poder razonarla.
