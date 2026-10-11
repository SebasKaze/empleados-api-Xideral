# Review Questions
Estas son las preguntas del Modulo 6 de Moddle.


# Modulo 6 Modificadores, static e inicialización

## Pregunta 1 
**Respuesta:**  b

**Explicacion.**

El compilador importa java.lang explicitamente

## Pregunta 2
**Respuesta:**  b


**Explicacion.**

De igual manera que arriba el java.lang no es necesario importarlo

## Pregunta 3
**Respuesta:**  b


**Explicacion.**

El metodo al ser statico se incoa con el nombre de la clase sin necesidad de crear una instancia

## Pregunta 4
**Respuesta:**  b


**Explicacion.**

Un bloque estatico se ejecuta una sola vez, cuando la clase se inicializa por primer vez en la JVM

## Pregunta 5
**Respuesta:**  a


**Explicacion.**

Un protected es accesible desde la propia clase y desde el mismo paquete y subclases por ello se puede llamar desde cualquiera de estos

## Pregunta 6
**Respuesta:**  c,e


**Explicacion.**

Una clase puede ser estática y publica, las demás opciones no son para clases
## Pregunta 7
**Respuesta:**  b,c,f,h


**Explicacion.**

Una clase superior o padre puede ser, abstract, strictfp, static, public y final

## Pregunta 8
**Respuesta:**  c


**Explicacion.**

Una de las clases es private asi que no hereda ni es visible desde los hijos, cambiarlo a protected ya lo hace visible

## Pregunta 9
**Respuesta:**  a


**Explicacion.**

Un contructor puede ser private o pretected, como el main esta dentro de la clase hija si puede el contenedor privado y super

## Pregunta 10
**Respuesta:**  b


**Explicacion.**

Al inicializar la clase se ejecutan los inicializadores static en orden, y los bloques de instancia despues

## Pregunta 11
**Respuesta:**  c


**Explicacion.**

Muy similar al de arriba, al inicializar los constructores se ejecutan y después los bloques de codigo

## Pregunta 12
**Respuesta:**  d


**Explicacion.**

Cada new ejecuta primero el inicializador del campo y bloques de instancia, y después el cuerpo del constructor

## Pregunta 13
**Respuesta:**  c


**Explicacion.**

Muy similar al de arriba, ya que se ejecutan los bloques de instancia en orden y despues el cuerpo del constructor
