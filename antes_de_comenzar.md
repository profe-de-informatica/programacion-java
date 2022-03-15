# Antes de comenzar...

Anteriormente hemos comentado que Java es multiplataforma, es decir, un mismo programa puede ser ejecutado en varias arquitecturas o sistemas operativos sin mayor problema. Para conseguir esto es necesario aclarar algunas cuestiones:

*   Cuando trabajamos con código java los ficheros que contienen este código tienen la extensión .java Estos ficheros se llaman [ficheros fuente](https://es.wikipedia.org/wiki/C%C3%B3digo_fuente) y contienen texto plano, es decir, podemos abrirlos con cualquier editor de texto y ver su contenido.
*   Cuando un fichero .java es compilado se obtiene un fichero .class del mismo nombre. Si nuestro fichero fuente se llama Saluda.java su versión compilada se llamará Saluda.class y si tratamos de abrirlo con un editor de texto veremos que su contenido nos resulta ilegible

Resumiendo, si yo tengo un fichero fuente ¿qué debo hacer? compilarlo, y para ello necesitarás el [kit de desarrollo java (JDK)](https://es.wikipedia.org/wiki/Java_Development_Kit) que incluye el programa _javac_ que te permite compilar código. Y entonces, cuando ejecutamos un programa escrito en Java ¿qué estamos ejecutando? estamos ejecutando la versión compilada, es decir, el fichero .class ¿y qué programa interpreta estos ficheros? Lo interpreta un programa llamado _java_ que está contenido dentro de la [máquina virtual java (JRE)](https://es.wikipedia.org/wiki/Java_Runtime_Environment) (y que no hay que confundir con las máquinas virtuales que creamos con Virtual Box o similares)

## Pregunta Verdadero-Falso

<quiz name=""><question><p>Si quiero poder compilar un fichero .class debo instalar en mi equipo el kit de desarrollo java (JDK)</p><answer>Verdadero</answer><answer correct>Falso</answer><explanation>Los ficheros que se compilan son los ficheros .java y se compilarían con el programa javac contenido dentro del JDK</explnation></question><question><p>Si quiero ejecutar un programa Java del cual me han facilitado su fichero .class en la máquina en la que quiero ejecutarlo deberé tener instalada la máquina virtual java (JRE)</p><answer correct>Verdadero</answer><answer>Falso</answer><explanation></explanation></question><question><p>Si quiero ejecutar un programa Java del cual me han facilitado su fichero .class en la máquina en la que quiero ejecutarlo deberé tener instalada la máquina virtual java (JRE)</p><answer correct>Verdadero</answer><answer>Falso</answer><explanation>Lo que se ejecuta son ficheros .class y se hace con el programa java que está dentro del JRE</explanation></question></quiz>


Como trabajar en consola con comandos resulta tedioso lo que nosotros vamos a hacer para facilitarnos la vida va a ser trabajar con un [entorno de desarrollo integrado (IDE)](https://es.wikipedia.org/wiki/Entorno_de_desarrollo_integrado) que nos va a aportar soporte para el lenguaje java evitándonos tener que hacer uso de la consola y facilitándonos el aprendizaje al reseñarnos los errores sintácticos que cometamos.

Para ello he elegido trabajar con el IDE [Netbeans](https://netbeans.org/) que es libre, gratuito y tiene una gran comunidad de gente detrás desarrollándolo y utilizándolo. Entre otras opciones tendríamos el trabajar con [Eclipse](https://eclipse.org) o [IntelliJ IDEA](https://www.jetbrains.com/idea/), además de utilizar un editor de texto plano como bloc de notas, [notepad++](https://notepad-plus-plus.org/) o [Sublime Text](https://www.sublimetext.com/) y utilizar aparte el terminal.

Netbeans puede ser ejecutado en equipos con sistemas operativos Windows, Linux o Mac OS en sus diferentes arquitecturas de 32 o 64 bits. Para ahorrarnos el descargar por un lado JDK y por otro lado netbeans vamos a descargar e instalar una versión en la que ya viene todo. Para ello nos dirigiremos a [http://www.oracle.com/technetwork/articles/javase/jdk-netbeans-jsp-142931.html](http://www.oracle.com/technetwork/articles/javase/jdk-netbeans-jsp-142931.html) y descargaremos e instalaremos la versión que se corresponda a nuestro sistema operativo. A continuación he realizado 2 videotutoriales en los que muestro como proceder en Windows 7 y Ubuntu 16.04 LTS.

{% youtube %}https://youtu.be/DldsDzidscg?list=PL1ubUMkNBAR_98ka0Q393l3fpzSjo3FGq{% endyoutube %}

{% youtube %}https://youtu.be/gm2ICqWz4P8?list=PL1ubUMkNBAR_98ka0Q393l3fpzSjo3FGq{% endyoutube %}

Si queremos prescindir del uso de un entorno de desarrollo integrado podemos hacerlo, aunque yo no lo haría con mi alumnado excepto que trabajase con ellos en FP de la familia de Informática y comunicaciones. En el siguiente [enlace](https://es.wikibooks.org/wiki/Programaci%C3%B3n_en_Java/Primer_programa) tenemos un pequeño manual en el cual nos explican como hacer la compilación y ejecución a través del terminal (previamente habrá que haber instalado el JDK). No obstante a lo largo del curso haré uso de NetBeans en mis explicaciones y vídeos con el fin de facilitar la tarea a docentes y alumnado.

