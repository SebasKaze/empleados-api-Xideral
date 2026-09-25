# Review Questions
En esta seccion se encuentran las respuestas de las preguntas del capitulo 1 con su respectiva explicacion
## Pregunta 1
**Respuesta:**  D,E


**Explicacion.**

Tanto la D como la E cumplen con lo necesario para compilar ya que si son parametros validos que puede tener main. 
Esto debido a que el main debe ser public, static y retornar un void

## Pregunta 2
**Respuesta:**  C,D,E


**Explicacion.**

En java se debe seguir una regla cuando se importan que es la siguiente. Paquetes (package), Importaciones (import) y luego clases (class).

## Pregunta 3
**Respuesta:**  A,E


**Explicacion.**

Tanto la A como E son validas ya que Bunny si es la definicion de la clase y bun es la variable que hace referencia al objeto creado

## Pregunta 4
**Respuesta:**  B, E, G


**Explicacion.**

Los identificadores validos pueden contener letras, numero y $ o _ pero no pueden iniciar con numero, ser palabras reservadas o unicamente _

## Pregunta 5
**Respuesta:**  A, D, F


**Explicacion.**

Primero la llamda al recolector es una sugerencia, puede o no correr. brownBear pierde la referencia en la linea 13 y polarbear aun tiene una referencia hasta que se pierde con browBear en la 13.

## Pregunta 6
**Respuesta:**  C


**Explicacion.**

Scope al estar dentro del while unicamente tiene acceso a distance, que es el parametro del metodo, path que se declaro dentro, water y twoHumps

## Pregunta 7
**Respuesta:**  C, E


**Explicacion.**

Dentro de un bloque de texto el contenido se tomo como un String plano. Lo que imprime # cup = 0 y tambien los espacios

## Pregunta 8
**Respuesta:**  B, D, E, H


**Explicacion.**

Var requiere una inicializacion con un tipo que el compilador pueda inferir explicictamente en esa misma linea.

## Pregunta 9
**Respuesta:**  E


**Explicacion.**

Las variables de clase e instancia de tipos de referencia se inicializan automaticamente con el valor por defecto null. Las locales no reciben valores por defecto y causan un error de compilacion

## Pregunta 10
**Respuesta:**  A, E, F


**Explicacion.**

Los guiones bajos _ en literales numericos son validos siempre que no esten al inicio, al final o a lado de un punto decimal

## Pregunta 11
**Respuesta:**  E


**Explicacion.**

Se pueden eliminar un total de 4 importaciones, las de java.lang y las de aquarium ya que vienen en el paquete

## Pregunta 12
**Respuesta:**  A,C,D


**Explicacion.**

A: No se pueden declarar multiples tipos de datos diferentes en una sola linea, C: No se pueden asignar valores por defecto a los parametros de un metodo y D: La variable fins ya esta fuera del alcance.

## Pregunta 13
**Respuesta:**  A,B,C


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

## Pregunta 22
**Respuesta:**  C,F,G


**Explicacion.**

Aunque A sea una asignacion correcta, no es el mismo nombre de amount por lo que daria error. Las demas opciones son validas al asignar

## Pregunta 23
**Respuesta:**  A,D


**Explicacion.**

La linea 3 la variable temp esta declarada como float, pero se le asigna 50.0 sin sufijo f por lo que da error de compilacion, en la linea 10 la varialbe depth fue declarada dentro un bucle for y esta fuera del alcance 
