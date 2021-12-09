
# David Madrid Nápoles

## Proyecto Final - Portafolio de evidencia

## Estructura de datos I


### Arreglo dinamico

Es un array de elementos que crece dinámicamente conforme los elementos se agregan o se eliminan.

El dinamismo de la longitud del arreglo es lo que lo convierte en un arreglo dinamico y no uno estatico de longitud definida.

**Métodos**
- agregar_inicio();
- agregar_inicio();
- size();

**Código** 

*[Repositorio](https://github.com/Daviiduhh/arreglo-dinamico)*

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


### Lista simplemente ligada

Una lista enlazada simple es una estructura de datos en la que cada elemento, generalmente nodos, apunta al siguiente. De este modo, teniendo la referencia del principio de la lista podemos acceder a todos los elementos de la misma.

- push_front();
- push_back();
- pop_front();
- pop_back();
- size();
- print();

**Código** 

*[Repositorio](https://github.com/Daviiduhh/lista-simplemente-ligada)*

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


### Lista doblemente ligada

Es una estructura de datos que consiste en un conjunto de nodos enlazados secuencialmente. Cada nodo contiene tres campos, dos para los llamados enlaces, que son referencias al nodo siguiente y al anterior en la secuencia de nodos, y otro más para el almacenamiento de la información. 

**Métodos**

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

*[Repositorio](https://github.com/Daviiduhh/lista-doblemente-ligada)*

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

### Listas circulares

Una lista circular es una lista lineal en la que el último nodo a punta al primero. Las listas circulares pueden ser simplemente enlazadas, o doblemente enlazadas.

**Métodos**

- insertarPrimero();
- insertarUltimo();
- vacia();
- imprimir();
- cantidad();
- borrar();

**Código** 

*[Repositorio](https://github.com/Daviiduhh/lista-circular)*

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

http://cidecame.uaeh.edu.mx/lcc/mapa/PROYECTO/libro9/listas_circulares.html#:~:text=Una%20lista%20circular%20es%20una,uno%20anterior%20y%20uno%20siguiente, listasCirculares, CIDECAME

http://conclase.net/c/edd/cap4, Listas circulares, conclase


### Pila

Una pila (stack en inglés) es una lista ordenada o estructura de datos que permite almacenar y recuperar datos, siendo el modo de acceso a sus elementos de tipo LIFO, del inglés Last In, First Out.

**Métodos**

- push();
- pop();
- top();
- size();
- empty();

**Código** 

*[Repositorio](https://github.com/Daviiduhh/pilas-y-colas)*

**Prueba**

Se pushearon -1, 0, 1, 2, 3

-1

3

Eliminar por pop e imprime tamano

4


**Conclusiones**

La estructura de datos de tipo pila se me hizo interesante, sobre todo por su funcionamiento LIFO, esta estructura de datos puede ser implementado en varias implementaciones, por ejemplo en los automatas de pila estas son parte fundamental para su funcionamiento, y estos automatas pueden ser aplicados en muchisimas areas.

**Referencias**

https://www.youtube.com/watch?v=235yQq2P-wc&feature=emb_imp_woyt, Pila, Michel
Davalos Boites.

### Cola

Una cola es una estructura de datos, caracterizada por ser una secuencia de elementos en la que la operación de inserción push se realiza por un extremo y la operación de extracción pop por el otro. También se le llama estructura FIFO (del inglés First In First Out), debido a que el primer elemento en entrar será también el primero en salir.

**Métodos**

- push();
- pop();
- front();
- back();
- size();
- empty();

**Código** 

*[Repositorio](https://github.com/Daviiduhh/pilas-y-colas)*

**Prueba**

Se pushea 10, 9, 8, 7

Tamano

4

Imprime tope de la pila y se va desapilando

7

8

9

10

Tamano

0


**Conclusiones**

Las colas son estructuras de datos diseñadas para devolver los elementos ordenados tal como llegan. Este comportamiento FIFO es muy parecido a lo que podemos ver en varios procesos del dia a dia, como las filas de espera, la progrmacion estructurada, y la mayoria de los procesos que vemos.

**Referencias**

https://www.youtube.com/watch?v=hhsa8ENCZls, Cola, Michel
Davalos Boites.

### Árbol binario de búsqueda

La búsqueda en árboles binarios es un método de búsqueda simple, dinámico y eficiente considerado como uno de los fundamentales en Ciencia de la Computación.

**Métodos**

- crearNodo();
- insertar();
- preOrden();
- enOrden();
- postOrden();
- verArbol();

**Código** 

*[Repositorio](https://github.com/Daviiduhh/arbol-busqueda-binaria)*

**Prueba**

Numero de nodos del arbol:  5

 Numero del nodo 1: 1

 Numero del nodo 2: 2

 Numero del nodo 3: 3

 Numero del nodo 4: 4

 Numero del nodo 5: 5

 Mostrando ABB

            5

         4

      3

   2

1

 Recorridos del ABB

 En orden   :  1 2 3 4 5

 Pre Orden  :  1 2 3 4 5

 Post Orden :  5 4 3 2 1


**Conclusiones**

Los árboles de búsqueda binaria son una excelente opción para poder relizar busquedas de una manera fácil, optima, y veloz. Su aplicación puede ser en cualquier busqueda que se necesite relizar.

**Referencias**

https://es.wikipedia.org/wiki/%C3%81rbol_binario_de_b%C3%BAsqueda, Árbol binario de búsqueda, Wikipedia.

https://ccia.ugr.es/~jfv/ed1/tedi/cdrom/docs/arb_BB.htm, Joaquín Fernández Valdivia, ARBOLES BINARIOS DE BUSQUEDA.

### Grafo

Es un conjunto de objetos llamados vértices o nodos unidos por enlaces llamados aristas o arcos, que permiten representar relaciones binarias entre elementos de un conjunto.

**Métodos**

- repetido();
- empty();
- agregarNodo()

**Código** 

*[Repositorio](https://github.com/Daviiduhh/grafos)*


**Prueba**

1.-Ingresar nodos

2.-Mostrar grafo

3.-Salir

Elige una opcion-> 2

2

[('1', 10), ('3', 11)]

1

[('2', 10)]

3

[('2', 11), ('4', 12)]

4

[('3', 12)]


**Conclusiones**

Los grafos son estructuras muy amplias que pueden representar deversas situaciones o elementos. Resultan ser útiles en situaciones complejas, ya que se utilizan en estudios de ciencias exactas, ciencias sociales y aplicaciones informaticas.

**Referencias**

https://es.wikipedia.org/wiki/Grafo, Grafo, Wikipedia. 

https://www.grapheverywhere.com/que-son-los-grafos/, Qué son los grafos, GRAPH EVERYWHERE.