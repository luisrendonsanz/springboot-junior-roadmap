# Enunciado — Mock Dependencies

## Qué construir
Aísla un service de su repository usando mocks.

## Requisitos
- Mockea repository
- verifica resultado
- verifica interacción relevante
- evita verificar cada llamada irrelevante
- prueba comportamiento cuando repository no encuentra datos.

## Restricciones
- No persigas cobertura alta como objetivo aislado.
- No mockees el objeto que estás intentando probar.
- No escribas assertions triviales que no protegen comportamiento.
- Mantén los fixtures pequeños y legibles.

## Criterios de aceptación
- Las pruebas son repetibles.
- El nivel de test elegido es coherente con el riesgo/comportamiento.
- Puedes explicar qué dependencia es real y cuál está sustituida.
