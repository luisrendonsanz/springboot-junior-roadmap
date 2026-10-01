# Enunciado — Production-friendly Logging

## Qué construir
Mejora logs sin convertirlos en ruido.

## Requisitos
- Usa niveles apropiados
- registra eventos útiles
- evita passwords/tokens
- configura nivel por entorno
- identifica al menos un log que no debería existir.

## Restricciones
- No subas secretos.
- No añadas infraestructura que no puedas explicar.
- No uses “funciona localmente” como criterio de aceptación.
- Mantén el foco en entrega junior, no en arquitectura cloud avanzada.

## Criterios de aceptación
- Los pasos de ejecución están documentados.
- El resultado es reproducible desde un checkout limpio.
- Los fallos de configuración producen diagnósticos razonables.
