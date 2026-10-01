# Enunciado — Repository Slice Tests

## Qué construir
Prueba queries JPA contra una base de datos de test.

## Requisitos
- Usa @DataJpaTest
- prepara datos
- prueba una derived query y/o @Query
- no levantes toda la app
- evita depender del orden accidental de resultados.

## Restricciones
- No persigas cobertura alta como objetivo aislado.
- No mockees el objeto que estás intentando probar.
- No escribas assertions triviales que no protegen comportamiento.
- Mantén los fixtures pequeños y legibles.

## Criterios de aceptación
- Las pruebas son repetibles.
- El nivel de test elegido es coherente con el riesgo/comportamiento.
- Puedes explicar qué dependencia es real y cuál está sustituida.
