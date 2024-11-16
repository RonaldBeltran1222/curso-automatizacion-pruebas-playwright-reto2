# Soluciones al reto

## Primer test

Para solcuionar el primer test use los lacator con un mapeo del Xpath, esta es una forma que no habia usado en mis otros test.

Esta es la solucion:
_Mapeo del search de la pagina_
![locator](./screenshots/locator.png)

_Expects y mapeo_
![expects](./screenshots/expectLocator.png)

_Otra forma de mapear el serch_

![search](./screenshots/Search.png)

## Segundo test

Para solucionar el error del segundo test, se tenia que ir de la mano el reporte que genera playwrigth ya que a simple vista no esta mal, pero usando el debug se puede observar que en el ejeccio en la _linea 29_ se esta tratando de optener un texto cuando lo que retorna ese elemento es un atributo por eso se modifica como se muestra en la solucion.

Esta es la solucion:
![test2](./screenshots/test2.png)

## Tercer test

El tercer test presentaba el mismo error que el test 2 y tenia un error de espacio de un espacio en blanco en mapeo del boton search en la solucion se resaltan los cambios.

Esta es la solucion:
![test3](./screenshots/test3.png)
