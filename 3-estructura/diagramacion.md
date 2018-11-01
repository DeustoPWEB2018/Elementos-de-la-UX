
# UN VOCABULARIO VISUAL PARA DESCRIBIR ARQUITECTURA DE LA INFORMACIÓN Y DISEÑO DE INTERACCIÓN

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

## COMPONENTES RE-UTILIZABLES: ÁREAS DE FLUJO Y REFERENCIAS (JON)

![Diagramacion5](/3-estructura/areasdeflujo.png)

## CONCEPTOS BÁSICOS PARA ELEMENTOS CONDICIONALES

## ELIGE UNO O MÁS: SELECTORES CONDICIONALES (JON)

![Diagramacion6](/3-estructura/selectorescondicionales.png)

## UNA DECISIÓN, MUCHOS CAMINOS: RACIMOS (JON)

![Diagramacion7](/3-estructura/racimos.png)

## ALGUNAS RESTRICCIONES: ÁREAS CONDICIONALES (JON)

Las ÁREAS CONDICIONALES (representadas por un rectángulo de esquinas redondeadas pero de línea cortada) se usan en situaciones que involucran permisos de acceso, cunado por ejemplo se requiere de un login o conexión encriptada (SSL). Las AREAS CONDICIONALES son asociadas con un resultado, el cual se genera en caso de las condiciones no son satisfechas. 

* ![Diagramacion8](/3-estructura/restricciones.png)

## Conclusión
