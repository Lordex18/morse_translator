# morse_translator
A translator-encrypter from spanish to morse or viceversa

ENUNCIADO
El algoritmo de cifrado de Julio Cesar, también conocido como ROT-k, es un algoritmo
muy antiguo que algunos programas de Internet siguen usando para encriptar la
información transmitida. Se basa en sustituir cada carácter de una cadena de
caracteres por el carácter situado a distancia k de éste. Por ejemplo, si la cadena a
cifrar es ABCDE y k es 1, la cadena cifrada será BCDEF. Es decir, A->B, B->C, C->D, D->E, E->F.

El código Morse es un sistema de comunicación telegráfica que a través de impulsos
de diferentes longitudes nos permite transmitir un mensaje. A continuación, alfabeto
y dígitos con su respectivo código morse.

Se les ha solicitado implementar un buscador encriptador-morse, que busque en una
matriz formada por palabras en cada una de sus celdas, las palabras que conforman
una frase (de máximo 7 palabras). Se debe validar la existencia de la frase completa,
la cual se debe poder formar con palabras que se encuentran en la matriz de 20 x 20
(dicha matriz debe ser leída y/o generada), luego se debe encriptar y traducir a morse
combinando las dos técnicas antes explicadas de tal forma que:
1. Cuando el usuario digite una frase, primero validar que se puede formar con
las palabras que se encuentran guardadas en la matriz, en caso positivo, se
solicita un k mayor o igual a 3 y el programa debe encriptar la cadena y traducir
a código morse.
2. Cuando el usuario digite una frase en morse y un k mayor o igual a 3, el
programa debe desencriptar la cadena y traducirla al español, luego debe
verificar que se pueda formar con las palabras de la matriz.

INSTRUCCIONES Y CONDICIONES.
1. Tener en cuenta el alfabeto morse.
2. Cada símbolo del código morse de una misma palabra es separado por un solo
espacio y dos espacios para separar dos palabras.
3. Se debe mostrar al usuario tanto la frase encriptada y como en código Morse.
4. La interfaz debe ser muy amigable y visualmente agradable al usuario.
5. Solo usar matrices, vectores, operaciones con cadenas de caracteres.
6. Implementar funciones propias, no las que vienen por defecto Java para facilitarte la tarea.
