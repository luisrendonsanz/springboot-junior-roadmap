# Enunciado — App + Database Compose

## Qué construir
Levanta app y PostgreSQL juntos.

## Requisitos
- Define ambos servicios
- la app usa el hostname del servicio DB, no localhost
- configura dependencia/health de forma razonable
- arranque reproducible con un comando.

## Restricciones
- No subas secretos.
- No añadas infraestructura que no puedas explicar.
- No uses “funciona localmente” como criterio de aceptación.
- Mantén el foco en entrega junior, no en arquitectura cloud avanzada.

## Criterios de aceptación
- Los pasos de ejecución están documentados.
- El resultado es reproducible desde un checkout limpio.
- Los fallos de configuración producen diagnósticos razonables.
