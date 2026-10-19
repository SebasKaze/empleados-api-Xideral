# Review Questions
Estas son las preguntas de los Modulos 1-6 de Moddle.


# Modulo 10 Colecciones y genéricos

## Pregunta 1 
**Respuesta:**  b

**Explicacion.**

Un Set es una interfaz que modela un conjunto matemático donde cada elemento debe ser único, por lo que no permite almacenar elementos duplicados

## Pregunta 2
**Respuesta:**  a


**Explicacion.**

ArrayList implementa la interfaz List, lo que significa que conserva el orden de inserción, almacena internamente sus datos en un arreglo redimensionable (solo de objetos, no tipos primitivos directamente) y permite guardar elementos repetidos o valores null.

## Pregunta 3
**Respuesta:**  c


**Explicacion.**

Tanto los arreglos tradicionales (Array) como ArrayList son estructuras basadas en índices que mantienen el orden de inserción y permiten almacenar el mismo valor múltiples veces en distintas posiciones

## Pregunta 4
**Respuesta:**  c


**Explicacion.**

Dictionary es una clase abstracta obsoleta de Java 1.0 anterior a la creación del Java Collections Framework, la cual fue reemplazada por la interfaz Map

## Pregunta 5
**Respuesta:**  d


**Explicacion.**

Existe un contrato estricto entre equals() y hashCode() que establece que si dos objetos son iguales según equals(), deben devolver obligatoriamente el mismo código hash; por ello, sobrescribir uno exige sobrescribir el otro para que colecciones como HashSet o HashMap funcionen correctamente.

## Pregunta 6
**Respuesta:**  a


**Explicacion.**

El método printList recorre e imprime los tres elementos en orden de inserción (Apple, Banana, Cherry), luego size() devuelve el total de elementos (3), contains("Banana") confirma que existe en la lista (true), y get(1) obtiene el segundo elemento (Banana, ya que los índices en Java empiezan en 0).


## Pregunta 7
**Respuesta:**  b


**Explicacion.**

El método Collections.sort() ordena los elementos de la lista en su orden natural ascendente (de menor a mayor), por lo que al imprimir la lista el resultado es [3, 5, 6, 8].

## Pregunta 8
**Respuesta:**  c,d


**Explicacion.**

Las opciones c y d definen correctamente clases genéricas utilizando parámetros de tipo entre paréntesis angulares: Box<T> permite trabajar con cualquier tipo de objeto (c), mientras que Box<T Number extends> utiliza un tipo genérico acotado (bounded type) que restringe T únicamente a Number o sus subclases (d).

## Pregunta 9
**Respuesta:**  b


**Explicacion.**

LinkedHashSet es la única implementación de Set (no permite duplicados) que combina una tabla hash con una lista doblemente enlazada para mantener el orden exacto de inserción, ofreciendo búsqueda e inserción en tiempo constante $O(1)$ e iteración rápida.

## Pregunta 10
**Respuesta:**  d


**Explicacion.**

La clase Item implementa correctamente la interfaz Comparable Item y su método compareTo() compara el atributo name (this.name.compareTo(other.name)), por lo que Collections.sort(items) ordenará e imprimirá la lista alfabéticamente por nombre (Apple: 3, Banana: 2, Cherry: 1).

## Pregunta 11
**Respuesta:**  a


**Explicacion.**

El método compareTo() ordena los objetos Item alfabéticamente usando this.name.compareTo(other.name), por lo que Collections.sort(items) mantiene el orden ascendente por nombre (Apple, Banana, Cherry) e imprime cada uno con su respectivo precio.

## Pregunta 12
**Respuesta:**  d


**Explicacion.**

En el método compare(Integer x, Integer y), al evaluar y.compareTo(x) en lugar de x.compareTo(y), se invierte el orden natural de comparación, por lo que Arrays.sort(primes, ms) ordena el arreglo de forma descendente (de mayor a menor).

## Pregunta 13
**Respuesta:** d


**Explicacion.**

En el método compare(Long a, Long b), al ejecutar b.compareTo(a) en lugar de a.compareTo(b) se invierte el orden natural de comparación, por lo que Arrays.sort(values, sort) ordena el arreglo de mayor a menor (orden descendente).

## Pregunta 14
  **Respuesta:**  c


**Explicacion.**

El método Collections.reverseOrder() devuelve un Comparator que invierte el orden natural ascendente de los objetos Integer, por lo que Arrays.sort() ordena el arreglo de mayor a menor (8, 6, 4, 1).

## Pregunta 15
**Respuesta:**  a


**Explicacion.**

El método Collections.reverseOrder() genera un Comparator que invierte el orden alfabético natural (de la Z a la A), por lo que Collections.sort(names, listNames) ordena la lista de forma descendente dando como resultado [Nadia, Mariel, Elo, Alejandro].

## Pregunta 16
**Respuesta:**  a,c

**Explicacion.**

Tanto la resta directa p1.getAge() - p2.getAge() (opción a) como el método Integer.compare(p1.getAge(), p2.getAge()) (opción c) devuelven un número negativo si la edad de p1 es menor, cero si son iguales y un número positivo si es mayor, logrando el orden ascendente por edad (a diferencia de la b que ordena por nombre y la d que ordena en orden descendente).

## Pregunta 17
**Respuesta:**  c


**Explicacion.**

La interfaz List tiene dos métodos sobrecargados remove(int index) y remove(Object o); al pasar un número entero primitivo (p.remove(1)), Java invoca el método que elimina por índice (la posición 1, donde está el primer 1) y no por valor ni todas sus apariciones, quedando [7, 5, 1].

## Pregunta 18
**Respuesta:**  c


**Explicacion.**

El código imprime true porque m1.name ("guitar") no es null, pero viola el contrato de Object.equals() ya que ni siquiera compara ambos objetos entre sí (incumpliendo las reglas de simetría, transitividad y el manejo de valores null, donde m2.equals(null) debe devolver false sin lanzar un NullPointerException).

## Pregunta 19
**Respuesta:**  c


**Explicacion.**

Aunque la clase MyKeys sobrescribe equals(), no sobrescribe hashCode(), por lo que hereda la implementación de Object que asigna un código hash distinto a cada instancia (m1, m2, m3 y m4); como HashMap evalúa primero el hashCode() antes de llamar a equals(), trata los cuatro objetos como claves completamente diferentes y guarda las 4 entradas.
