# Lista 04

## Kruchten s 4 + Model View

Debido a la dificultad de caputar el comportamiento completo de un sistema con una sola perspectiva al analizar si el software logra
su objetivo. debido a esto nace Kruchtens 4 + 1 model view que permite describir el sistema en distintas perspectivas. para ello se ocupan 
diversas vistas que se mencionaran a continuacion.

* **Logical View**
  Se centra principalmente en lograr los requisitos funcionales de un sistema. El contexto son los servicios que se deben proporcionar
  a los usuarios finales. En la practica, la vista logica generalmente involucra los objetos del sistema.
  **Un diagrama de clase UML** que ilustra la vista logica cuyo proposito es establecer el vocabulario del problema y el sistema
  resultante. Esto tambien puede ser util al especificar esquemas de base de datos debido a que se hace mas facil ver como interactuan
  las clases.

* **Process View**
  Se centra en lograr los requisitos no funcionales que especifican las cualidades deseadas para el sistema incluyendo
  atributos de calidad como el rendimiento y la disponibilidad.La vista de procesos presenta procesos que corresponden 
  a los objetos en una vista logica, es decir mostrara el orden de ejecucion de sus diferentes objetos. 
  **Un diagrama de secuencia UML** seria util para ilustrar los metodos, como se ejecutan y en que orden,
  un **diaagrama de actividad de UML** puede ilustrar los procesos o actividades de un sistema.


* **Development view**
  Se describe la estructura jerarquica del software. La vista de desarrollo tambien considera elementos como lenguajes de
  programacion, bibliotecas y conjunto de herramientas (Detalles del desarrollo de software ). Ademas del codigo se incluyen 
  detalles de gestion como programacion, presupuestos y asignacion de trabajo siendo esto ultimo esencial.
 
* **Physical View**
  Maneja como los elementos del proceso logico y las vistas de desarrollo deben asignarse a nodos diferentes o hardware para ejecutar 
  el sistema. Un **Diagrama de implementacion de UML** puede expresar como se implementan las piezas de un sstema en entornos de hardware 
  o ejecucion  

Los **Escenarios** se alinian con los casos de usos o las tareas de usuarios de un sistema y muestra como funcionan juntas
las otras cuatro vistas. Para cada escenario, hay un **script** que describe la secuencia de interacciones entre objetos y procesos.

Los diversos puntos de vistas no son totalmente independientes entre si. Si algunos de los puntos de vistas es considerado inutil puede 
ser omitido.

## UML Component Diagram

  Se refieren a los componentes de un sistema. Cada commponente proporciona una interfaz para que otros componentes interactuen con el.
  Los diagramas de componentes se utilizan para visualizar como interactuan las pizas de un sistema y que relaciones tienen etre ellas.

  ![UML CD](https://www.softwareideas.net/i/DirectImage/366/uml-component-diagram.png)

  Lo que diferencia este diagrama a otros diagramas es que se trata de una estructura de alto nivel y no de detalles
  como atributos y metodos. Se trata puramente de componentes y como interactuan entre si.

  La base de los diagramas de componentes son los componentes y sus relaciones. Cada componente tiene una relacion especifica con
  otro a travez de la interfaz de usuario que proporciona.

## UML Package Diagram
  Cuando crea software orientado a objetos, define clases que interactuan, aveces tienes varias clases que estan relacionadas de alguna 
  manera. Un **Paquete** agrupa elementos del software que estan relacionados. Estos elementos se pueden relacionar en funcion de datos,
  clases, tareas de usuarios, mismo paquete. Los diagramas de paquetes muestran los paquetes y las dependencias entre ellos. Puede crear
  uno de estos diagramas para organizar su sistema completo en paquetes de elementos empaquetables relacionados. Estos son utiles cuando
  se desea una mirada de alto nivel en su sistema. **Package Diagram** se puede crear en cualquier etapa del desarrollo. se adaptan y cambian
  con la ultima version de su software. Son muy utiles para los diseñadores tecnicos para ver las dependencias y reaciones entre grupos 
  de elementos relacionados.
  ![UML PD](https://sparxsystems.com/enterprise_architect_user_guide/15.2/images/package-diagram-8220.png)


## UML Deployment Diagram

## UML Activity Diagram

## Layered Systems

## Cliente Server n-Tier

## Pipes and Filters

## Event Based

## Process Control
