# Enunciado — Service Unit Tests

## Qué construir
Escribe tests unitarios para un service sin levantar Spring.

## Requisitos
- Prueba happy path
- prueba al menos un error
- usa assertions claras
- no levantes ApplicationContext
- identifica las dependencias del service.

## Restricciones
- No persigas cobertura alta como objetivo aislado.
- No mockees el objeto que estás intentando probar.
- No escribas assertions triviales que no protegen comportamiento.
- Mantén los fixtures pequeños y legibles.

## Criterios de aceptación
- Las pruebas son repetibles.
- El nivel de test elegido es coherente con el riesgo/comportamiento.
- Puedes explicar qué dependencia es real y cuál está sustituida.
