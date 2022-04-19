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
las otras cuatro vistas. Para cada escenario, hay un script que describe la secuencia de interacciones entre objetos y procesos.

Los diversos puntos de vistas no son totalmente independientes entre si. Si algunos de los puntos de vistas es considerado inutil puede 
ser omitido.

## UML Component Diagram

## UML Package Diagram

## UML Deployment Diagram

## UML Activity Diagram

## Layered Systems

## Cliente Server n-Tier

## Pipes and Filters

## Event Based

## Process Control
