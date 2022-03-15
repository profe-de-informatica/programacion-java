# Static

Tenemos la posibilidad de crear **variables de clase** y **métodos de clase** haciendo uso de la palabra reservada _static_. Para ello haremos uso de la siguiente sintaxis para las variables de clase:

```java
static tipoVariable nombreVariable;
```

Y la siguiente sintaxis para los métodos de clase:

```java
static tipoDevuelvo nombreMetodo(parámetros) {  
    sentencias;  
}
```

En ocasiones nos puede interesar que una variable no esté asociada a un objeto sino que esté asociada a la clase, en ese momento es cuando nos interesa crear una variable de clase. Análogamente puede ocurrir con un método. Si en un momento dado nos interesa que el método esté asociado a la clase y no al objeto entonces debemos hacerlo estático, debemos hacer un método de clase.

Para acceder a una variable de clase debemos hacerlo con la sintaxis

```java
NombreDeLaClase.nombreVariable;
```

Y para acceder a un método de clase debemos hacerlo con la sintaxis

```java
NombreDeLaClase.nombreMetodo(parámetros);
```

Presta atención a que escribimos el nombre de la clase y no el nombre de ningún objeto.

