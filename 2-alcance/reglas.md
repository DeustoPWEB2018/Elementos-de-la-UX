# Especificación: Parte Nro 4

## Introducción: 

Mediante el siguiente informe vamos a indicar unas reglas necesarias para poder realizar unas especificaciones que sean leídas y no sean aburridas para el receptor. Una de las principales quejas que se pueden oír por parte de los equipos que si escriben especificaciones es que nadie las lee. Si unas especificaciones no son leídas habrá muchas discusiones cuando se entregue el producto terminado. Las especificaciones son buenas, pero no si nadie las lee. Para poder “engañar” a las personas para que lean especificaciones es necesario seguir algunas reglas que nos ayudarán a que sean unas especificaciones amenas y comprensibles para nuestro público.

## Desarrollo: Las cinco reglas 
1. SÉ DIVERTIDO

Para poder engañar a nuestros lectores debemos de conseguir que sea una experiencia agradable. Mucha gente se autocensura a la hora de ser divertido ya que piensan que no es algo profesional. A la hora de redactar las especificaciones un buen lugar para poder ser graciosos son los ejemplos.

El siguiente ejemplo ha sido extraído del texto trabajado en clase:
-	El usuario pulsa Ctrl+N para poder crear una nueva tabla, Empleados, y comienza a introducir los nombres de los empleados. (Ejemplo de una especificación aburrida)
-	La cerdita Peggy, golpeando las teclas con el pintalabios porque sus rechonchos deditos son demasiado gordos para poder apretar una sola tecla cada vez, pulsa Ctrl+N oara crear una nueva tabla, Novios, y escribe el único registro “Gustavo”. (Ejemplo de una especificación divertida)
Una simple forma de ser divertido es sustituir la palabra “usuario” por cualquier otra, Hommer Simpson, Pollito Pio, Rana Gustavo… 

2. ESCRIBIR UNA ESPECIFICACIÓN ES COMO ESCRIBIR CÓDIGO PARA QUE LO EJECUTE UN CEREBRO

Debemos de tener en cuente que a la hora de escribir en código de programación nuestra audiencia principal es el compilador (def Wikipedia: traduce un programa que ha sido escrito en lenguaje de programación a un lenguaje común). Por lo tanto, es muy difícil leerlo para aquellas personas que no son compiladores y debemos de preocuparnos por hacerlo legible para aquellas personas que no son compiladores.

El siguiente ejemplo ha sido extraído del texto trabajado en clase:
-	Sea una función, DirecciónDe(x), que se define como la correspondencia de un usuario x, a la dirección de e-mail del usuario según RFC-822, una cadena ANSI. Sean el usuario A y el usuario B, donde A quiere enviar un e-mail al usuario B. Po tanto, el usuario A inicia un nuevo mensaje usando alguna (pero no odas) de las técnicas definidas en otra parte, y escribe DirecciónDe(B) en el cuadro de edición Para: (Ejemplo de una especificación poco legible)
-	La cerdita Peggy quiere irse a almorzar, así que comienza un nuevo e-mail y escribe la dirección de la rana Gustavo en el cuadro “Para”.
Nota técnica: la dirección de ser una dirección estándar de Internet (siguiendo RFC-822) (Ejemplo de una especificación algo más legible)
A menudo los programadores creen que una especificación correcta tiene que ser técnicamente correcta y no es así. Una especificación debe de ser correcta y comprensible.
Cuando escribimos especificaciones es importante que nos imaginemos a las personas que van a leerlas. Es importante preguntarse frase a frase si la persona que va a leerla la entenderá. 


3. ESCRIBE TAN SENCILLAMENTE COMO SEA POSIBLE 

	Tenemos que empezar por quitarnos de la mente que escribir sencillo es poco profesional. La personas tendemos en el amito laboral a caer en el vicio de buscar palabras mas rigidas o estructuradas en lugar de hallar palabras mas coloquiales y de facil entendimiento para transmitir ideas o lineamientos a los demás.
	 Algunos consejos:

	 * Divide el texto en frases cortas: Cuando tengamos dificultad para expresar una frase de forma clara, pues, divide la misma en 2 ó mas frases cortas.

	 * Evita los muros de texto: Nos referimos a una pagina con puro texto, y esto se debe a que generalmente tendemos a agotarnos visualmente cuando nos encontramos con algo así. Ejemplo, las revistas aplican una tecnica para evitar que su audiencia se canse rapidamente de ver y leer sus noticias: extraen una cita de la nota, la amplían exageradamente, la colocan en el centro y así de simple, quitan la sensación de que la pagina es puro texto. Tambien se puede usar listas numeradas, figuras, gráficas, tablas y mucho espacio en blanco para que parezca mas fluída la lectura.
	 * Utilíza imgagenes: como todos sabemos, una buena imagen puede resumir más que mil palabras.
	 
	 :octocat:
	 [Ejemplo de una revista aplicando varios de estos consejos en una nota](http://escuelanemomarlin.com/wp-content/uploads/Articulo-revista-mia-no-me-escucha-cuando-le-hablo.jpg)
4. REVISA Y RELEÉ VARIAS VECES
	
	Cuando revises y releas las especificaciones que escribiste y encuentres alguna frase que no sea super facíl de entender, volvé a escribirla.

5. LAS PLANTILLAS SE CONSIDERAN DAÑINAS
	Al principio puede parecer importante que todas las especificaciones tengan el mismo aspecto pero NO es así. Hacer plantillas con una estructura ó que sume nuevas secciones que pretendan abarcar mas cosas que se suponen necesarias pueden convertir todo en una gran bola de nieve. No podemos pretender que para nuevas especificaciones se utilice siempre plantillas predeterminadas y volver todo burocratico, lento y con información de sobra, estas cosas son las que terminan por desviar la atención de lo importante.
	
	Entonces, para cada especificación, definir la mejor, mas clara y facíl manera para transmitir las indicaciones de modo que los compiladores sepan que deben hacer y no tengan que caer en segundas interpretaciones o peor abandonando la tarea.

## Conclusión 

Las cinco reglas que hemos analizado anteriormente engloban a la perfección el modo que hay que redactar correctamente las comentadas especificaciones funcionales, y así en conclusión, poder “engañar” por decir de alguna manera para que los clientes lleguen a leer esas especificaciones que han tenido que escribir los de los equipos correspondientes a su redacción. 

Aunque estas reglas que subraya en el texto Spolsky parecen a primera vista y en teoría demasiados obvios o irrelevantes, a la hora de poner en práctica se nota claramente que nos necesarias para cumplir los objetivos de los editores, que como hemos dicho anteriormente, no es otra que la gente llegue a leerlos antes de utilizar el producto correspondiente. 

Por lo tanto, cabe destacar que es imprescindible seguir con mayor rigurosidad posible las cinco reglas posibles, para que todo pueda salir como los editores puedan imaginarse, y para que no haya problemas en el entendimiento de las especificaciones, o directamente los clientes ni presten ninguna atención a lo que aparezca en el texto. 

## Ejemplo general: QuéHoraEs.com 

En el mismo libro que hemos analizado minuciosamente, Spolsky además añade un ejemplo para poder explicar lo que también analizó teóricamente. En este caso, el autor nos habla de un “proyecto pensado con fines educativos, no par referirse a un producto concreto”. Para ser más concretos, habla sobre una página web llamada QuéHoraEs.com, que consiste en mostrar la hora que es a sus usuarios. 

Analizando el ejemplo tras leer las reglas, uno por uno, para empezar vemos que las especificaciones son en cierto modo “divertidos”, ya que el ejemplo en general el poder ver la hora en una página web es posiblemente divertido, o los escenarios que crea el autor también lo son. 

Por otro lado, aunque parezca difícil el hecho de que las personas puedan entender fácilmente el funcionamiento de una página web desde dentro, este ejemplo también permite que el cerebro humano, como habla Spolsky, pueda entender a la perfección lo que la página permite, y lo que puedan hacer mediante su usabilidad. Relacionado con  esto también está la segunda regla, donde los editores escriben el texto de la forma más sencilla posible, para que la gente lo pueda entender. 

La cuarta regla, la de revisar una y otra vez, la podemos pasar en este caso, ya que podemos dar de hecho que los editores la hayan hecho antes de publicar las especificaciones pertinentes. 

Por último, en el caso de la quinta regla que subraya el autor, no parece que las especificaciones funcionales de la página web QuéHoraEs.com estén sacadas de ninguna plantilla general para las especificaciones, ya que parece una estructura propia de la página y específica para explicar lo que consiste el proyecto. 

Por lo tanto, podemos llegar a la conclusión de que este ejemplo del que nos habla Spolsky es muestra perfecta del que deben ser unas especificaciones funcionales para cumplir los objetivos, y para que los clientes o los que utilicen el producto puedan entender a la perfección su utilización, y lo que deben hacer en todo momento. 

## Bibliografia
- Joel Spolsky (2000), Especificaciones funcionales sin esfuerzo: https://web.archive.org/web/20171220104805/http://spanish.joelonsoftware.com:80/PainlessSpecs/4.html
- Spolsky-Especificacion_de_ejemplo_QueHoraEs.pdf
   
