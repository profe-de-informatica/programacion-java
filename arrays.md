# Arrays

En Java existen un tipo de variables llamadas **Arrays** que nos permiten crear **vectores** de un mismo elemento. Es importante indicar que un Array es un objeto.

Existen distintos modos de declarar un Array, vamos a verlos:

```java
int[] array1 = new int[4]; // Creamos una variable llamada array1 que tendrá 4 posiciones
int array2[] = new int[4]; // Creamos una variable llamada array2 que tendrá 4 posiciones
int[] array3 = {1, 2, 3}; // Creamos una variable llamada array3 que en su posición 0 tendrá un 1, en su posición 1 tendrá un 2 y en la posición 2 tendrá un 3
```

Cuando creamos un Array como es el caso de array1 y array2 y lo inicializamos pero no definimos el valor de sus posiciones estas toman el valor por defecto de la variable, en nuestro caso 0.

La primera posición de un Array es la posición 0. En caso de intentar acceder a una posición inexistente obtendremos una excepción (se tratan mas adelante)

De un modo análogo al anterior podemos crear Arrays de Arrayx (matrices). A continuación podemos ver un ejemplo:

```java
int[][] matriz = new int[10][10];// Creamos una variable llamada matriz que es una matriz de enteros de 10x10
```

Si queremos acceder al valor de un array debemos hacerlo con la sintaxis nombreVariable[posicion]. A continuación unos ejemplos:

```java
boolean[] array4 = {false, true, false}; 
System.out.println(array4[0]);
System.out.println(array4[1]);
System.out.println(array4[2]);
```

Y lo que veríamos por pantalla:

```java
false
true
false
```

Cuando lleguemos al apartado de control de flujo realizaremos mas ejemplos con Arrays.

