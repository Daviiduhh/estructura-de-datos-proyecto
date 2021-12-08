
# David Madrid Nápoles

## Proyecto Final - Portafolio de evidencia

## Estructura de datos I


#### Arreglo dinamico

Es un array de elementos que crece dinámicamente conforme los elementos se agregan o se eliminan.

El dinamismo de la longitud del arreglo es lo que lo convierte en un arreglo dinamico y no uno estatico de longitud definida.

**Metodos**
- agregar_inicio();
- agregar_inicio();
- size();

**Código** 

*[Repositorio](https://Repositorio.com/Daviiduhh/arreglo-dinamico)*

**Pruebas**

Insertar final

1

2

3

4

5

6

7

8

Insertados al inicio

-1

0

1

2

3

4

5

6

7

8

**Conclusiones**

Me pareció muy útil el uso de arreglos dinámicos, se me hizo muy útil y muy practico que para
aumentar el tamaño de este se pueda crear uno nuevo y pasarle la información del anterior.
Con esta modificación a los arreglos les da muchas posibilidades más, y se les pueden dar muchas
más aplicaciones.
Con el video fui fácil aplicar los mismos arreglos dinámicos, pero para strings.

**Referencias**

https://www.youtube.com/watch?v=tozHXqXI3Js, Memoria dinámica, Michel Davalos Boites.


#### Lista simplemente ligada

Una lista enlazada simple es una estructura de datos en la que cada elemento, generalmente nodos, apunta al siguiente. De este modo, teniendo la referencia del principio de la lista podemos acceder a todos los elementos de la misma.

- push_front();
- push_back();
- pop_front();
- pop_back();
- size();
- print();

**Código** 

*[Repositorio](https://Repositorio.com/Daviiduhh/lista-simplemente-ligada)*

**Prueba**

Tamano de lista

5

Eliminamos uno

Tamano de lista

4

Imprimimos lista

4

0

10

7

Destructor

Tamano de lista

0


**Conclusiones**

La manera de llevar las listas con ligas hacia el siguiente nodo se me hace interesante, ya que cada
nodo contiene dos datos, su valor y algo que lo vincula a siguiente nodo. Y el uso de -> se me hace
una manera muy interesante de como se lleva la implementación.

**Referencias**

https://www.youtube.com/watch?v=mmRfQxiP7b8, Lista Ligada (I), Michel Davalos Boites.
https://www.youtube.com/watch?v=wDDIH92zM90, Lista Ligada (II), Michel Davalos Boites.
https://www.youtube.com/watch?v=QcghZvKTFXA, Lista Ligada (III), Michel Davalos Boites.


#### Lista doblemente ligada

Es una estructura de datos que consiste en un conjunto de nodos enlazados secuencialmente. Cada nodo contiene tres campos, dos para los llamados enlaces, que son referencias al nodo siguiente y al anterior en la secuencia de nodos, y otro más para el almacenamiento de la información. 

**Metodos**

- empty();
- push_front();
- push_back();
- pop_front();
- pop_back();
- insert();
- erase();
- find();
- print();
- print_reverse();
- front();
- back();
- size();

**Código** 

*[Repositorio](https://Repositorio.com/Daviiduhh/lista-doblemente-ligada)*

**Prueba**

Agregados al inicio

3

2

1

Agregados al final

3

2

1

4

5

6

tamano

6

Busca 1 y cambia su valor por 3

Busca 0 y si no lo encuentra pone 0 al final

tamano

7

Lista

3

2

3

4

5

6

0


**Conclusiones**

Sentí la lista doblemente ligada fácil de usar, sobre todo al momento de borrar un nodo en un punto medio el uso del valor ant fue muy útil para moverse entre los nodos.
Mi mayor dificultad fue haber confundido la actividad 13 con la 12, implementé ya varios de los métodos de ese video, solo faltándome remove_if, no la pude implementar, pero de la actividad 12 fue ya bastante sencillo el método find, para que retornara el nullptr me apoyé de una bandera que se hace verdadera cuando encuentra un valor, y dentro de un condicional lo retorna.

**Referencias**

https://www.youtube.com/watch?v=5VQj3Ep2RMI&t=260s, Lista Doblemente Ligada (I), Michel Davalos Boites.
https://www.youtube.com/watch?v=DOjuBkDDAMs, Lista Doblemente Ligada (II), Michel Davalos Boites.

#### Listas circulares

Una lista circular es una lista lineal en la que el último nodo a punta al primero. Las listas circulares pueden ser simplemente enlazadas, o doblemente enlazadas.

**Metodos**

- insertarPrimero();
- insertarUltimo();
- vacia();
- imprimir();
- cantidad();
- borrar();

**Código** 

*[Repositorio](https://Repositorio.com/Daviiduhh/lista-circular)*

**Prueba**

Luego de insertar 4 nodos al principio

4-12-45-100-

Luego de insertar 2 nodos al final

4-12-45-100-250-7-

Cantidad de nodos:6

Luego de borrar el de la primer posicion:

12-45-100-250-7-

Luego de borrar el de la cuarta posicion:

12-45-100-7-

**Conclusiones**

La lista circular me resultó muy parecida a las otras listas enlazadas, con su diferencia de conectar el back con el front, sus aplicaciones pueden ser muy variadas, sobre todo cuando estas representen ciclos, ya que como todo ciclo, despues del final llega el inicio, como un reloj, reproductor de musica, etc.

**Referencias**

http://cidecame.uaeh.edu.mx/lcc/mapa/PROYECTO/libro9/listas_circulares.html#:~:text=Una%20lista%20circular%20es%20una,uno%20anterior%20y%20uno%20siguiente., listasCirculares, CIDECAME

http://conclase.net/c/edd/cap4, Listas circulares, conclase


#### Pila

Definición y características de la Estructura de Datos.

Describe los métodos u operaciones que tiene la Estructura de Datos.

**Código** 

*[Repositorio](https://Repositorio.com/Daviiduhh/pilas-y-colas)*

Prueba de la ejecución de el uso de la Estructura de Datos.

**Conclusiones**

**Referencias**


#### Cola

Definición y características de la Estructura de Datos.

Describe los métodos u operaciones que tiene la Estructura de Datos.

**Código** 

*[Repositorio](https://Repositorio.com/Daviiduhh/pilas-y-colas)*

Prueba de la ejecución de el uso de la Estructura de Datos.

**Conclusiones**

**Referencias**


#### Árbol binario de búsqueda

Definición y características de la Estructura de Datos.

Describe los métodos u operaciones que tiene la Estructura de Datos.

**Código** 

*[Repositorio](https://Repositorio.com/Daviiduhh/arbol-busqueda-binaria)*

Prueba de la ejecución de el uso de la Estructura de Datos.

**Conclusiones**

**Referencias**


#### Grafo

Definición y características de la Estructura de Datos.

Describe los métodos u operaciones que tiene la Estructura de Datos.

**Código** 

*[Repositorio](https://Repositorio.com/Daviiduhh/)*


Prueba de la ejecución de el uso de la Estructura de Datos.

**Conclusiones**

**Referencias**