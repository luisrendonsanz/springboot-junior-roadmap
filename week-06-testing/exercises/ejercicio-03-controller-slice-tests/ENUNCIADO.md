# Enunciado — Controller Slice Tests

## Qué construir
Prueba el contrato HTTP de un controller aislando la capa service.

## Requisitos
- Usa @WebMvcTest
- usa MockMvc
- mockea el service
- comprueba status/content-type/body
- incluye un caso de error.

## Restricciones
- No persigas cobertura alta como objetivo aislado.
- No mockees el objeto que estás intentando probar.
- No escribas assertions triviales que no protegen comportamiento.
- Mantén los fixtures pequeños y legibles.

## Criterios de aceptación
- Las pruebas son repetibles.
- El nivel de test elegido es coherente con el riesgo/comportamiento.
- Puedes explicar qué dependencia es real y cuál está sustituida.
