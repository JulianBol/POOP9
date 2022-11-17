# **PATRONES DE DISEÑO**

## ¿QUÉ SON?
### Describen un problema.
### Son descripciones de clases y objetos relacionados.
### Un patron de diseño: nomina, abstrae e identifica aspectos clave en una estructura de diseño.


## TIPOS DE PATRONES
### Creacionales

#### Son aquellos que abstraen el proceso de creación de objetos y ayudan a diseñar clases de forma independiente.

##### Factory
###### Tiene una interfaz abstracta para crear un objeto y delega sus subclases.

##### Abstract Factory
###### Define una interfaz abstracta para crear una familia de objetos y relaciones que son dependientes de una variedad de soluciones concretas.

##### Builder
###### Busca encapsular los detalles de la construcción de objetos tales como la instanciación de partes de un objeto.

##### Prototype
###### Permite crear objetos haciendo una copia del objeto prototipo.

##### Singleton
###### Es útil cuando se requiere una sola instancia de una clase durante el ciclo de vida de la aplicación.

#### Este tipo de patrones resuelven problemas recurrentes.
#### Brindan estrategias para configurar una gran variedad de objetos con comportamientos complejos.


### De Comportamiento
#### Estan relacionados con los algortimos y la asignación de responsabilidades entre objetos.
#### No describen solo patrones de clases y objetos, sino como estos se comunican.
##### Iterator
##### Visitor
##### Command
##### Mediator
##### Chain of responsability
##### Momento
##### Observer


### Estruturales
#### Usan la herencia para formar interfaces o implementaciones.
#### Describen formas para estructurar un objeto complejo y después pueda solicitar recursos al sistema.
##### Decorator
##### Flyweiht
##### Composite
##### Adapter
##### Facade
##### Proxy 
##### Bridge
##### Virtual Proxy
##### Counting Proxy
##### Aggregate Enforcer
##### Object Cache


## ELEMENTOS ESCENCIALES
### Nombre
### Problema
### Solución
### Consecuencias