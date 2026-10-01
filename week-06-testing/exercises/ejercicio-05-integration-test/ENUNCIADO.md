# Enunciado — Integration Test

## Qué construir
Escribe una prueba que atraviese varias capas.

## Requisitos
- Levanta contexto completo
- verifica un flujo realista
- usa una base de datos de test
- explica qué cubre que no cubrían los slice tests.

## Restricciones
- No persigas cobertura alta como objetivo aislado.
- No mockees el objeto que estás intentando probar.
- No escribas assertions triviales que no protegen comportamiento.
- Mantén los fixtures pequeños y legibles.

## Criterios de aceptación
- Las pruebas son repetibles.
- El nivel de test elegido es coherente con el riesgo/comportamiento.
- Puedes explicar qué dependencia es real y cuál está sustituida.
