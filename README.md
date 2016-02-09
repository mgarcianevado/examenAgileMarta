Vamos a construir una calculadora que realice diferentes operaciones como son:

- Suma
- Resta
- Multiplicación

Realizada cada una de las operaciones, debe indicar el o los casos donde no se pueda realizar dicha tarea. Por ejemplo, en la resta, si el primer número es menor que el segundo.
--------------------------------------------------------------------------------------

--> HISTORIA DE USUARIOS

A continuación, vamos a analizar cada una de las historias de usuario que necesitamos para realizar el Sprint. 

 PRIMER SPRINT:

	Historias de usuario:
		SUMA
		RESTA
		MULTIPLICACION

--------------------------------------------------------------------------------------

--> ESTIMACIÓN DE PRIORIDADES

Como lo que deseamos crear es una calculadora, lo primero que debemos tener en cuenta es que vamos a usar números naturales.  La cadena de prioridades en este proyecto la hemos dispuesto valorando su nivel de dificultad.

1. Historia de Sumar:

Establecemos la historia de usuario en la que dados dos números naturales, nuestra aplicación nos va a dar el resultado de la suma de ambos.

La tarea quedará "terminada" cuando se hayan realizado las pruebas así como los test de validación con valores 'frontera'  y otros valores, y hayamos  comprobado su correcto funcionamiento.

	ESTIMACION AGIL(Planning poker): 3

2. Historia de Multiplicar:

Establecemos la historia de usuario en la que dados dos números naturales, nuestra aplicación nos va a dar el resultado de la multiplicación de ambos.

La tarea quedará "terminada" cuando se hayan realizado las pruebas así como los test de validación con valores 'frontera'  y otros valores, y hayamos  comprobado su correcto funcionamiento.

	ESTIMACION AGIL(Planning poker): 3


3. Historia de Restar:

Establecemos la historia de usuario en la que dados dos números naturales, nuestra aplicación nos va a dar el resultado de la resta de ambos. Para ello, el primer número debe ser mayor que el segundo. Si no es así nos dará un mensaje de error.

La tarea quedará "terminada" cuando se hayan realizado las pruebas así como los test de validación con valores 'frontera'  y otros valores, y hayamos  comprobado su correcto funcionamiento. 

	ESTIMACION AGIL(Planning poker): 8

En el enunciado se solicita la creación de una historia 'Error' para que el usuario sepa cuando se ha confundido. Sin embargo, considero que esa cuarta historia 'Error' no es tal sino que se trata de una tarea de la Historia Restar.

--------------------------------------------------------------------------------------
-->   PILA DE PRODUCTO

        HISTORIA DE USUARIO		PRIORIDAD
      	    Suma			         1
	Multiplicacion		         2
	   Resta			         3
	    Error		      	         4
--------------------------------------------------------------------------------------

Hemos detectado que la tarea de comprobar que son dos números naturales están presente  en todas las Historias de usuario, por lo que se podría reutilizar el código para reducir el tiempo de desarrollo.