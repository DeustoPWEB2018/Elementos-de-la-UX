
# Tipografía

## 1. Introducción

La tipografía es fundamental para una página web. Podemos encontrar miles de estilos de tipos tipográficos que nos pueden ser útiles para este último apartado de nuestra página web, y que nos servirán para que nuestros usuarios puedan tener una visita agradable y que puedan entender sin ningún problema nuestros contenidos. 

## 2. Tipografía con CSS (Megane)
	a. Noción de la fuente
	b. Opciones para mejorar la legibilidad

## 3. Decisiones de maquetación 

A la hora de maquetar es importante tener en cuenta las proporciones de la tipografia ya que influyen en el espacio vertical de entre líneas. Por ello es aconsejable crear un ajuste de intelineado para cada fuente que usemos. 

Es importante tener en cuenta dos aspectos: 
- Si el espacio en vertical es mínimo provocará que el texto tenga un aspecto abarrotado esto dificultará saber cuando comienza la siguiente línea. 
- Si el espacio es excesivo la lectura será incómoda y poco legible.

En el diseño web es aconsejable usar unidades de medida relativas, especialmente en lo concrniente a la tipografía. El interlineado se debe de escoger en función al tamaño de la fuente. Si usamos valores em para definir el interlineado, siempre estará relacionado con el tamaño de la fuente. En el siguiente ejemplo, vemos como afecta a la legibilidad el cambio de los valores de la altura de línea o interlineado. 

![IMG1](/5-superficie/img1.png)

Tradicionalmente llamos interlineado al espacio que hay entre líneas (no confundirlo con la altura de línea "line-height" en CSS)

![IMG2](/5-superficie/img2.png)

Para calcular la altura de línea, se añade un valor igual a la mitad del interlineado, tanto por encima como por debajo de los caracteres. EJEMPLO: Un tamaño de fuente de 36px, con una altura de línea de 54px (1,5em) deberemos de añadir un espacio de 9px tanto por encima como por debajo de los caracteres (54-36=18 18/2=9)

![IMG3](/5-superficie/img3.png)

Ahora hablaremos de la jsutificación; es decir, la alineación horizontal del texto. En la siguiente imagen el texto está alineado a la izquierda ("bandera izquierda"),también podría esta alineado a la derecha ("bandera derecha"), estar centrado o justificado a ambos lados. Cuando realizamos justificación mediante CSS debemos de aplicar la propiedad text-align, por ejemplo: {text-align: center;}

![IMG4](/5-superficie/img4.png)

El texto al estar totalmente justificado elimina el margen variable...

![IMG5](/5-superficie/img5.png)

... puede causar un efecto no desea denominado "rios", huecos que forman canales verticales en el bloque de texto.

En el mundo de la maquetación fluida (fluid layouts), donde la anchura del cuerpo del texto puede ser dificil de concretar, los textos justificados debemos de usarlos con mucha cautela. 

## 4. Seleccionar una tipografía

Como hemos comentado anteriormente, el tipo de tipografía que utilizaremos en nuestra página web es esencial. Bien para la comodidad del usuario, o la legibilidad que tienen a la hora de leer el contenido que haya en ella. 

En primer lugar, ¿se trata de una tipografía con serifas (serif) o sin serifas (sans-serif)? Las serifas son esos trazos adicionales que rematan los trazos principales de una tipografía. Fuentes como la Arial no tienen estos remates, son por tanto fuentes de “palo” o sans-serif.

Se dice que las serifas ayudan a distinguir mejor las letras y seguir el flujo del texto, haciendo que las palabras se perciban más cohesionadas, lo cual facilita la lectura. Sin embargo, en ocasiones, la forma de los caracteres puede ser tan complicada que acaba fatigando al lector y en consecuencia entorpecer la comprensión del texto. Este tema ha sido muy discutido durante décadas y no se ha presentado nunca ninguna evidencia concreta que demuestre cuál de los dos tipos de letra es más legible.

![serif](/5-superficie/serif.png)

Al ser tan importante la tipografía utilizada, podría decirse que seleccionar una tipografía puede llegar a ser hasta complicado. Debemos elegir diferentes tipos y diseños de tipografía dependiendo del tipo de contenido que vayamos a escribir. Ya sea que estés buscando una para los titulares, para el cuerpo del texto, para los bloques de citas, etc., hay muchos factores en juego.

Cabe destacar que en ocasiones, la forma de los caracteres puede ser tan complicada que acaba causando ‘estragos’ al lector y en consecuencia entorpecer la comprensión del texto. 

Uno de los conceptos más importantes en el terreno de la tipografía, es la legibilidad formal. Usamos el termino legibilidad formal cuando nos referimos a detalles tipográficos; la capacidad de reconocer letras y palabras individuales. La legibilidad lingüística tiene un rol más funcional, está relacionada con la facilidad que tendrá un lector para comprender o asimilar un bloque o fragmento texto.

Los trazos dentro de la forma de un carácter, particularmente en las tipografías serif, puede variar también en estilo y en grosor; siendo "hairline" el trazo más fino de todos los existentes.

Por tanto, algunos trazos, especialmente los curvilíneos, tendrán un grosor que variable a lo largo de extensión. Llamamos a esto modulación. Esta modulación equilibra el peso en conjunto de un carácter y evita que se produzcan áreas excesivamente pesadas en las uniones de los distintos trazos.

![modulacion](/5-superficie/modulacion.png)

Una mala modulación del trazo dará como resultado un carácter tosco y pesado en comparación con el resto del conjunto. David Kadavy llama a esto 'equilibrio de mancha', y normalmente se toma como criterio para definir la calidad de una tipografía bien diseñada. Echa un vistazo a un bloque de texto, después cierra un poco los ojos para captar la impresión de la mancha general que produce.