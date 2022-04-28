# Lista 03

## Software Development Models
En la actualidad existen muchos modelores de desarrollo de software. Con modelo de desarrollo de software me refiero a estandares de la industrias que se utilizan para desarrollar un software. Estos se diferencias entre **Predictivo** y **Adaptativo**.

* **Predictivo**: Se utiliza esto cuando se sabe exactamente lo que quiere el cliente y se tiene una confianza muy alta de los requisitos. Una vez esto el equipo realiza la fase de prueba, implementacion y testing para finalmente producir el producto que el cliente esta buscando. Es importante estar seguro de los requisitos debido a que en este modelo no permite cambios en la fase de desarrollo. 

* **Adaptativo**: Tienen una idea de lo que quieren construir, pero no del todo. Este modelo se basa en realizar un prototipo de lo que el cliente desea. Este prototipo debe ser minimalista ya que la idea es mostrarselo al cliente para luego obtener feedback y posteriormente repetir el proceso hasta finalizar el producto. Usualmente en estos modelos es muy comun terminar con un producto muy diferente al inicial.

La otra clasificacion de modelos es:

* **Incremental**: Se refiere a cuando uno tiene claro lo que tiene construir y esto lo realiza mediante incrementos. un ejemplo es un vehiculo ya que se sabe que forma debe tomar al final. Esto se realiza de manera incremental. Primero los neumaticos, luego el volante y finalmente todo lo que falta. Basicamente asi funciona un modelo incremental. Es bueno utilizarlo cuando la empresa pueda beneficiarse de estos incrementos intermedios o simplemente si necesita hacer cambios posteriormente dado los comentarios del cliente.

* **Iterativo**: Es cuando no se tiene tan clara una idea y se tiene la necesidad de cabiar el producto dado de que lo que se construyo no era lo que se pedia o construir el nuevo producto encima del anterior.

la diferencia de incremental e iterativo es que en iterativo se construye encima del otro y en incremental el problema se divide en varios tramos.

## Waterfall Model

Consiste en colocar todas las fases del desarrollo de software una tras de otra. e ir secuancialmente completando cada una. Si se llegara a encontrar un error perfectamente se puede volver a la fase anterior pero si se llegara a encontrar este error muy tarde el costo seria muy alto. Dicho esto este modelo se debe utilizar cuando los requisitos no cambian y ademas conocemos muy bien los requisitos. Por lo tanto para asegurarnos que este modelo sea existoso tenemos que asegurarnos que los requisitos sean solidos. Otra suposicion que se hace en este modelo es que el equipo tiene experiencia en la construccion de software similar. Dicho esto decimos que este modelo es mas bien **predictivo** y entre sus **ventajas** estan:
* facil de entender
* predecible
* eficiente

entre sus **desventajas** estan:
* no es flexible al cambio
* primera version toma mucho tiempo


**OCUPAR ESTE MODELO SOLO Y SOLO SI EL TRABAJO ES MUY PREDICTIBLE O ES REPETITIBLE**
## V-Model

Es lo mismo que cascada solo que las fases estan partidas en forma de v. en la **izquierda** podemos encontrar todas las fases correspondiente a la definicion del proyecto(conceptos, requerimiento, diseño) en la parte de abajo esta la implementacion y el otro lado estan las pruebas y validaciones. Este es un modelo **predictivo**.

**beneficion**: 
* Proporciona adeteccion temprana de posibles defectos y problemas 

**Contras**:
mas trabajo ya que en la fase de requerimientos debera tener una validacion de estos.

**ESTE MODELO SE DEBE USAR CUANDO EXISTE AMBUGUEDAD EN LOS REQUISITOS Y LUEGO QUIERES ALGUN TIPO DE VALIDACION TEMPRANA**

## Sashimi

Es basicamente comenzar con las primeras tareas del desarrollo en paralelo estas son (Requerimientos, diseño, implementacion y testin). Este modelo es **Predictivo** pero no al 100%.

**Beneficios**:

* Modelo util si desea acortar el tiempo de desarrollo. 

* Las personas con diferentes habilidades pueden empezar a trabajar en el proyecto sin esperar a que el trabajo esta realizado para la fase anterior.

* a veces se puede obtener un aprendizaje en una fase temprana.

**Desventajas**:

* modelo resulta en algo de retrabajo.

**ESTE MODELO SE DEBE USAR CUANDO SE QUIERE ACORTAR LA ESCALA DE TIEMPO O SI SE TIENEN TODOS LOS RECURSOS(PERSONAL) DISPONIBLES Y SE DESEA QUE EL PROYECTO COMIENZE PRONTO**
## Incremental Models

## Unified Process and its Variants

## Spiral Model

## Phase Gates Stage Gates

## Why agile

## Agile Manifesto and principles

## Scrum

En esta metodologia se trabaja en un sprint entre 1 a 4 semanas en donde se define,diseña,construye y prueba. Luego muestra su producto a sus partes interesadas y ve si necesita ajustar su producto o si necesita hacer algo diferente. Una vez hecho esto se repite el ciclo una y otra vez.

### Roles Scrum

* **Propietario del producto**: el que define lo que hay que hacer y en que orden.

* **Scrum master**: Ayuda al equipo a mantenerse fiel a los valores y principios de scrum. ademas de ayudar a facilitar la mayoria de las reuniones del equipo.

* **El equipo de desarrollo(Desarrolladores, tester y todos)**: los que hacen la mayor parte del software.

Los pasos de esta metodologia son

* 1) el propietario del producto va a hablar con los ejecutivos, el equipo, las partes interesadas, clientes, usuarios y tratara de definir exactamente lo que necesita ser construido. Esto creara algo llamado product backlog que es basicamente una lista de historias de usuarios que se priorizan y definen lo que se debe hacer.


* 2) Una vez que el equipo esta listo se reunen en una reunion llamada sprint planning meeting. Luego escogen las mejores historias en las que pueden trabajar en el sprint existente. El propietario del producto revisas esas historias con el equipo y ayuda a responder cualquier pregunta o aclara cualquier cosa que no este clara.

* 3) El equipo se reune de nuevo y luego hacen una tarea fuera de las historias lo que significa, como lo que exactamente tenemos que hacer para construir el software. Unos ejemplos de estos es diseñar bd, rellenar algunos datos, probarlos en la base de datos, crear interfaz de usuario.

* 4) Luego comienza la fase de desarrollo donde todo el mundo esta trabajando para implementar el software.

* 5) Cada 24 horas el equipo se reune en un stand-up en donde todos hablan de lo que hicieron ayer, que van a hacer hoy y si hay bloqueos.

* 6) Una vez finalizado el sprint se termina teniendo el producto terminado.

* 7) Una vez terminado el sprint suceden 2 reuniones **Sprint review** donde todo el equipo se reune con las partes interesadas,cliente y demostrar el trabajo que han hecho y obtener feedback. La siguiente reunion es **Retrospectiva de sprint** donde se habla del proceso y no del producto, es decir de como hacerlo mejor.
Entonces se habla de lo que salio bien en el ultimo sprint y lo que no salio bien. 


**Este modelo es adaptativo-iterativo**

## Kanban

## Lean Startup
