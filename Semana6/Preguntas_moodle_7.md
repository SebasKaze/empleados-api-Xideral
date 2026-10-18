# Review Questions
Estas son las preguntas de los Modulos 1-6 de Moddle.


# Modulo 7 Herencia y polimorfismo

## Pregunta 1 
**Respuesta:**  d

**Explicacion.**

La clase hija hereda el constructor del padre, por ello cuando se instancia manda a llamar al constructor del padre y despues del hijo

## Pregunta 2
**Respuesta:**  a,b


**Explicacion.**

Las dos opciones son validas para crear un objeto, ya en ambas la referencia es de tipo Dog

## Pregunta 3
**Respuesta:**  b


**Explicacion.**

Es valido ya que es posible ya que si es posible asignar a una subclase una referencia a la clase padre sin necesidad de un casteo

## Pregunta 4
**Respuesta:**  c


**Explicacion.**

Se manda a llamar al constructor del hijo a pesar que la referencia sea del padre

## Pregunta 5
**Respuesta:**  d


**Explicacion.**

La referencia es de su padre pero el objeto es un hijo, por ello cuando se manda a llamar al metodo es el del hijo

## Pregunta 6
**Respuesta:**  d


**Explicacion.**

Sucede algo muy similar que arriba, en este caso se crea un objeto con referencia del padre pero declaracion de hijo, cuando se manda a llamar a un metodo se llama al del hijo que en este caso sobreescribe al del padre


## Pregunta 7
**Respuesta:**  a


**Explicacion.**

El objeto apunta a un hijo, por eso cuando se hace un casteo a hijo es valido y el metodo es el del hijo

## Pregunta 8
**Respuesta:**  b


**Explicacion.**

Cada uno apunta a su clase, tanto padre como hijo a su respectiva clase por eso imprime la clase de la referencia

## Pregunta 9
**Respuesta:**  d


**Explicacion.**

Al cambiar la referencia del objeto padre al hijo este cambia su clase he imprime la del hijo

## Pregunta 10
**Respuesta:**  c


**Explicacion.**

Es el resultado despues de sobrescribir el metodo y cada uno muestra algo diferente

## Pregunta 11
**Respuesta:**  a


**Explicacion.**

Es el orden en como se van ejecutando los constructores, que empiezan del padre al hijo y al nieto

## Pregunta 12
**Respuesta:**  b 


**Explicacion.**

Es el orden correcto en el cual imprime, llama al constructor con un mensaje, y luego el del hijo

## Pregunta 13
**Respuesta:** 13


**Explicacion.**

El operador | en un print es un OR bit a bit esto siempre y cuando sea entre enteros.

## Pregunta 14
  **Respuesta:**  b


**Explicacion.**

El metodo del padre al ser protected el hijo no lo puede sobrescribir

## Pregunta 15
**Respuesta:**  a


**Explicacion.**

Al invocar a la clase de manda a llamar aquel con el constructor con mensaje, luego se invoca al hijo que manda a llamar al constructor del padre que no tiene parametros y luego el mensaje

## Pregunta 16
**Respuesta:**  b,c,e


**Explicacion.**

son las opciones validas cuando se inserta el codigo y no generan problemas en sobreescribir el metodo

## Pregunta 17
**Respuesta:**  c,d


**Explicacion.**

Son las maneras correctas de sobrescribir el metodo del padre

## Pregunta 18
**Respuesta:**  d


**Explicacion.**

No es posible sobrescribir el metodo cuando este es de un tipo diferente al del padre porque el return cambia

## Pregunta 19
**Respuesta:**  a,b,d 


**Explicacion.**

Son las opciones que mejor representan las relaciones entre clases

## Pregunta 20
**Respuesta:**  d


**Explicacion.**

Es la manera en la que se van llamando los metodos y como va saltando de un main a otro

## Pregunta 21
**Respuesta:**  a


**Explicacion.**

El compilador falla debido a que se intenta sobrescribir un metodo del padre que es public y cambiar a protected

## Pregunta 22
**Respuesta:**  c


**Explicacion.**

Es la forma correcta en como se van sobrescribiendo los metodos de una lista de objetos

## Pregunta 23
**Respuesta:**  b


**Explicacion.**

Es el orden correcto en como se van llamando los metodos dependiendo de sus parametros

## Pregunta 24
**Respuesta:**  c


**Explicacion.**

Esa es la respuesta debido a que la variable del padre la sobrescribe el hijo, entonces es la misma variable

## Pregunta 25
**Respuesta:**  a

**Explicacion.**

Es la respuesta que mejor ejemplifica la relacion entre las clases

## Pregunta 26
**Respuesta:**  d


**Explicacion.**

El compilador falla porque cuando se instancia el objeto hijo este lleva datos, tanto el padre como el hijo tienen constructores que reciben el mismo valor, el compilador no sabe a cual ir y falla

## Pregunta 27
**Respuesta:**  f


**Explicacion.**

Es el orden correcto en como se van llamando los constructores

## Pregunta 28
**Respuesta:**  a


**Explicacion.**

Es el orden en como se van llamando los cosntructores, el cual empieza desde el padre y va bajando

## Pregunta 29
**Respuesta:**  d


**Explicacion.**

Son las opciones correctas para que se vayan mostrando los valores que pide

## Pregunta 30
**Respuesta:**  e


**Explicacion.**

No es posible haceer un downcast de un objeto padre hacia un hijo

## Pregunta 31
**Respuesta:**  b,d,e


**Explicacion.**

Son las opciones validas para reasignar una clase hija 

## Pregunta 32
**Respuesta:**  c


**Explicacion.**

No es posible hacer un cast de un objeto a String porque no tienen relacion de herencia

## Pregunta 33
**Respuesta:**  d


**Explicacion.**

El programa corre sin una salida porque no hay ningun print en el codigo

## Pregunta 34
**Respuesta:**  b


**Explicacion.**

El resultado es tru porque instanceof pregunta si es una instancia de cada tipo y si corresponde

## Pregunta 35
**Respuesta:**  g


**Explicacion.**

Al no craerse un campo a las demas operaciones con esta no pueden hacerce

## Pregunta 36
**Respuesta:**  b,d


**Explicacion.**

Son las 2 maneras correctas de invocar a la variable del padre

## Pregunta 37
**Respuesta:** a,b


**Explicacion.**

Son los 5 metodos que se meten y si pueden compilar

## Pregunta 38
  **Respuesta:**  c,d,f


**Explicacion.**

Son todas las lineas que fallan al compilar 

## Pregunta 39
**Respuesta:**  c


**Explicacion.**

Al el objeto nieto de tipo Abuelo los metodos los toma de nieto pero cuando se hace un llamado a atributos lo toma del abuelo

## Pregunta 40
**Respuesta:**  a


**Explicacion.**

Al ser private no se hereda ni sobrescribe por ello al ser la referencia del padre se manda a llamar a ese metodo
