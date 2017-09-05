# Variables y Constantes en JavaScript

Antes de seguir te sugiero una web para probrar tu codigo JavaScript y ver la ejecucion del mismo, es decir, ver paso a paso como se ejecuta cada linea de codigo:

[editor](http://www.pythontutor.com/visualize.html#mode=edit)

Ahora sigamos:

En JavaScript deciamos que las variables eran dinamicas y debilmente tipadas pero...

## ¿Que es una variable?:

> Una variable es un espacio de memoria reservado para almacenar un valor que corresponde a determinado tipo de dato.
> Este valor puede cambiar, y segun el tipo de dato contenido le asignara un tipo a la variable que le contiendo.

Ahora veamos que es una constante

# Asignando valores en JavaScript

Para asignarle un valor a una variable utilizamos el siguiente operador:

```
 =
```
Generalmente para nosotros puede significar es igual, pero este es otro operador, de ahora en adelante significara **asignar**

Veamos un ejemplo

```
numero = 5 // Le asigno 5 a numero, ahora numero contiene el valor 5
hola = "Hola, buen dia" // Le asigno Hola, buen dia a hola, ahora hola contiene el valor Hola, buen dia
frutas = [pera,manzana,naranja] // Le asigno a frutas el arreglo que contiene el valor [pera,manzana,naranja]

```

## ¿Como declarar variables en JavaScript?

Declarar es presentarle a tu codigo las variables que deseas utilizar y lo podemos hacer de tres posibles maneras:

## usando var

Para declarar una variable usando ```var``` basta solo escribir de esta manera:

```
var curso = "JavaScript";
```

Notamos que:

- Se coloca la *palabra reserverda* en la izquierda de la *sentencia*.
- Escribimos el nombre de la variable *curso* en este caso.
- Colocamos el operador de *asignacion*.
- Colocamos el valor, usamos comillas dobles ("") para asignar en este caso por ser una cadena de texto.



## usando let


