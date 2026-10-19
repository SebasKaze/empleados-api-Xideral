# Review Questions
Estas son las preguntas de los Modulos 1-6 de Moddle.


# Modulo 9 Excepciones

## Pregunta 1 
**Respuesta:**  e

**Explicacion.**

Throwable es la clase base directa de la cual heredan tanto los errores (Error) como las excepciones

## Pregunta 2
**Respuesta:**  c,d


**Explicacion.**

Las excepciones se dividen en verificadas (Checked), que el compilador te obliga a manejar en el código, y no verificadas (Unchecked), que ocurren durante la ejecución del programa sin requerir manejo obligatorio.

## Pregunta 3
**Respuesta:**  a


**Explicacion.**

Son las cinco palabras clave exclusivas en Java para gestionar excepciones: try (evalúa el código), catch (captura el fallo), finally (ejecuta código final siempre), throw (lanza una excepción) y throws (declara que un método puede lanzarla).

## Pregunta 4
**Respuesta:**  d


**Explicacion.**

La palabra clave throw se utiliza dentro del cuerpo de un método para generar y lanzar manualmente una instancia de excepción en un punto específico del código.

## Pregunta 5
**Respuesta:**  d


**Explicacion.**

La palabra clave throw permite al programador provocar una excepción de forma explícita en medio de la ejecución del código cuando se detecta una condición inválida o un error específico.

## Pregunta 6
**Respuesta:**  c


**Explicacion.**

En Java, throws se coloca en la firma del método para declarar qué excepciones pueden ocurrir sin ser manejadas dentro de él, mientras que throw es la instrucción que realmente lanza la excepción en el cuerpo del código.


## Pregunta 7
**Respuesta:**  b


**Explicacion.**

IOException es una excepción verificada (checked) porque el compilador obliga a manejar fallos de entrada/salida, mientras que NullPointerException hereda de RuntimeException, por lo que es no verificada (unchecked) y ocurre en tiempo de ejecución.

## Pregunta 8
**Respuesta:**  b


**Explicacion.**

El método mf() se ejecuta sin lanzar ninguna excepción, por lo que se imprime "A" dentro del try, se omite el bloque catch, se ejecuta el bloque finally imprimiendo "C", y el programa continúa normalmente imprimiendo "D"

## Pregunta 9
**Respuesta:**  c


**Explicacion.**

Al pasar 16 al método validarEdad, se cumple la condición de ser menor a 18 y se lanza la excepción IllegalArgumentException, interrumpiendo el método antes de imprimir "Edad válida." y pasando el control al bloque catch, el cual imprime el mensaje de error con e.getMessage().

## Pregunta 10
**Respuesta:**  b,d,e


**Explicacion.**

En Java es mala práctica usar excepciones de tiempo de ejecución (ArrayIndexOutOfBoundsException) para controlar el flujo normal de un bucle o intentar recuperarse de errores de lógica en lugar de validar los límites con código (b y e), así como capturar objetos de tipo Error (d), ya que representan fallos críticos e irrecuperables de la máquina virtual (JVM).

## Pregunta 11
**Respuesta:**  a,c


**Explicacion.**

Tanto IOException como InterruptedException heredan directamente de Exception (sin pasar por RuntimeException), por lo que son excepciones verificadas (checked) que el compilador te obliga a capturar con try-catch o declarar con throws, mientras que el resto son de tiempo de ejecución (unchecked).

## Pregunta 12
**Respuesta:**  a,c,d,e


**Explicacion.**

En Java, RuntimeException y todas sus subclases (ArrayIndexOutOfBoundsException, NumberFormatException e IllegalArgumentException) son excepciones no verificadas (unchecked), lo que significa que ocurren en tiempo de ejecución y el compilador no obliga a capturarlas ni a declararlas.

## Pregunta 13
**Respuesta:** a,c


**Explicacion.**

La operación 10 / 0 lanza una excepción ArithmeticException, por lo que se omite el resto del bloque try, entra únicamente en el primer bloque catch específico imprimiendo "Error: División por cero." y, finalmente, ejecuta siempre el bloque finally imprimiendo "Ejecución finalizada.".

## Pregunta 14
  **Respuesta:**  b


**Explicacion.**

El bloque try comienza imprimiendo "Running " e inmediatamente lanza la excepción (throw new Exception()), la cual es capturada en el bloque catch que imprime "Problem", y por último se ejecuta el bloque finally imprimiendo "Stopping".

## Pregunta 15
**Respuesta:**  b


**Explicacion.**

Al usar un bloque try-with-resources, primero se ejecuta el método resource.use() imprimiendo "Resource used " y, justo al terminar el bloque try, Java invoca automáticamente el método close() de la interfaz AutoCloseable, imprimiendo "Resource closed ".

## Pregunta 16
**Respuesta:**  a,d

**Explicacion.**

El método Math.random() genera un número aleatorio entre 0.0 y 1.0: si es mayor a 0.5, imprime "Before if clause" y lanza la excepción deteniendo el programa (opción a); pero si es menor o igual a 0.5, no lanza la excepción y continúa imprimiendo "Before if clause" seguido de "After if clause" (opción d).

## Pregunta 17
**Respuesta:**  a,d


**Explicacion.**

Como IOException es una excepción verificada (checked), el método doSomething() está obligado a declararla en su firma con throws IOException, y el método main() que lo invoca debe o bien propagarla añadiendo también throws IOException a su firma (opción a), o bien capturarla cambiando el argumento del bloque catch a IOException (opción d), ya que RuntimeException es unchecked y no requiere captura obligatoria.

## Pregunta 18
**Respuesta:**  a,b,d


**Explicacion.**

En Java es mala práctica usar excepciones de tiempo de ejecución (ArrayIndexOutOfBoundsException) para controlar el fin de un bucle o intentar recuperarse de errores de lógica en lugar de validar la longitud del arreglo con código (a y d), así como capturar objetos de tipo Error (b), ya que representan fallos graves e irrecuperables de la máquina virtual (JVM).

## Pregunta 19
**Respuesta:**  c


**Explicacion.**

El método go(x) se llama a sí mismo de forma recursiva sin ninguna condición de parada, lo que agota la memoria de la pila de llamadas (call stack) antes de que ocurra cualquier problema de índice (ya que x % 5 siempre da un índice válido entre 0 y 4), provocando un StackOverflowError.

## Pregunta 20
**Respuesta:**  a,c,e


**Explicacion.**

Al sobrescribir un método de una interfaz (usando implements, no extends), el método puede declarar la misma excepción verificada (IOException, opción a), una subclase más específica (FileNotFoundException hereda de IOException, opción c) o no declarar ninguna excepción (opción e), pero nunca una excepción verificada más general como Exception.

## Pregunta 21
**Respuesta:**  b


**Explicacion.**

El código no compila porque dentro del método a() se intenta capturar Exc1 (una excepción verificada o checked), pero ninguna línea dentro de su bloque try puede lanzarla, lo que genera un error de compilación por código inalcanzable (unreachable catch block)

## Pregunta 22
**Respuesta:**  a


**Explicacion.**

En Java, la primera expresión de un assert debe evaluar obligatoriamente a un valor boolean, pero aquí se utiliza el operador ternario ? : que devuelve un String en ambos casos ("x==6" o "x!=6"), provocando un error de compilación de tipos incompatibles.

