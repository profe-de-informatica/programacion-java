# Constantes y variables

Una **[variable](https://es.wikipedia.org/wiki/Variable_(programaci%C3%B3n)** es un lugar en memoria donde almacenaremos un dato que podrá cambiar o no a lo largo de la ejecución de nuestros programas. Todas las variables tienen que ser de un determinado tipo y tener un nombre. Por convenio las variables tienen al menos el primer caracter de su nombre en minúsculas. Una **[constante](https://es.wikipedia.org/wiki/Constante_(inform%C3%A1tica)** es un lugar en memoria en el cual almacenaremos un dato con el fin único de leerlo y sin posibilidad de modificación. Las constante deben tener un determinado tipo y deben tener un nombre. Por convenio el nombre de las constantes se escribe en mayúsculas. En java para definir una constante lo haremos exactamente igual que si definieramos una variable pero las constantes deben ser precedidas por la [palabra reservada](https://es.wikipedia.org/wiki/Palabra_reservada) final.

Anteriormente hemos indicado que tanto las constantes como las variables deben ser de un determinado tipo, a continuación vamos a hablar de ellos.

En java **existen 2 tipos de variables: los tipos básicos** (también llamados tipos primitivos) **y los objetos**. De los objetos nos ocuparemos en el módulo 3 por lo que a continuación paso a enumerar los tipos primitivos mas habituales.

*   Números enteros:
    *   byte: utiliza 8 bits en memoria. Su rango va de -27 a 27-1
    *   short: utiliza 16 bits en memoria. Su rango va de -215 a 215-1
    *   int: utiliza 32 bits en memoria. Su rango va de -231 a 231-1
    *   long: utiliza 64 bits en memoria. Su rango va de -263 a 263-1
*   Números decimales:
    *   float: utiliza 32 bits.
    *   double: utiliza 64 bits.
*   Booleanos:
    *   boolean: utiliza 1 bit. Solo puede valer true (verdadero) o false (falso)
*   Cadenas:
    *   char: utiliza 16 bits.

Ejemplos con tipos primitivos:

```java
int operando1 = 4; // Declaramos una variable llamada operando1 de tipo int y le asignamos el valor 4

final double PI = 3.1416; // Declaramos una constante de tipo double. El nombre de la constante es PI y le asignamos el valor 3,1416

boolean esMayor = false;//Declaramos una varible de tipo boolean, con nombre esMayor y le asignamos el valor falso

final char CARACTER = 'a';// Declaramos una costante de tipo char y nombre CARACTER. Le asignamos el valor 'a'. Fíjate en que son comillas simples.
```

Aunque lo veremos en el siguiente módulo del curso a continuación vamos a crear unas variables que harán referencias a objetos. Del código que aparece a continuación me interesa que nos fijemos en que **declaremos tipos primitivos u objetos la sintaxis es prácticamente la misma**:

```java
Integer operando1  = new Integer(4); // Declaramos una variable llamada operando1 de tipo Integer y le asignamos el valor 4

final Double PI = new Double(3.1416); // Declaramos una constante de tipo Double. El nombre de la constante es PI y le asignamos el valor 3,1416

Boolean esMayor = new Boolean(false); // Declaramos una variable de tipo Boolean, con nombre esMayor y le asignamos el valor falso.

final String CADENA = "a";// Declaramos una constante de tipo String y nombre CADENA y le asignamos el valor "a". Fíjate en que son comillas dobles. Además aquí es el único lugar donde no hemos escrito new String("a") pero de esto ya hablaremos mas adelante aunque no es trivial
```

Como podemos intuir en base a estos ejemplos **cada tipo básico tiene asociado un objeto equivalente**. Pero como vemos a continuación (y profundizaremos en el módulo 3) también podemos crear variables del tipo de Objetos que hayamos creado.

```java
Coche miCoche = new Coche(); //Declaramos una variable de tipo Coche con el nombre miCoche y llamamos al constructor de la clase. Mas adelante hablaremos de esto

Moto moto1 = null; //Declaramos una variable de tipo Moto con el nombre moto1 y le asignamos el valor null
```

Si eres observador/a te habrás dado cuenta de que los tipos básicos empiezan en minúscula mientras que los objetos comienzan en mayúsculas. Es probable que también te hayas percatado de que el nombre que asigno a las variables siempre comienza en minúsculas y el nombre que asigno a las constantes está completamente en mayúsculas, esto son convenios de escritura del lenguaje Java y tu puedes seguir tu propio estilo de código pero es interesante hacer uso del convenio porque facilita la lectura y comprensión del código yen caso de trabajar con otras personas se es mas productivo. En este módulo, un poco mas adelante, hablaremos en mayor profundidad de esta cuestión.

