# Review Questions
En esta seccion se encuentran las respuestas de las preguntas del capitulo 2 con su respectiva explicacion
## Pregunta 1
**Respuesta:**  A,D,G


**Explicacion.**

Primero == es un operador de igualdad y compara 2 valores booleanos, ! es un complemento logico y es para invertir valores booleanos y boolean que es el casting a booleano

## Pregunta 2
**Respuesta:**  A,B,D


**Explicacion.**

Cualquier tipo de operador byte, short o char pasa a int cuando se utiliza dentro de una oprecacion aritmetica binaria

## Pregunta 3
**Respuesta:**  B,C,D,F


**Explicacion.**

En la linea 4, la expresion 2 * ear multiplica un int(2) por un long(ear), lo que promueve el resultado a long, si no hace un casteo de long a int esto provoca un error.

## Pregunta 4
**Respuesta:**  B


**Explicacion.**

Los identificadores validos pueden contener letras, numero y $ o _ pero no pueden iniciar con numero, ser palabras reservadas o unicamente _

## Pregunta 5
**Respuesta:**  


**Explicacion.**

Primero la llamda al recolector es una sugerencia, puede o no correr. brownBear pierde la referencia en la linea 13 y polarbear aun tiene una referencia hasta que se pierde con browBear en la 13.

## Pregunta 6
**Respuesta:**  


**Explicacion.**

Scope al estar dentro del while unicamente tiene acceso a distance, que es el parametro del metodo, path que se declaro dentro, water y twoHumps

## Pregunta 7
**Respuesta:**  


**Explicacion.**

Dentro de un bloque de texto el contenido se tomo como un String plano. Lo que imprime # cup = 0 y tambien los espacios

## Pregunta 8
**Respuesta:**  


**Explicacion.**

Var requiere una inicializacion con un tipo que el compilador pueda inferir explicictamente en esa misma linea.

## Pregunta 9
**Respuesta:**  


**Explicacion.**

Las variables de clase e instancia de tipos de referencia se inicializan automaticamente con el valor por defecto null. Las locales no reciben valores por defecto y causan un error de compilacion

## Pregunta 10
**Respuesta:**  


**Explicacion.**

Los guiones bajos _ en literales numericos son validos siempre que no esten al inicio, al final o a lado de un punto decimal

## Pregunta 11
**Respuesta:**  


**Explicacion.**

Se pueden eliminar un total de 4 importaciones, las de java.lang y las de aquarium ya que vienen en el paquete

## Pregunta 12
**Respuesta:** 


**Explicacion.**

A: No se pueden declarar multiples tipos de datos diferentes en una sola linea, C: No se pueden asignar valores por defecto a los parametros de un metodo y D: La variable fins ya esta fuera del alcance.

## Pregunta 13
**Respuesta:** 


**Explicacion.**

Importar una clase unicamente por su nombre tiene prioridad sobre las importaciones con *.

## Pregunta 14
**Respuesta:**  A,B,D,E


**Explicacion.**

Linea 3: El literal 5L es un long y no se puede asignar directamente a un short sin casteo, Linea 4: es un literal double y no cabe en un int y Linea 6 y 7: numPets y numGrains son tipos primitivos

## Pregunta 15
**Respuesta:**  C,E,F


**Explicacion.**

El JVM puede reclamar memoria de otros objetos inaccesibles, tambien el recolector se lleva aquellos objetos sin referencias

## Pregunta 16
**Respuesta:**  A,D


**Explicacion.**

La barra invertida \ al final en un texto cancela el salto de linea y \s fuerza a conservar los espacions en blanco finales.

## Pregunta 17
**Respuesta:**  D,F,G


**Explicacion.**

Los boleanos se inicializan en false, las referencias a null y los flotantes a 0.0

## Pregunta 18
**Respuesta:**  B,C,F


**Explicacion.**

var no se permite en parametros de metodos ni en variables de instancias. Var tambien se determina en tiempo de compilacion por lo cual no puede cambiar en ejecucion

## Pregunta 19
**Respuesta:**  A,D


**Explicacion.**

Long.parseLong() devuelve un primitivo long y Long.valueOf() devuelve el envoltorio long.

## Pregunta 20
**Respuesta:**  C


**Explicacion.**

La linea 4 especifica un tipo de retorno void, convirtiendo a PoliceBox() en un metodo ordinario y no en un constructor. Asi cuando se construye un objeto las variables de instancia se van a valores por defecto

## Pregunta 21
**Respuesta:**  D


**Explicacion.**

Hay un orden de ejecucion que es primero main(), inicializadores de instancias y campos en orden de declaracion, constructor y el print final del main
