Vamos a construir una calculadora que realice diferentes operaciones como son:

- Suma
- Resta
- Multiplicaci�n

Realizada cada una de las operaciones, debe indicar el o los casos donde no se pueda realizar dicha tarea. Por ejemplo, en la resta, si el primer n�mero es menor que el segundo.
--------------------------------------------------------------------------------------

--> HISTORIA DE USUARIOS

A continuaci�n, vamos a analizar cada una de las historias de usuario que necesitamos para realizar el Sprint. 

 PRIMER SPRINT:

	Historias de usuario:
		SUMA
		RESTA
		MULTIPLICACION

--------------------------------------------------------------------------------------

--> ESTIMACI�N DE PRIORIDADES

Como lo que deseamos crear es una calculadora, lo primero que debemos tener en cuenta es que vamos a usar n�meros naturales.  La cadena de prioridades en este proyecto la hemos dispuesto valorando su nivel de dificultad.

1. Historia de Sumar:

Establecemos la historia de usuario en la que dados dos n�meros naturales, nuestra aplicaci�n nos va a dar el resultado de la suma de ambos.

La tarea quedar� "terminada" cuando se hayan realizado las pruebas as� como los test de validaci�n con valores 'frontera'  y otros valores, y hayamos  comprobado su correcto funcionamiento.

	ESTIMACION AGIL(Planning poker): 3

2. Historia de Multiplicar:

Establecemos la historia de usuario en la que dados dos n�meros naturales, nuestra aplicaci�n nos va a dar el resultado de la multiplicaci�n de ambos.

La tarea quedar� "terminada" cuando se hayan realizado las pruebas as� como los test de validaci�n con valores 'frontera'  y otros valores, y hayamos  comprobado su correcto funcionamiento.

	ESTIMACION AGIL(Planning poker): 3


3. Historia de Restar:

Establecemos la historia de usuario en la que dados dos n�meros naturales, nuestra aplicaci�n nos va a dar el resultado de la resta de ambos. Para ello, el primer n�mero debe ser mayor que el segundo. Si no es as� nos dar� un mensaje de error.

La tarea quedar� "terminada" cuando se hayan realizado las pruebas as� como los test de validaci�n con valores 'frontera'  y otros valores, y hayamos  comprobado su correcto funcionamiento. 

	ESTIMACION AGIL(Planning poker): 8

En el enunciado se solicita la creaci�n de una historia 'Error' para que el usuario sepa cuando se ha confundido. Sin embargo, considero que esa cuarta historia 'Error' no es tal sino que se trata de una tarea de la Historia Restar.

--------------------------------------------------------------------------------------
-->   PILA DE PRODUCTO

        HISTORIA DE USUARIO		PRIORIDAD
      	    Suma			         1
	Multiplicacion		         2
	   Resta			         3
	    Error		      	         4
--------------------------------------------------------------------------------------

Hemos detectado que la tarea de comprobar que son dos n�meros naturales est�n presente  en todas las Historias de usuario, por lo que se podr�a reutilizar el c�digo para reducir el tiempo de desarrollo.