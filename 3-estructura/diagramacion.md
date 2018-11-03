
# UN VOCABULARIO VISUAL PARA DESCRIBIR ARQUITECTURA DE LA INFORMACIÓN Y DISEÑO DE INTERACCIÓN

## INTRODUCCIÓN
Los diagramas son una herramienta de trabajo muy importante para transmitir la arquitectura de información y el diseño de las interacciones en equipos de desarrollo Web. 
En resumen, lo que encontraremos en esta entrega son consideraciones en el desarrollo de diagramas, simbología básica para diagramas, conceptos de arquitectura de información y diseño de interacción y una entrega guía para el uso de estos elementos.

Para la elaboración de este escrito nos hemos basado en la lectura de Jesse James Garrett.

## CONSIDERACIONES INICIALES

Un vocabulario visual se utiliza para describir la arquitectura de información y diseño de interacción de una página web. Por lo que podríamos definirlo como explica el autor James Garrett, como un “conjunto de símbolos usado para describir algo”. Ese vocabulario descrito, es usado para dichas funciones de arqutectura e interacción, para describir la estructura y/o flujo de la experiencia que pueda tener el usuario de un sitio Web.

Estas diagramas o descripciones son usados por: 

- Inversionistas y gerentes de proyecto

- Productores de contenido

- Diseñadores visuales y de interfaces

- Tecnólogos

- Arquitectos de información y diseñadores de interfaz

Pero hay que tener en cuenta que, estas audiencias necesitan gran cantidad de detalles para hacer su trabajo, pero cada uno de ellos necesitan datos específicos, por lo que los demás son irrelevantes para sus necesidades.


## TRASFONDO CONCEPTUAL

Hay que subrayar que el diagrama se enfoca en lo que llamamos la macro-estructura. La tarea del arquitecto es determinar el nivel apropiado de detalle para lograr ese objetivo. Aún así, las diagramas deben enfatizar cómo el usuario fluye a través de tareas definidas. 

El vocabulario explicado brevemente, consta en lo siguiente: El sistema presenta al usuario unos caminos en los que se mueve a través de ellas mediante acciones, para que esas acciones el sistema genera unos resultados. Que sería la pantalla de la página web que desea el usuario.

## ELEMENTOS SIMPLES

La unidad básica de la experiencia de usuario en la Web es la pagina, la cual vamos a representar con un simple rectángulo. Aclaración importante, la pagina es una unidad de presentación no (necesariamente) una unidad de implementación (una página en tu diagrama puede presentar múltiples archivos HTML o unidades múltiples de código).

Además, tendremos archivos que no requerirán de navegación web, es decir, archivos que se entregan al usuario para que tenga la habilidad de descargarlos y usarlos por fuera del ambiente de navegación web, ejemplo: archivos de video, archivos PDF, entre otros. La simbología de los archivos es el icono con oreja de perro. 

![Elementos simples](https://github.com/DeustoPWEB2018/Elementos-de-la-UX/blob/87c275024379c29e4e84d888f0a9464facbd3a15/3-estructura/paginas_y_archivos.png)

También, se puede emplear la pila de páginas para indicar un grupo de páginas funcionalmente idénticas. Del mismo modo, una pila de documentos representa un grupo de documentos que reciben un tratamiento de navegación idénticos. Ejemplos: una colección de juegos descargables ó una librería de manuales de instrucciones en PDF.

Es bueno poner etiquetas en paginas y archivos para identificarlas, no es necesario que las mismas mantengan algún tipo de correlación, pero la idea es que sean únicos para cada pagina ó documento del diagrama así, se facilita la tarea de rastrear todas las paginas y documentos que contiene el diagrama.

## TODO DE UNA VEZ: CONJUNTOS RECURRENTES

Un CONJUNTO CONCURRENTE (representado por el semi-círulo) se  usa cuando la acción del usuario genera resultados múltiples simultáneos (al abrir una ventana pop-up mientras una página se carga en la ventana principal o mostrar una página mientras un documento es descargado).  

* ![Diagramacion1](/3-estructura/conjuntos.png)

## SEPARÁNDOLO: PUNTOS DE CONTINUACIÓN

A menudo a los arquitectos de la información las hojas de papel se les quedan pequeñas para diagramar. Para poder separar los diagramas en secciones fáciles, se usan los PUNTOS DE CONTINUACIÓN (paréntesis cuadrado) para unir los vacíos entre las páginas.

* ![Diagramacion2](/3-estructura/continuacion.png)

La orientación de los corchetes (horizontal y vertical) no tiene importancia, la elección es problema del juicio estético del arquitecto. 

## ELEMENTOS COMUNES: ÁREAS Y ÁREAS ITERACTIVAS

El elemento ÁREA (representado por un rectángulo con esquinas redondeadas) se utiliza a la hora de representar un grupo de páginas que comparten uno o más atributos comunes  (como aparecer una ventana pop-up, o tener un tratamiento único de diseño). Usar etiquetas para identificar estos atributos (como con los conectores) o también anotar fuera del documento si tenemos mucho que decir. 

* ![Diagramacion3](/3-estructura/areas.png)


Por otro lado si disponemos de un amplio catálogo con varios productos y cada producto tiene varias páginas asociadas a él usaremos un ÁREA ITERACTIVA (representado por una pila de rectángulos con esquinas redondeadas), de esta forma no perderemos el tiempo dibujando una instancia para cada producto. 

* ![Diagramacion4](/3-estructura/areasiteractivas.png)

## COMPONENTES RE-UTILIZABLES: ÁREAS DE FLUJO Y REFERENCIAS 

Algunos diseños requieren que una secuencia de pasos aparezca repetidamente en diferentes contextos mediante el diseño. Tal área re-utilizable es llamada un flujo, y es representada en el diagrama por dos elementos: el ÁREA DE FLUJO, que encierra el flujo mismo; y la REFERENCIA DE FLUJO, que sirve como marcador para el flujo en cada momento que se repite. Ambos elementos tienen la misma forma, un rectángulo con las esquinas cortadas o un octágono desconfigurado.

![Diagramacion5](/3-estructura/areasdeflujo.png)

También requieren de PUNTOS DE ENTRADA y PUNTOS DE SALIDA. Se ubican fuera del área de flujo, mientras los puntos de continuación, dentro del área de flujo, indican que el flujo abarca múltiples diagramas. El objetivo de ambos elementos es el mismo: permitir al arquitecto cortar el diagrama en páginas. La diferencia es que la REFERENCIA DE FLUJO puede ser usada en ambas modalidades; "continua desde" y "continua hasta", mientras que un punto de continuación sólo puede ser uno o otro. Si no necesitamos un elemento que tenga los dos roles, no necesitaremos usar el flujo. 

## CONCEPTOS BÁSICOS PARA ELEMENTOS CONDICIONALES

Las arquitecturas de información y diseños de interacción son reformados de manera dinámica. Esta reformación es lograda mediante lógica condicional, y los elementos restantes de este vocabulario son específicos a estructuras de lógica condicional. Un modelo conceptual básico sería el siguiente: 

-El sistema sigue la pista a uno o más atributos, estos atributos pueden ser particulares a: 

	-El usuario

	-La sesión

	-El contenido siendo accedido

	-Pueden existir en el mundo

-Los atributos tienen valores.

-Condición: asociación de un atributo con un valor particular.

-Las condiciones son evaluadas por el sistema para determinar si son verdaderas.  

Para minimizar la sobrecarga de las diagramas, estas condiciones son típicamente descritas en una nota al pie o anexo. 

## HACIENDO ELECCIONES: PUNTOS DE DECISIÓN

Cuando una acción de un usuario puede generar uno de un número de resultados, el sistema debe tomar una decisión acerca de cuál es el resultado: PUNTO DE DECISIÓN. 

(Figura 10.)

## BUSCANDO CAMINO: CONECTORES Y FLECHAS CONDICIONALES

Cuando un camino puede ser o no ser presentado al usuario, depediendo de si una o más condiciones son cumplidas, se usa el CONECTOR CONDICIONAL.

(Figura 11.)

## ELECCIÓN MÚLTIPLE: RAMAS CONDICIONALES

Por otro lado, cuando un sistema debe seleccionar un camino entre un número de opciones mutuamente exclusivas a ser presentadas al usuario, se utiliza la RAMA CONDICIONAL.

(Figura 12.)

Cabe la posibilidad de que una rama condicional puede entregar al usuario ningún camino (RESULTADO NULO). La diferencia es que con una rama condicional un resultado está prohibido; y de estar permitido, es uno de tres o más resultados posibles. 

## ELIGE UNO O MÁS: SELECTORES CONDICIONALES

El SELECTOR CONDICIONAL (se representa mediante un trapezoide) funciona de manera muy similar que la rama condicional. Eso si, hay una diferencia muy importante: con el selector, los varios caminos corriente abajo no son mutuamente exclusivos, cualquier número de caminos que satisfagan las condiciones pueden ser representados al usuario. 

![Diagramacion6](/3-estructura/selectorescondicionales.png)

El SELECTOR CONDICIONAL se usa en resultados generados por un motor de búsqueda. En este caso (figura 13), la página de resultados de búsqueda aparecería corriente abajo desde el selector; la condición es la busqueda realizada por el usuario; los caminos corriente abajo son los resultados de búsqueda del usaurio. Tal como con una rama condicional, el selector condicional puede generar un resultado nulo y de hecho esto es más común con un selector que con una rama. 

## UNA DECISIÓN, MUCHOS CAMINOS: RÁCIMOS

La estructura condicional requiere que el sistema presente más de un camino basado en condiciones. Asociamos estos caminos mediante un RACIMO (se representa mediante un círulo). El RÁCIMO puede aparecer corriente abajo desde una rama condicional o un selector condicional.
 
![Diagramacion7](/3-estructura/racimos.png)

La figura 14 funciona de una forma muy parecida a una rama condicional, pero mediante la condición presentamos más de un camino al usuario. Si el atributo tiene valor X, el usuario se dirige a la página B; pero si el atributo tiene valor Y, el usuario se dirige a C y D. 

## ALGUNAS RESTRICCIONES: ÁREAS CONDICIONALES 

Las ÁREAS CONDICIONALES (representadas por un rectángulo de esquinas redondeadas pero de línea cortada) se usan en situaciones que involucran permisos de acceso, cunado por ejemplo se requiere de un login o conexión encriptada (SSL). Las AREAS CONDICIONALES son asociadas con un resultado, el cual se genera en caso de las condiciones no son satisfechas. 

* ![Diagramacion8](/3-estructura/restricciones.png)

## Conclusión
