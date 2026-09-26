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
**Respuesta:**  A,C


**Explicacion.**

La precedencia de operadores en Java evalúa desde los tipos con mayor prioridad a los de menor

## Pregunta 6
**Respuesta:**  F


**Explicacion.**

Sumar un entero con un `float` promueve toda la expresión a float. Un método con retorno declarado como `long` no puede devolver un `float` sin un casteo explícito.

## Pregunta 7
**Respuesta:**  D


**Explicacion.**

Los operadores cortocircuito (`&amp;&amp;`, `||`) omiten evaluar el lado derecho si la parte izquierda ya define el resultado, evitando que se ejecuten sus efectos secundarios.

## Pregunta 8
**Respuesta:**  A


**Explicacion.**

El post-incremento entrega el valor original antes de modificar la variable. Por su parte, la asignación compuesta (`-=`) realiza un casteo automático al tipo de la variable izquierda.

## Pregunta 9
**Respuesta:**  A,D,E


**Explicacion.**

El operador ternario evalúa únicamente la rama seleccionada por la condición lógica, y el **post-incremento** utiliza el valor actual de la variable antes de sumar 1.

## Pregunta 10
**Respuesta:**  G


**Explicacion.**

Toda operación aritmética binaria promueve sus operandos al menos a int, impidiendo asignar el resultado directamente a un short

## Pregunta 11
**Respuesta:** D  


**Explicacion.**

El operador módulo calcula el residuo de una división entera y respeta la precedencia estándar evaluándose de izquierda a derecha.

## Pregunta 12
**Respuesta:** D


**Explicacion.**

El post-incremento devuelve el valor original previo al cambio, mientras que el pre-decremento resta primero y devuelve el valor ya modificado.

## Pregunta 13
**Respuesta:** F


**Explicacion.**

Sigue la prioridad de operadores lógicos: la negación `!` se evalúa primero, seguida de la conjunción `&amp;&amp;` / `&amp;` y finalmente la disyunción.

---

## Pregunta 14
**Respuesta:**  B,E,G


**Explicacion.**

Se pueden comparar referencias de objetos con `!=`, las asignaciones devuelven el valor asignado y el operador ! es exclusivo de tipos booleanos.

## Pregunta 15
**Respuesta:**  D


**Explicacion.**

* El operador ternario (? :) es el único operador en Java que exige exactamente tres operandos (condición, expresión verdadera y expresión falsa).

## Pregunta 16
**Respuesta:**  B


**Explicacion.**

Incluir un literal long(3L) en una operación aritmética promueve todo el resultado a `long`, lo que invalida su asignación directa en una variable `int`

## Pregunta 17
**Respuesta:**  C,F


**Explicacion.**

Los operadores compuestos (`+=`, `*=`) reasignan el valor sobre la misma variable e incorporan la conversión de tipo explícita de forma implícita.

## Pregunta 18
**Respuesta:**  C


**Explicacion.**

Solo los paréntesis () permiten alterar de forma explícita el orden natural de precedencia en las expresiones.

## Pregunta 19
**Respuesta:**  B,F


**Explicacion.**

El pre-incremento modifica la variable antes de usarla, y superar el límite superior de un primitivo provoca un overflow hacia su valor negativo mínimo.

## Pregunta 20
**Respuesta:**  A,D,E


**Explicacion.**

Los operadores unarios poseen la mayor prioridad, el post-decremento devuelve el valor previo a la resta y ! no puede aplicarse a tipos numéricos.

## Pregunta 21
**Respuesta:**  E


**Explicacion.**

El complemento a nivel de bits \~ invierte la representación binaria de un número (equivale a `-x - 1`), y el pre-decremento descuenta 1 antes de la evaluación.
