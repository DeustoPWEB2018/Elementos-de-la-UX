
# Tipografía

## 1. Introducción (Mikel)

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



## 4. Seleccionar una tipografía (Mikel)
