# Review Questions
En esta seccion se encuentran las respuestas de las preguntas del **Capitulo 3** con su respectiva explicación
## Pregunta 1
**Respuesta:**  A,B,C,E,F,G


**Explicacion.**

Switch permite el uso de tipos primitivos y sus envolturas. Los que no estan permitidos son los long, double,float y boolean

## Pregunta 2
**Respuesta:**  B


**Explicacion.**

Al evaluar la expresión entra al primer if, el segundo es falso y salta al else del segundo, como el primer if si entro no pasa al else final.

## Pregunta 3
**Respuesta:**  A,D,F,H


**Explicacion.**

For-each acepta arreglos, pueden ser de cualquier dimension, o objetos cuya clase implemente una interfaz

## Pregunta 4
**Respuesta:**  F


**Explicacion.**

Switch necesita un default para todos los casos en donde no aplique, por ello da un error de compilacion

## Pregunta 5
**Respuesta:**  E


**Explicacion.**

Da un error de compilación en el segundo for, debido a que antes del print hay un continue que fuerza la siguiente iteración, pero el print se vuelve en codigo inalcanzable

## Pregunta 6
**Respuesta:**  C,D,E


**Explicacion.**

C es correcta porque la condición de un bucle for se evalúa antes de entrar por primera vez al bloque.

D es correcta porque una switch expression que retorna un valor basado en un String requiere de un bloque default para ser exhaustiva.

E es correcta porque los bucles do/while garantizan la ejecución de su cuerpo al menos una vez (la evaluación es al final).

## Pregunta 7
**Respuesta:**  B,D


**Explicacion.**

El primero inicializa correctamente el for y hace un incremento ascendente y el otro unos descendente. C podría ser, pero no se puede inicializar con un tipo de dato mas de 2 veces variables en un for

## Pregunta 8
**Respuesta:**  G


**Explicacion.**

Hay 2 errores, el primero en la linea 36 por un error de alcance y en la 38 por el default, no existe para un if. 

## Pregunta 9
**Respuesta:**  B,C,E


**Explicacion.**

Son las opciones en donde se interrumpe el bucle en el momento exacto para que el contador valga 2.

## Pregunta 10
**Respuesta:**  D


**Explicacion.**

El codigo tiene 3 fallas; Línea 15: Se usa continue en un switch, Línea 18: Como no es un final no se evalúa en tiempo de compilación, Línea 19: se usa enum cuando lo que se evalúa es un int 

## Pregunta 11
**Respuesta:**  A


**Explicacion.**

La expresión switch evalúa a (que es Animal.MAMMAL). Se produce un match exitoso en case MAMMAL -> 3;. El tipo de retorno implícito (el entero 3) es auto-promovido al tipo primitivo declarado como receptor, es decir a long. La salida estándar imprime "3".

## Pregunta 12
**Respuesta:**  C


**Explicacion.**

Al terminar las operaciones del bucle este imprime 23

## Pregunta 13
**Respuesta:**  G


**Explicacion.**

El codigo no compila porque la condicion no esta entre parentesis

## Pregunta 14
  **Respuesta:**  B,D,F


**Explicacion.**

Una vez definida var se queda con ese tipo de dato en el bucle

## Pregunta 15
**Respuesta:**  F


**Explicacion.**

El código tiene un error de sintaxis y no compila. La sentencia múltiple case 'B': 'C': es sintácticamente inválida.

## Pregunta 16
**Respuesta:**  A,B,D


**Explicacion.**

La opción A usa el pre-decremento (--q) empezando desde el valor 5 de tamaño, por lo que el primer elemento evaluado es el índice 4 (el final) hasta llegar a salir. La opción B usa un bucle clásico válido empezando en length - 1 decreciendo hasta 0. La opción D es más truculenta con sus condicionales, pero funcionalmente idéntica a la B, y también recorre el índice en cuenta regresiva hacia el 0.

## Pregunta 17
**Respuesta:**  B,E


**Explicacion.**

Al ejecutar las condiciones y los incrementos se llega a que participants = 10, animals = 3 y performers = 3

## Pregunta 18
**Respuesta:**  C,E


**Explicacion.**

La coincidencia de patrones con un if se implementa fundamentalmente utilizando el operador instanceof.

## Pregunta 19
**Respuesta:**  E


**Explicacion.**

La variable snake se declara adentro del bloque do {}. Esto significa que su scope se muere una vez que el compilador pasa la llave de cierre }

## Pregunta 20
**Respuesta:**  A,E


**Explicacion.**

Ambas opciones interrumpen el bucle do while sin que se vuelva un bucle infinito.

## Pregunta 21
**Respuesta:**  E


**Explicacion.**

Hay 4 errores.
-Una expresión switch en Java no evalúa tipos de datos mayores como Long ni long.
-El caso 10 -> {"Jane"} es un bloque de código y está obligado a usar la palabra clave yield "Jane";.
-El caso 20 cierra su bloque con punto y coma {...};, lo cual es un error sintáctico (las llaves de un bloque case no llevan punto y coma final).
-El caso 30 aparece doble (case 30 ->). Las etiquetas duplicadas en un mismo switch ocasionan errores

## Pregunta 22
**Respuesta:**  E


**Explicacion.**

Primero se evalúa el caso base del switch que es 5 y luego entra el while que imprime 2 y 1

## Pregunta 23
**Respuesta:**  F


**Explicacion.**

El codigo no compila hay un else if despues de otro else, se necesita un if antes.

## Pregunta 24
**Respuesta:**  G


**Explicacion.**

El bucle define la sintaxis for(var friend in friends). Esto no existe en Java, pero si en otros lenguajes

## Pregunta 25
**Respuesta:**  D


**Explicacion.**

Se evaluan las demas que no son "violin" porque no esta dentro de los casos 

## Pregunta 26
**Respuesta:**  F


**Explicacion.**

El bucle interno evalúa } while (r <= 1);. Pero, la variable r jamás se ve incrementada dentro del cuerpo del bloque do-while lo que da un bucle infinito

## Pregunta 27
**Respuesta:** F


**Explicacion.**

El if en el caso 2 no tiene un else, en el swtich todos los caminos deben de tener un final, si no fuese Frog no se sabe que es, por eso da error

## Pregunta 28
**Respuesta:**  F


**Explicacion.**

El compilador detecta que se estan haciendo 2 guppy por lo cual es una variable local duplicada

## Pregunta 29
**Respuesta:**  C


**Explicacion.**

Al preincrementar la variable y se hace el incremento antes de imprimir, por lo cual pasa a -1 hasta el 6
