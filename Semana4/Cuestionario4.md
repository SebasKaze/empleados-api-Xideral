# Review Questions
En esta seccion se encuentran las respuestas de las preguntas del **Capitulo 3** con su respectiva explicación
## Pregunta 1
**Respuesta:**  F


**Explicacion.**

La línea 5 intenta asignar la suma de una variable int y 1  directamente a una variable String. Esto provoca un error de compilacion


## Pregunta 2
**Respuesta:**  C,E,F


**Explicacion.**

-C intenta instanciar un arreglo con beans lo cual no es valido
-E,F Se debe de declarar el tamaño de al menos la primer dimension

## Pregunta 3
**Respuesta:**  A,C,D


**Explicacion.**

Estas son las opciones validas que el compilador acepta, no existe el dia 40, 2023-02-29 no es bisiesto y MountEnum no esta en Java

## Pregunta 4
**Respuesta:**  A,C,D


**Explicacion.**

s apunta al StringPool y t es un objeto nuevo, cuando se usa equals se compara el valor, t.intern() extrae la referencia directa del pool y "hello" se compara con lo que hay en el pool

## Pregunta 5
**Respuesta:**  B


**Explicacion.**

Es el orden correcto en el que se van insertando las cadenas de texto, que es de izquierda a derecha

## Pregunta 6
**Respuesta:**  C


**Explicacion.**

- Math.round() devuelve un long
- Math.random() devuelve un double

## Pregunta 7
**Respuesta:**  A,E


**Explicacion.**

Al convertir al formato universal UTC estan 6 horas de diferencia

## Pregunta 8
**Respuesta:**  A,B,F


**Explicacion.**

Son estas opciones las que extraen correctamente el 5

## Pregunta 9
**Respuesta:**  A,C,F


**Explicacion.**

Los arreglos siempre inician desde el índice 0. Al comparar dos arreglos distintos con .equals(), únicamente se verificará si son el mismo objeto en memoria.

## Pregunta 10
**Respuesta:**  A


**Explicacion.**

No genera ningun error, todos los tipos de datos son correctos

## Pregunta 11
**Respuesta:**  E


**Explicacion.**

La clase LocalDate solo maneja componentes de fecha, no tiene funciones de manejo de tiempo, esto genera un error

## Pregunta 12
**Respuesta:**  A,D,E


**Explicacion.**

indent(1) anade un espacio al frente y un salto de linea, stripLeading() elimina el espacio pero deja el salto de linea, cuando se extrae "12" en la segunda un espacio en blanco y en la tercera "78"

## Pregunta 13
**Respuesta:**  B


**Explicacion.**

Las variables String son objetos inmutables. Pero la clase StringBuilder es mutable, por lo que roar2.append("!!!") si se agrega al objeto

## Pregunta 14
  **Respuesta:**  A,F


**Explicacion.**

La clase Instant sirve para representar una estampa global de tiempo. Puede extraerse usando el método estático Instant.now() o desglosando una clase que cuente con todos los datos del calendario de zona

## Pregunta 15
**Respuesta:**  C,F


**Explicacion.**

Tras emplear Arrays.sort(), los elementos quedan ordenados numéricamente y de acuerdo con su valor alfabético, dejando el arreglo como [123, PIG, pig]. 

## Pregunta 16
**Respuesta:**  A,B,G


**Explicacion.**

La variable inicial base mide 11 caracteres. Al llamar indent(2), se agregan dos espacios iniciales para cada uno de los dos renglones que separaba el salto de línea y corrobora el espaciado final, saltando la longitud total a 16. El método translateEscapes(), en cambio, es capaz de interpretar secuencias sueltas para encoger y traducir \\t (dos caracteres físicos en la cadena base) transformándolos en una simple tabulación (un carácter lógico), lo que reduce la cadena a solo 10 espacios

## Pregunta 17
**Respuesta:**  A,G


**Explicacion.**

.subtring va de un indice inicial al siguiente, si se utiliza el mismo manda una excepcion.

## Pregunta 18
**Respuesta:**  C,F


**Explicacion.**

s1 es creado empleando bloques de texto """. Los métodos como .toUpperCase(), .trim() o .substring() arrojan valores desechados porque no se encuentran reasignados a nada. Únicamente la línea donde se suma "two" altera exitosamente la asignación a "purrtwo"
s2 se edifica mediante múltiples concatenaciones sumadas en el tiempo de ejecución

## Pregunta 19
**Respuesta:**  A,B,D


**Explicacion.**

El comparador compare(s1, s2) saca un valor positivo porque el carácter 'P' del primer arreglo se evalúa numéricamente por encima de la 'L' (de Llama). El método mismatch(s1, s2) marca un número entero positivo (1) dictando el lugar del primer índice exacto que no coincidió en ambas listas

## Pregunta 20
**Respuesta:**  A,D


**Explicacion.**

Se configura el tiempo a la 1:30 AM durante un día designado con cambio automático de ahorro diurno. Si se añade un lapso físico de 1 hora con plus(1, ChronoUnit.HOURS), los relojes brincan su marcación y se estampan sobre las 3:30 AM.

## Pregunta 21
**Respuesta:**  A,C


**Explicacion.**

La opción A invierte a través de reverse() directamente el StringBuilder cambiando el texto "Java" por "avaJ". La opción C hace una concatenación larga ("JavavaJ$"), de la cual suprime limpiamente las primeras 3 letras ("Jav") usando delete(0, 3)

## Pregunta 22
**Respuesta:**  A


**Explicacion.**

Igual que pasa con las literales de texto, un objeto LocalDate es inmutable, así que cualquier método que modifique o altere su temporalidad generará objetos enteramente desacoplados. Al no tener variables destinadas para albergar a los objetos construidos en date.plusDays(2) ni en date.plusYears(3), ambos desaparecen y la fecha prístina se resguarda bajo la variable principal inalterada, arrojando "2022 APRIL 30"
