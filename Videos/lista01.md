# Lista 01

## Requirements vs Specification
En esta seccion se diferenciara las dos formas en que se documenta la funcionaldad en un documento de especificacion de requisitos de software. La razon por la que hay dos maneras de escribir estas delcaraciones de lo que el sistema hara, Es que hay 2 audiencias para esa informacion.

* **Usuario o cliente**: En muchos casos el usuario no es tecnico por lo que tendria un momento muy dificil al hablar con ustedes acerca de lo que quieren. Ellos no saben el potencial de lo que puede hacer. 

* **Equipo de desarollo**: Se necesita proporcionar suficientes detalles para permitir que las personas que hacen la solucion sepa lo que el sistema debe y no debe hacer.

Los **Los requisitos del usuario** son exactamente lo que el usuario quiere que la solucion haga en el idioma del usuario. Ejemplo: los usuarios no quieren iniciar sesion aunque nosotros lo queramos, sino ellos quieres que el sistema sea seguro.

La **Especificacion** es el lenguaje un poco mas tecnico de lo que el usuario quiere que haga. Ejemplo: iniciar sesion. esta especificacion debe cumplir con los requisitos del usuario

## Non-functional Requirements
Estos requisitos no especifican lo que el sistema va a hacer, si no como el sistema va a realizar los comportamientos.

Estos se clasifican en:

* **Producto**: hablan de un comportamiento especifico. Esto es a menudo en forma de requisitos de protocolo, codificaciones o requisitos de cifrado. Es decir cosas que se necesitan del producto en una vista no funcional. 

* **Organizacion**: Son aquellos definidos por la empresa. Esto es los estandares de la empresa, los requisitos de estilo de codigo de su equipo de desarrollo, procesos de desarrollo en si como usar scrum. 

* **Externa**: son un gran factor, especialmente en las industrias reguladas. Cuando la FAA(Federal Aviation Administration) dice que tienes que usar este proceso de desarrollo o cumplir con estas metricas de prueba de cobertura de codigo, eso es todo lo que hay. Tienes que hacerlo

## Software Architecture Models
Existe una variedad de modelos que se han convertido esencialmente en modelos para una serie de diferentes problemas comunes. asi que estos modelos que se presentaran a continuacion son efectivamente soluciones de mejores practicas para los problemas que ocurren comunmente a nivel empresarial.

Modelos de arquitectura de software:

* **Pipe-and-filter**: Se caracteriza por sucesivas transformaciones de flujos de datos. Un solo filtro puede consumir datos o producir datos para uno o mas puertos de salida. Tambien pueden ejecutarse simultaneamente y no son dependientes. Una tuberia tiene una sola fuente para su entrada y un solo objetivo para su salida. Conserva la secuencia de elemnetos de datos y no altera los datos que pasan.

* **blackboard**: Es cuando los componentes se comunican con una blackboard para obtener datos. el blackboard sirve como intermediario.

* **Layered**: Es una forma de dividir el sistema. Si se desea cambiar algo solo es necesario editar la capa y no lo demas. cada capa tiene una interfaz que permite comunicarse con sus capas adyacentes. 

* **Client-servidor**: Informacion primaria se almacena en un servidor, y el cliente simplemente utiliza ese servicio para realizar cualquier tarea que desea.

* **Event-based**: Esta arquitectura está compuesta por productores y consumidores de eventos. El primero detecta los eventos y los representa como mensajes. No conoce al consumidor del evento ni el resultado que generará este último. 

Una vez que se detecta un evento, este se transmite del productor a los consumidores a través de canales de eventos, donde se procesa de manera asíncrona con una plataforma para este fin. Cuando se produce un evento, se debe informar a los consumidores, quienes podrían procesarlo o simplemente recibirlo. 

La plataforma de procesamiento ejecutará la respuesta adecuada para el evento y enviará la actividad a los consumidores correspondientes. Esta actividad downstream corresponde al lugar en el que se verá el resultado del evento.

## Software Architecture Process

El proceso de diseño de la arquitectura se compone en 3_

* **System Structuring**: como el sistema se descompone en estos varios subsistemas principales y comunicaciones entre esos subsistemas son luego identificadas. Estamos intercediendo particularmente en cosas como las interfaces. Tan pronto se comienza a descomponer o separar elementos o componentes, subsistemas a gran escala de nuestro sistema general. tenemos que preocuparnos por como van a continuar comunicandonos ahora que los hemos separado. Esto es importante cuando vas a paralelisar el trabajo de desarrollo.

* **Control Modeling**: Es como las arquitecturas crean un modelo de las relaciones de control entre las diferentes partes del sistema que se establece

* **Modular descomposition**: Es como definimos esas particiones del subsistema. Estamos particularmente mirando cosas como la simplicidad. Estamos buscando cosas como mantenibilidad, confiabilidad, seguridad, todo ese tipo de atributos de calidad, pero tambien, estamos preocupados por cosas como la gestion de recursos.
