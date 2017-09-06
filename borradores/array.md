# Arrays en JavaScript

Un array es un tipo especial de variable que funciona como contenedor de multiples variables.

Existen arrays unidimensionales y bidimensionales.

Veamos un ejemplo de un array:
```
+---------+---------+---------+--------+--------+---------+---------+--------+
|    0    |    1    |    2    |    3   |    4   |    5    |    6    |    7   |
|   pera  | manzana | cambur  |  piña  |  fresa | guayaba | guanaba |  limon |
+---------+---------+---------+--------+--------+---------+---------+--------+
```
El array es tambien llamado *lista ordenado*, y es porque se encuentra ordenado a traves de un numero entero el cual se le asigna a cada variable que vamos agregando, podriamos decir que la variable agregada es el nombre, y el numero es el apellido.

2 - cambur
6 - guanaba
8 - no existe.

Este apellido es llamado *indice* y comienza a contar desde el cero, es decir, si tenemos 8 variables guardadas en nuestro array la ultima tendra el indice numero 7, por tanto para obtener la cantidad de elementos en un array diremos que es **longitud del array -1** o visto en notacion matematica **n -1**.

En nuestro caso tenemos 8 frutas, si tratamos de acceder al puesto 8 para buscar el limon nos daria error, porque este esta en la posicion 8-1, es decir la 7.

Un array nos da el beneficio de guardar listas de variables en un solo lugar, permitiendonos asi:
- Relacionar el contenido.
- Ordenarlo.
- Separarlos en otros arrays mas pequeños.
- 

Ahora veamos como declaramos y le asignamos un valor a un array:
