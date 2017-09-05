#JavaScript: ¿Con que se come eso?

#¿Que es JavaScript?

Es un lenguaje de programacion que tiene las siguientes caracteristicas:

- **Unico hilo (single thread)**: Solo maneja un hilo de ejecución, es decir, se dedica a funcionar unicamente en la pagina que se esta ejecutando (mas adelante se profundizara este tema).

- **Lenguaje Concurrente sin bloqueo para peticiones Asincronas**: En español, ejecutar un bloque de codigo en un segundo plano mientras la pagina ejecuta otro codigo, sin interrumpirse.

- **Orientado a Objetos, Basado en Prototipos**: Manejaremos los fundamentos de la POO, tendremos objetos con atributos y metodos y en vez de *Clases*, usaremos prototipos, donde cada objeto puede ser un padre para crear muchos hijos y cada hijo modificarlo a nuestro antojo.

- **Funcional**: Podremos crear funciones puras, pasar funciones como argumentos, retornar y llamar funciones desde otras funciones, y crear objetos a partir de funciones.

- **Interpretado**: No necesitas compilarlo, pues se ejecuta dentro de los navegadores y estos con distintos motores se encargan de ejecutarlo.

- **Imperativo**: Ejecuta de manera secuencial las sentencias que estan en el codigo de arriba hacia abajo, utiliza condicionales y bucles para controlar el flujo del programa.

- **Debilmente tipado**: El tipo de variable se asocia al valor que se le asigna a la variable y no a ella, es decir no veremos:

    entero numero = 5;
    cadena mensaje = "JavaScript";

- **Tipado Dinamico**: Los valores de las variables pueden cambiar y traer consigo un cambio al tipo de variable:

    let numero = 5; // Es un numero
    numero = "Soy un cinco"; // Es una cadena de caracteres
    numero = {yo:"un cinco"} // Ahora un objeto.
    
-**1) Complementado por el DOM**: Como JavaScript reside en el navegador tendremos la capacidad de manipular todo el DOM(Document Object Model) a nuestro antojo, es decir, crear; modificar; y eliminar elementos HTML de nuestra web.

-**2) Complementado por el BOM**: Como JavaScript se ejecuta en un navegador tendremos la capacidad de abrir pestañas, mostrar ventanas emergentes, imprimir nuestra web, y acceder a las funciones que traiga el navegador.