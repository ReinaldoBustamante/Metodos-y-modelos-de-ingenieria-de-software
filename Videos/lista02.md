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

El acoplamiento se puede medir en diferentes formas.

* **Inestabilidad**: Es una medida de como el cambio se propaga a traves del sistema es decir, como el cambio externo afecta a la clase. La inestabilidad en cualquiera de los extremos es buena. EL medio es lo que podria indicar un problema.

Esta se mide por las dependencia entrante llamada acoplamiento aferente, y las dependencias salientes llamadas acoplamiento eferente. 

I = AE/(AE+AA)

## Cohesion

Es lo bien que todo dentro de un modulo encaja, Lo bien que funciona hacia un proposito singular. cuando hablamos de cohesion lo hacemos en torno a su nivel, esto es para definir mejor lo que queremos decir cuando decimos cohesion.



## Measuring Cohesion

Una forma de medir la cohesion es con LCOM4

## Measures of Quality

Existen varias metricas que se pueden utilizar. Entre ellas:

* **Densidad de defectos**: Se asocia a los defectos y errores que se encuentran en su codigo. El calculo de esto se logra durante el desarrollo, pruebas y despues del lanzamiento. Calcular esto es sencillo ya que es simplemente el numero de errores. 

* **Complejidad cyclomatica**: Esto es simple de calcular. Simplemente todas las funcioes parten en 1, cuando encuentra un ciclo for,while o un condicional if cambia el flujo de control y le suma un 1.

* **Complejidad cognitiva**

* **Calificacion de capacidad de mantenimiento**

* **Factor de acoplamiento**

* **Falta de documentacion**

## Software Testing Introduction

## Software Testing Definitions

## Software Testing Strategies 

## Software Testing Perspectives

## Deplyment

## Deployment Rollback

## Towards CI, CD 

## The CICD Process

