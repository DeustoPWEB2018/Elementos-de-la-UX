# Plano de Superficie

## ¿Qué son las retículas? (Estelle)

## Terminología (Estelle)

## La regla de los tercios (Estelle)

## La retícula de doce columnas (Iñaki)

## Conclusiones (Iñaki)

## Sistema de Retícula Infinita

### ¿Qué es?

Teniendo en cuenta que en la actualidad, existen múltiples opciones que permiten al usuario navegar a través de la web, es conveniente adaptar el diseño y la estructura de un sitio web, que aunque principalmente pueda estar diseñado para que los usuarios la visiten a través del ordenador, es recomendable que el grado de accesibilidad a otros dispositivos, y por ende, a otras necesidades de visualización y navegación, sean lo suficientemente amplias como para que la visualización a través de dispositivos como teléfonos móviles o tablets sea adecuado. 

En determinadas situaciones, el estado de la cuadrícula puede variar, hasta situarse en una sola columna en determinadas situaciones, principalmente cuando se trata de adaptar el contenido a dispositivos móviles. 
 
#### Componentes

Cabe destacar los siguientes atributos cuando hacemos referencia a este tipo de retículas: 

1. Jerarquía: ¿Cuál es el orden y cuáles son los elementos más importantes a la hora de definir el diseño?

2. Densidad: ¿Cuántos detalles se muestran?

3. Interacción: ¿Cómo debería ser el menú? ¿Una lista de enlaces o un desplegable? ¿Las imágenes deben aparecer de forma seguida o agrupadas?

4. Ancho: ¿Cómo está definido el ancho? ¿Tiene una anchura determinada? ¿Tiene un límite de anchura establecido? ¿O está establecido a través de porcentajes?


### Diseñando un sistema de retículas infinita

Para realizar el diseño de retículas infinito, se puede optar por seguir los siguientes pasos: 

1. __Usar unidades proporcionales__

Deben tomarse decisiones acerca de la proporcionalidad del sitio web respecto a los elementos que se situarán en el propio sitio. Esto supone que cuando tomamos una decisión acerca de determinadas unidades, lo hacemos teniendo en cuenta que esta situación será determinante en las siguientes decisiones que se vayan a tomar. 

* Tamaño de la fuente empleada en relación a la fuente base del documento

* Tamaño del píxel en un elemento determinado que se ajuste a una resolución determinada

* El tamaño de un elemento respecto al contenido 

* Unidades de medición VH y VW, que posibilitan la inclusión de imágenes a lo largo y ancho del fondo del sitio web, así como la adaptabilidad del texto a los dispositivos en los que es cifrado. La unidad VH determina la centésima parte de la altura del viewport mientras que la unidad VW determina la centésima parte de la anchura del viewport, de tal forma que: 

	* 1VH = 1% del viewport
	* 100VH = 100% del viewport    
	* 1vw = 1% del viewport
	* 100vw = 100% viewport 

2. __Comenzar con los extremos para después resolver los entrecruzamientos__
Es importante, en primer lugar, contemplar la posibilidad de diseñar cada elemento en función de sus posibilidades y necesidades, teniendo en cuenta la premisa de adaptar el contenido a las necesidades de los usuarios. Es por ello que cabe la posibilidad que un diseño extendido en exceso a lo ancho o a lo largo resulte incómodo para su visualización en determinados dispositivos. Dependiendo del contenido en cuestión, se buscará una proporción entre adaptabilidad y optimización del contenido. Hay que tener en cuenta el estado más grande y más pequeño, de tal forma que para cada uno de ellos se podrá cumplir una determinada función, de ahí que lo adecuado es realizar combinaciones de ambos formatos, de tal forma que el resultado obtenido sea más interactivo para el usuario.  

3. __Cambiar el estado cuando se rompan las relaciones__
Cuando se produce un choque entre los contenidos y el diseño de la cuadrícula llega el momento en el que el diseño debe variar para adaptarse a las necesidades de cada contexto. Aunque es difícil predecir en qué ancho respecto al contenido que aparece en la página es óptimo cambiar el estado del diseño, existen herramientas que permiten realizar una previsualización para obtener una respuesta que atiende a dicha cuestión de forma parcial, tales herramientas son Gridset y Responsive.is. 
Puede resultar que el estado mínimo y el máximo no contemplen situaciones de carácter intermedio, de ahí que la cantidad de diseños que creemos variarán en base a las necesidades del sitio web y de las variedades que pueden existir en su visualización.    

4. __Ir más allá de los extremos__
A su vez, pueden encontrarse situaciones en las que, el ancho de los blancos resulta demasiado corto, y produce espacios en blanco que producen una resolución del texto muy inferior, mientras que por la parte superior, el espacio entre el cuerpo del texto y los encabezados, así como el pie de página, resulta mínimo, y ofrece una sensación de acoplamiento en el que apenas existe margen en la parte superior e inferior. 

## Referencias 