
# UN VOCABULARIO VISUAL PARA DESCRIBIR ARQUITECTURA DE LA INFORMACIÓN Y DISEÑO DE INTERACCIÓN

Para la elaboración de este escrito nos hemos basado en la lectura de Jesse JAmes Garrett. 

## INTRODUCCIÓN

## CONSIDERACIONES INICIALES

## ELEMENTOS SIMPLES

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
