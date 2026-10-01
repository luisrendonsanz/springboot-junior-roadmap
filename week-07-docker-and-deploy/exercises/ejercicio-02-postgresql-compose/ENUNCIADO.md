# Enunciado — PostgreSQL with Compose

## Qué construir
Levanta PostgreSQL de forma reproducible con Docker Compose.

## Requisitos
- Define servicio postgres
- usa variables de entorno
- volumen para datos cuando corresponda
- conecta desde una herramienta externa o app
- no hardcodees secretos reales.

## Restricciones
- No subas secretos.
- No añadas infraestructura que no puedas explicar.
- No uses “funciona localmente” como criterio de aceptación.
- Mantén el foco en entrega junior, no en arquitectura cloud avanzada.

## Criterios de aceptación
- Los pasos de ejecución están documentados.
- El resultado es reproducible desde un checkout limpio.
- Los fallos de configuración producen diagnósticos razonables.
