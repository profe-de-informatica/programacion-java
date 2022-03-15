# Funciones útiles para el aula

Cuando hemos creado nuestro primer programa hemos utilizado una función que muestra texto en una línea por pantalla. Voy a recoger en este apartado algunas funciones de la biblioteca de Java (API) que pueden resultarnos de utilidad para los programas que realicemos en el aula:

|Comando|Acción|
|:--:|:--:|
|System.out.println("Texto");|Escribe un texto y salta a la siguiente línea|
|System.out.print("Texto");|Escribe un texto y permanece en la línea|
|BufferedReader br = new BufferedReader(new InputStreamReader(System.in));</br>int lado = Integer.parseInt( br.readLine() );|Nos permite almacenar en una variable lo que introduzcan en consola|
|Math.PI|Equivale a pi|
|Math.E|Equivale a e|
|Math.pow(base, exponente);|Eleva la base al exponente|
|Math.sqrt(número);|Devuelve la raíz cuadrada positiva del número|

En los siguientes capítulos haremos haciendo uso de estas útiles funciones que procuraré ir introduciendo poco a poco pero me ha parecido interesante mostrar un pequeño adelanto.

