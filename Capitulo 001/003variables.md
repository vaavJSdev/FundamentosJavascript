# Variables y Constantes en JavaScript

Antes de seguir te sugiero una web para probrar tu codigo JavaScript y ver la ejecucion del mismo, es decir, ver paso a paso como se ejecuta cada linea de codigo:

[editor](http://www.pythontutor.com/visualize.html#mode=edit)

Ahora sigamos:

En JavaScript deciamos que las variables eran dinamicas y debilmente tipadas pero...

## ¿Que es una variable?:

> Una variable es un espacio de memoria reservado para almacenar un valor que corresponde a determinado tipo de dato. Este valor puede cambiar, y segun el tipo de dato contenido le asignara un tipo a la variable que le contiendo.
> De manera mas sencilla, *una variable es un contenedor de un valor que puede variar*.

Ahora veamos que es una constante

> Una constante al igual que la variable es un espacio de memoria reservado para almacenar un valor, la unica diferencia es que este no podra ser modificado durante la ejecución del codigo, una vez asignado un valor, este se mantendra hasta que el codigo finalice su ejecucion.
> De manera mas sencilla, *una constante es un contenedor de un valor que no puede variar*.

## ¿Como declarar variables en JavaScript?

**Declarar** es presentarle a tu codigo las variables que deseas utilizar y se hace de la siguiente manera:

```
palabraReservada nombreDeLaVariable;
```

Veamos algunos ejemplos, *abre tu consola y comenzemos*.

Escribre lo siguiente:


```javascript
var javascript;
```

# Asignando valores en JavaScript

Para asignarle un valor a una variable utilizamos el siguiente operador:

```
 =
```
Generalmente para nosotros puede significar es igual, pero este es otro operador, de ahora en adelante significara **asignar**

Veamos un ejemplo:

```javascript

var numero = 5 // Le asigno 5 a numero, ahora numero contiene el valor 5

var hola = "Hola, buen dia" // Le asigno Hola, buen dia a hola, ahora hola contiene el valor Hola, buen dia

var frutas = [pera,manzana,naranja] // Le asigno a frutas el arreglo que contiene el valor [pera,manzana,naranja]

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

**Notamos que**:

1. Se coloca la *palabra reserverda* en la izquierda de la *sentencia*.

> Una palabra reservada son terminos que utiliza el lenguaje para acceder a funciones especificas, debemos evitar declarar variables que tengan el mismo nombre, ya que el funcionamiento podria fallar, o por el contrario podriamos *opacar* las parabras reservadas.

2. Escribimos el nombre de la variable, *curso* en este caso.

> - No se puede empezar el nombre con un numero -> 5Casas = "La roja, la azul, la verde, la amarilla, la naranja"
> - Ni con caracteres especiales %laVariable , /numero, )(otroNumero.
> - Podemos comenzar nuestro nombre de variable unicamente con estos dos caracteres especiales: como
>     - **_** guion bajo.
>     - **$** signo de dolar.
>     - **az-Az** Letras en mayusculas y minisculas de la a(A) hasta la z(Z)
> - Entonces el nombre de la variable puede ser: galactico, elmejor123, juan25, numeroEspecial, PrImErNuMeRo, _persona, $persona.
> - Como convenio se utiliza el nombre con la primera letra en mayuscula para designar un Constructor.
> - Y para atributos privador un **_** guion bajo, ya que en javascript no hay propiedades privadas (profundizado mas adelante).

> - El nombre de la variable es para **entendimiento humano**, javascript solo buscara en su memoria los datos, asi que busquemos:
>     - Un buen nombre que de mucha más información.
>     - Usar nombres descriptivos y claros. 
>     - Legibles y evitar codificaciones complejas.
>     - utilicemos camelCase, es decir la primera palabra con toda en minuscula y la siguiente con la primera en mayuscula, simulando las jorobas de un camello: primerNumero, segundoNumero, mensajeInicialUsuario, mensajeInicialAdministrador

3. Colocamos el operador de *asignacion*.

> Le asignaremos lo que este a la derecha de este operador a la variable *curso*

4. Colocamos el valor, en este caso usamos comillas dobles ("") por ser de tipo *string* el valor que asignaremos.

> Asignaremos el valor "JavaScript" a la variable curso, ahora esta sera de tipo *string*

5. Agregamos un **;** al final, esto ocurre porque javascript evalua cada linea de codigo que termine en **;** punto y coma.

## Practiquemos un poco mas:

1. Un vendedor desea crear variables en un sistema para guardar el *dinero total* de su cuenta, el *dinero invertido en una compra* , el *dinero que ganara por una futura venta*, y para terminar el *numero de compras*, terminamos nuestro trabajo y nos retiramos. Al dia siguiente nos encontramos y nos dice que, su cuenta bajo a 43000, compro una nevera por 7000 y que piensa venderla en 15000.

Comenzamos leyendo y **analizando** la peticion del ejercicio, podemos identificar cuatro variables, procedemos a declararlas:

```javascript
var dineroTotal = 50000;
var dineroInvertidoCompra;
var dineroGanadoVenta;
var numeroCompras;
```
Luego nos dice una serie de operaciones que podriamos describir de esta manera:

```javascript
dineroTotal = dineroTotal - 7000;
dineroInvertidoCompra = 7000;
dineroGanadoVenta = 8000;
numeroCompras = 1;
```
