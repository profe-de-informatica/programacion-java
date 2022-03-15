# Separadores

# Separadores

En Java utilizaremos los siguientes separadores:

*   Corchetes \[\]: Se utilizan en operaciones con vectores
*   Llaves {}: Sirven para definir bloques de código dentro de las clases y métodos.
*   Paréntesis (): Dentro de los paréntesis ubicaremos los parámetros de un método. También nos permiten realizar moldeados de objetos (lo trataremos en el tercer módulo).
*   Punto y coma ;: Se utiliza para separar las distintas sentencias de código.
*   Punto .: Se utiliza para referirnos a clases y subpaquetes. También nos da acceso a métodos o variables de variables.
*   Coma ,: Sirve para separar parámetros dentro de un método. También nos permite separar variables en su declaración.

Con anterioridad ya hemos utilizado todos ellos y conforme avancemos en el curso vamos a ir viendo mas ejemplos de su uso. Vamos a ver un pequeño recordatorio de donde los hemos utilizado:

*   Cuando definimos una variable llamada args que era un vector de Strings utilizamos los corchetes: _String**\[\]**__ args_.
*   Cuando definimos la clase Modulo1HolaMundo ya utilizamos las llaves para definir el alcance de la clase: _public class Modulo1HolaMundo **{** (...) **}**_.
*   Creando creamos el método main hicimos uso para los paréntesis para indicar el comienzo y fin de los parámetros: _public static void main**(**String\[\] args**)** {_.
*   Al finalizar la sentencia _System.out.println("Hola mundo")**;**_ hicimos uso del punto y coma para delimitar el fin de la misma.
*   En la misma sentencia que en el caso anterior _System**.**out**.**println("Hola mundo");_ hicimos uso del punto para acceder a una clase y sus objetos. En este apartado entraremos en mayor profundidad mas adelante.
*   El caracter coma aún no lo hemos utilizado, pero podríamos darle uso en el siguiente ejemplo: _void nombreFuncion(int param1**,** int param2);_ Aquí la función de la coma no es otra mas que separar los parámetros param1 y para2 del método nombreFuncion.

## Pregunta Verdadero-Falso

<quiz name=""><question><p>Para delimitar el contenido de una clase haré uso de los corchetes []</p><answer>Verdadero</answer><answer correct>Falso</answer><explanation>Para delimitar el contenido de una clase se hace uso de las llaves {} Ocurre lo mismo con los métodos.</explanation></question><question><p>En Java al final de cada línea debo colocar un punto y coma.</p><answer>Verdadero</answer><answer correct>Falso</answer><explanation>El punto y coma solo debe colocarse al final de las sentencias. Cuando declaramos una clase o método no hay que hacerlo.</explanation></question><question><p>Para crear un vector haré uso de los corchetes []</p><answer>Verdadero</answer><answer correct>Falso</answer><explanation>Para definir un vector se usan los corchetes []</explanation></question></quiz>


