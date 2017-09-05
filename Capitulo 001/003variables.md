# Variables y Constantes en JavaScript

Antes de seguir te sugiero una web para probrar tu codigo JavaScript y ver la ejecucion del mismo, es decir, ver paso a paso como se ejecuta cada linea de codigo:

[editor](http://www.pythontutor.com/visualize.html#mode=edit)

Ahora sigamos:

En JavaScript deciamos que las variables eran dinamicas y debilmente tipadas pero...

## ¿Que es una variable?:

> Una variable es un espacio de memoria reservado para almacenar un valor que corresponde a determinado tipo de dato. Este valor puede cambiar, y segun el tipo de dato contenido le asignara un tipo a la variable que le contiendo.

Ahora veamos que es una constante

> Una constante al igual que la variable es un espacio de memoria reservado para almacenar un valor, la unica diferencia es que este no podra ser modificado durante la ejecución del codigo, una vez asignado un valor, este se mantendra hasta que el codigo finalice su ejecucion.

## ¿Como declarar variables en JavaScript?

**Declarar** es presentarle a tu codigo las variables que deseas utilizar y se hace de la siguiente manera:

```
palabraReservada nombreDeLaVariable;
```

Veamos algunos ejemplos, *abre tu consola y comenzemos*

escribre lo siguiente:


```javascript
var javascript;
```



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


## Declaracion de Variables Usando ```var```

Para declarar una variable usando ```var``` basta solo escribir de esta manera:

```javascript
var curso;
```

Hemos declarado una variable llamada *curso*, ya javascript habra reservado espacio para guardar el valor que le asignemos.


Pobremos asignadle un valor: 

```javascript
curso = "JavaScript";

```

Le asignamos el valor de la derecha *javascript* a la variable de la izquierda *curso*.

Pobremos llamando nuestra variable, escribre:

```javascript
curso

// javascript
```

Ya tenemos nuestra declaracion de variable lista, incluso asignamos un valor.

Podriamos hacerlo todo en una unica *sentencia*:

```javascript
var curso = "JavaScript";
```

Notamos que:

- Se coloca la *palabra reserverda* en la izquierda de la *sentencia*.
- Escribimos el nombre de la variable *curso* en este caso.
- Colocamos el operador de *asignacion*.
- Colocamos el valor, usamos comillas dobles ("") para asignar en este caso por ser una cadena de texto.

## Declaración de variables usando ```let```

Seguimos la misma estructura general:

```javascript
let curso = "JavaScript";

```

## ¿Que diferencia este metodo del anterior?

Cuando usamos la palabra reservada ```let``` para declarar una variable esta tendra un *scope* local, a diferencia de ```var``` que es *global*

