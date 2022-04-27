# Lista 02

## Modularity
Cuando se habla de modularidad se habla de 4 cosas:

* Coupling
* Cohesion
* Information Hiding
* Data encapsulation

Las primeras dos son medidas de como funcionan bien los modulos juntos y que tan bien cada modulo individual cumple una determinada tarea bien definida y tienden a ir juntos, por lo que mas adelante se hablara de ellos por separado.

**La informacion oculta** describe nuestra capacidad de abstraer informacion y conocimiento de una manera que nos permita completar el trabajo complejo en paralelo sin tener que saber todos los detalles de implementacion relativos a como la tarea se completara eventualmente.

**la encapsulacion de datos** se refiere a la idea que puede contener constructos y conceptos dentro de un modulo permitiendonos entender y manipular mas facilmente el concepto cando lo estamos viendo en un relativo aislamiento.

Los sistemas complejos deben dividirse en partes pequeñas. Para ello se deben tener en cuenta 3 metas.

* Descomponibilidad.
* Composibilidad
* Facilidad de entender.

asi que cuando se habla de modularidad realmente se esta hablando en descomponer y reensamblar todos estos componentes 

## Coupling
Lo que se espera lograr es que los cambios no crucen los limites de nuestros modulos idealmente cuando un requisito cambia. Los cambios en nuestro codigo deberian estar contenidos en un solo modulo: el modulo encargado de completar la funcion que ha cambiado. 
Existen 2 tipos de acoplamiento:
* **Estrecho**: cambios podrian afectar a un gran numero de modulos.
* **Holgado**: cambios no afectan a otros modulos.

Podemos ver el acoplamiento estrecho en el acoplamiento de una estructura de datos ya que al modificarla todos los modulos tendran problemas con esta. Una forma de ver el acoplamiento estrecho es con el traspaso de mensaje ya que si cambia un mensaje no deberia afectar en otro modulo.

## Measring Coupling

## Cohesion

## Measuring Cohesion

## Measures of Quality

## Software Testing Introduction

## Software Testing Definitions

## Software Testing Strategies 

## Software Testing Perspectives

## Deplyment

## Deployment Rollback

## Towards CI, CD 

## The CICD Process

