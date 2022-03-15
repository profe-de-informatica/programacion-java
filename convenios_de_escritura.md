# Convenios de escritura

# Convenios de escritura

Cuando os hablé de "Constanes y variables" ya comenté algo sobre los convenios de escritura en Java. Vamos a recordarlo:

> Si eres observador/a te habrás dado cuenta de que los tipos básicos empiezan en minúscula mientras que los objetos comienzan en mayúsculas. Es probable que también te hayas percatado de que el nombre que asigno a las variables siempre comienza en minúsculas y el nombre que asigno a las constantes está completamente en mayúsculas, esto son convenios de escritura del lenguaje Java y tu puedes seguir tu propio estilo de código pero es interesante hacer uso del convenio porque facilita la lectura y comprensión del código yen caso de trabajar con otras personas se es mas productivo. En este módulo, un poco mas adelante, hablaremos en mayor profundidad de esta cuestión.
> 
> Pablo Ruiz Soria - Capítulo "Constantes y variables"

Hay que dejar claro que un [convenio](http://dle.rae.es/?id=AgBNpjI "Definición de convenio") no es mas que eso, un [convenio](https://es.wikipedia.org/wiki/Convenci%C3%B3n_de_nombres_(programaci%C3%B3n) "Convenio en wikipedia"). No estamos obligados a seguirlo pero si va a facilitarnos la labor a la hora de entender código de otras personas. Además, si acostumbramos a nuestro alumnado a seguirlo nos facilitará enormemente la tarea de corrección y detección de errores en su código. Voy a elaborar una pequeña tabla donde recoger algunas generalidades al respecto:

|Elemento|Explicación|Ejemplos|
|:--|:--|:--|
|Clases|Siempre el primer carácter en mayúsculas. Si son varias palabras, cada una de ellas separada por la primera mayúscula. Buscaremos nombres descriptivos pero no largos. Usaremos nombres en singular.|Pregunta</br>Respuesta</br>ClasificacionHistorica|
|Variables|Siempre el primer carácter en minúsculas. Si son varias palabras, cada una de ellas separada por la primera mayúscula. Buscaremos nombres descriptivos pero no largos. Usaremos nombres en singular.|pregunta</br>respuesta</br>clasificacionHistorica|
|Constantes|Todo en mayúsculas. Si son varias palabras, cada una de ellas separada por guión bajo (_). Buscaremos nombres descriptivos pero no largos. Usaremos nombres en singular.|PREGUNTA</br>RESPUESTA</br>CLASIFICACION_HISTORICA|
|Paquetes|En minúsculas. No es habitual que tengan varias palabras. Si son paquetes para web generalmente usan el dominio invertido.|com.trivinet.modelo</br>com.trivinet.util|
|Funciones y métodos|Siempre el primer caracter en minúsculas. Si son varias palabras, cada una de ellas separada por la primera mayúscula. Buscaremos nombres descriptivos pero no largos. Utilizaremos verbos.|obtenerPregunta(...)</br>borrarRespuesta(...)</br>establecerClasificacionHistorica(...)|
|Parámetros|Estableceremos 1 espacio en blanco tras la coma que separa los parámetros en una función para facilitar la lectura.|obtenerPregunta(int id, boolean activa)|
|Operadores|Estableceremos 1 espacio en blanco tras los mismos para facilitar la lectura.|a = b + c;</br>a == b|
|Paréntesis dentro de paréntesis|Cuando un paréntesis no sea el último procuraremos dejar un espacio en blanco para facilitar la lectura.|escribir( multiplicar(4, 5) );|
|Bloques de código|Todo el código dentro de un bloque (clase, método, condición, bucle, excepción,...) debe tener la misma identación|
|Longitud de las líneas|Evitaremos hacer líneas de longitud mayor a 80 caracteres (en Netbeans viene delimitado por una línea roja). Recordad que una sentencia, en Java, termina con un punto y coma, no con el fin de la línea.|


No me cansaré de insistir en que el compilador no comprueba que sigamos ningún convenio (ni que la lógica del programa sea correcta). El compilador únicamente va a comprobar que sintácticamente el código está escrito del modo adecuado.

