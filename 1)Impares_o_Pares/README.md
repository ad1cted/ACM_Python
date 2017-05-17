## Impares o Pares

Existen Muchas versiones de pares ó impares, un juego qué
muchos competidores realizan para decidir muchas cosas,
por ejemplo, quien resolverá este problema. En una
variación de este juego los competidores comienzan
escogiendo ya sea pares ó impares. Después a la cuenta
de tres extiende una mano mostrando un número de dedos
que pueden ser de cero hasta cinco. Luego se suman la
cantidad escogida por los competidores. Si suma par la
persona que escogió par gana. Similarmente ocurre lo
mismo con la persona qué escoge impar, si suma impar
gana.
Juan y Miaría jugaron muchos juegos durante el día. En
cada juego Juan escogió pares (y en consecuencia Miaría
escogió impares). Durante los juegos se cada jugador anoto
en unas tarjetas el numero de dedos que mostró. Miaría
utilizo tarjetas azules, y Juan tarjetas rojas. El objetivo era el
de revisar los resultados posteriormente. Sin embargo al
final del día Juan hizo caer todas las tarjetas. Aún cuando
se podían separar por colores no podían ser colocadas en
orden original.
Dado un conjunto de números escritos en tarjetas rojas y
azules, usted debe escribir un programa para determinar el
mínimo de juegos que Miaría con certeza gano.

###Input
La entrada consiste de varios casos de prueba. La primera
línea de la prueba consiste en un entero N que representa
el numero de juegos (1 ? N ? 100). La segunda línea es un
caso de prueba que contiene N enteros X i , Indicando el
numero de dedos que mostró Miaría en cada uno de los
juegos (0 ? X i ?? 5, para 1 ? i ? N). La tercera línea contiene
N enteros Y i , el número de dedos que escogió Juan en cada
juego. (0 ? Y i ?? 5, para 1 ? i ? N). El fin de archivo se indica
con N = 0.
La entrada se debe leer de standard input (teclado).

###Output
Para cada caso de prueba su programa debe escribir en
una línea un numero de entero, indicando el mí mino
número de juegos que pudo haber ganado Miaría.
La salida debe ser standard output (pantalla).

####Ejemplo de Entrada
3
1 0 4
3 1 2
9
0 2 2 4 2 1 2 0 4
1 2 3 4 5 0 1 2 3
0

Salida para el ejemplo de Entrada

0
3