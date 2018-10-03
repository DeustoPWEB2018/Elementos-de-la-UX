# Cómo usar este repositorio

En este repositorio iremos recogiendo todos los contenidos que generéis durante las reuniones de expertos, en las que trabajaréis contenidos adicionales sobre la asignatura que no presentaremos durante las clases expositivas.

Para incorporar estas aportaciones, utilizaremos el flujo de trabajo que ya has visto en los tutoriales que has realizado: fork a tu cuenta personal, branch con las modificaciones concretas en las que estés trabajando, y pull request para incorporar tus cambios al repositorio central. 

## La primera vez que lo uses

Vamos a aprovechar la configuración del entorno de trabajo con este repositorio para recordar la manera concreta de aplicar este flujo de trabajo y al mismo tiempo dejar ya preparado el repositorio para cuando empecemos con el trabajo _de verdad_. 

1. Clona este repositorio a tu ordenador. En la terminal, accede a la carpeta en la que almacenes tus repositorios git, y utiliza el comando `git clone https://github.com/DeustoPWEB2018/Elementos-de-la-UX.git`. Esto creará la carpeta `Elementos-de-la-UX` en tu ordenador.

<!-- Previous steps, before we actually started working. Fork+branch approach

1. Crea un fork de este repositorio en tu cuenta personal. Haz clic en el botón **Fork** que tienes en la parte superior derecha de la pantalla.
2. Clona tu copia personal a tu ordenador. 
    1. En tu navegador, asegúrate de que estás viendo tu fork y haz clic sobre el botón verde **Clone or download**. Copia la URL. 
    2. En la terminal, accede a la carpeta en la que almacenes tus repositorios git, y utiliza el comando `git clone URL-COPIADA-ANTES`. Esto creará la carpeta `Elementos-de-la-UX` en tu ordenador.
3. Crea un branch llamado `añadir-TUNOMBREDEUSUARIO` (por ejemplo, `añadir-mberasategi`) para hacer los cambios correspondientes a la incorporación de tu nombre, y cámbiate a esa rama: `git checkout -b NOMBERDETUBRANCH`
4. Utiliza Sublime Text para crear un archivo llamado `TUNOMBREDEUSUARIO.md`  y guárdalo en una carpeta nueva llamada `estudiantes` dentro del repositorio `Elementos-de-la-UX`.
5. Copia este texto en el archivo recién creado y sustituye con tus datos (nombre y apellido y nombre de usuario y URL del perfil de GitHub):
```
Miren Berasategi :octocat: [@mberasategi](http://github.com/mberasategi)
```
5. Añade si quieres más líneas con más información acerca de ti y guarda el archivo. Asegúrate de hacerlo en el directorio `estudiantes` del repositorio `Elementos-de-la-UX`.
6. Vuelve a la terminal, comprueba que git ha reconocido los cambios con `git status`, y añade todos los cambios para el siguiente commit con `git add .`. Después, haz commit utilizando un mensaje descriptivo, por ejemplo, `git commit -m "Añadir TUNOMBREDEUSUARIO al directorio de estudiantes"`
7. Actualiza tu fork en GitHub con los cambios que acabas de hacer en tu ordenador: `git push origin NOMBREDETUBRANCH`
8. Accede al [repositorio central de Elementos de la UX](https://github.com/DeustoPWEB2018/Elementos-de-la-UX) y crea [un nuevo pull request](https://github.com/DeustoPWEB2018/Elementos-de-la-UX/compare) para incorporar tus cambios. 
    - Si aparece tu recién creado branch, simplemente haz clic en **Compare & pull request**
    - Si no, es posible que tengas que hacer clic en _compare accross forks_. En cualquier caso:
        - **Base fork** debe ser el repositorio central (en DeustoPWEB2018), branch `master`
        - **Head fork** debe ser tu fork personal, branch `añadir-TUNOMBREDEUSUARIO`
        - Haz clic en **Create pull request**
9. ¡Sigue las instrucciones en el propio pull request para terminar!
-->

Con esto ya tendrás una copia personal del repositorio de contenidos adicionales en tu ordenador, que utilizarás a lo largo de todo el semestre. La manera de trabajar será prácticamente idéntica para las modificaciones futuras en este repositorio, tal y como se detalla en el siguiente apartado.

## Aportaciones del trabajo con expertos

Cuando os reunáis con el grupo de expertos, primero decidid quién se encargará de cada tarea:

- Secretaría: tomar nota y recoger el acta en papel de la reunión durante la clase, decisiones, primera redacción del contenido, :octocat: contribuir al contenido después de clase, revisar y comentar el contenido antes de entregar
- Control: controlar el tiempo y asegurar el cumplimiento de los requisitos, :octocat: añadir el texto al repositorio ([instrucciones a continuación](#control)), contribuir al contenido después de clase, revisar y comentar el contenido antes de entregar
- Comunicación: comunicarse con el profesor y/o otros grupos, presentar el contenido a la clase, :octocat: marcar el contenido como finalizado ([instrucciones a continuaión](#comunicacion)), contribuir al contenido después de clase, revisar y comentar el contenido antes de entregar

A continuación se detallan las tareas paso a paso para cada rol.

### Control

La persona encargada de control será quien incorpore el contenido redactado o iniciado durante la clase (recogido en el acta en papel por secretaría) en este repositorio. Para esto:

1. Asegúrate de que tienes la última versión del repositorio en tu ordenador. En tu terminal: `git pull origin master`
2. Crea un branch de trabajo para utilizar durante esta unidad. Nombra el branch con una palabra que indique el tema en el que estáis trabajando, por ejemplo, `personas`: `git checkout -b TEMA`
3. Utilizando Sublime Text, crea un archivo nuevo y añade el texto que hayáis elaborado durante la reunión en clase utilizando la sintaxis de Markdown. Aseguráos de establecer quién escribirá sobre cada sección o parte del documento, para evitar pisaros durante el trabajo
4. Guárdalo en la carpeta de la unidad correspondiente, con el nombre del tema que estéis tratando, por ejemplo, `personas.md`. Ten en cuenta estas indicaciones a la hora de dar nombre a los archivos:
    - Utiliza siempre minúsculas 
    - Evita utilizar espacios: puedes sustituirlos por guiones
    - No utilizar caracteres especiales como ñ, letras con tilde, o símbolos como \& o \%
5. Vuelve a la terminal y comprueba que git ha detectado los cambios con `git status`. Asegúrate de que estás en tu branch de trabajo, `TEMA`
6. Añade los cambios y haz commit con un mensaje descriptivo:
    ```
    git add .
    git commit -m "Generar el documento sobre Personas"
    ```
7. Envía los cambios al repositorio central en la nube: `git push origin TEMA`
8. Accede [con tu navegador al repositorio](https://github.com/DeustoPWEB2018/Elementos-de-la-UX) y, si aparece tu recién creado branch, simplemente haz clic en **Compare & pull request**. Si no, haz clic en la pestaña **Pull requests**, y ahí en el botón **New pull request**
    - **Base** debe ser el branch `master`
    - **Compare** debe ser tu branch, `TEMA`
    - Haz clic en **Create pull request**
9. En el lado derecho de la página del pull request, 
    - haz clic en **Reviewers** y señala a todas las personas que hayan participado en tu grupo de expertos 
    - haz clic en **Milestone** y selecciona la unidad a la que corresponde este tema 

Recuerda revisar también las [instrucciones para contribuir al contenido](#todos-los-miembros-del-grupo-de-expertos).

### Comunicación

Una vez que el trabajo esté terminado y tenga todos los miembros del grupo hayan aprobado el contenido, la persona encargada de comunicación marcará el pull request con la etiqueta correspondiente. Para esto:

1. Accede a la página del pull request y, en el lado derecho, haz clic en **Labels** y selecciona **terminado** 
2. En **Assignee**, añade a @mberasategi

Es importante que recordéis que el plazo para esto es **antes de la clase del segundo lunes de cada unidad**. 

Recuerda revisar también las [instrucciones para contribuir al contenido](#todos-los-miembros-del-grupo-de-expertos).

### Todos los miembros del grupo de expertos

En cuanto finalicemos la clase dedicada al trabajo en grupos de expertos, todos tendréis que realizar las **autoevaluaciones** para todos los participantes. Las autoevaluaciones se recogen en una carpeta llamada `evaluaciones` dentro del directorio correspondiente a cada unidad. 

Cada vez que participes en una sesión de trabajo en grupos de expertos:

1. En la terminal, accede a tu carpeta del repositorio y crea el branch de trabajo para utilizar durante esta unidad: `git checkout -b TEMA`
2. Abre la carpeta en tu Explorador de archivos (Windows) o Finder (Mac). Accede al directorio `evaluaciones` de la unidad en la que estemos trabajando y abre el archivo Excel que tienes en esa carpeta (`MiApellidoMiNombre-2018MMDD.xlsx`)
3. Rellena en esa hoja de cálculo tus evaluaciones (para ti y el resto de miembros que han trabajado contigo en el grupo de expertos), siguiendo las indicaciones que encontrarás en el mismo documento. Guárdalo modificando el nombre como corresponde, por ejemplo, `BerasategiMiren-20181002.xlsx` (con `Archivo > Guardar como`)
4. En la terminal, guarda, confirma y envía a la nube los cambios realizados:
    ```
    git add .
    git commit -m "Evaluar reunión del día 20181002"
    git push origin TEMA
    ```


<!-- Previous branch approach 

En primer lugar es necesario que actualices tu copia local con los cambios del repositorio central, que incluyen la plantilla para la autoevaluación. Para esto, accede a la carpeta del repositorio con tu terminal y ejecuta los siguientes comandos:
```
git pull origin master
git checkout evaluaciones
```

Después, cada vez que participes en una sesión de trabajo en grupos expertos:

1. En la terminal, accede a tu carpeta del repositorio y cámbiate al branch `evaluaciones`: `git checkout evaluaciones`
2. Abre la carpeta en tu Explorador de archivos (Windows) o Finder (Mac). Verás que ahora, en lugar de mostrar los contenidos trabajados acerca de los elementos de la UX, solamente tienes un directorio `evaluaciones`. Abre el archivo Excel que tienes en esa carpeta (`MiApellidoMiNombre-2018MMDD.xlsx`)
3. Rellena en esa hoja de cálculo tus evaluaciones (para ti y el resto de miembros que han trabajado contigo en el grupo de expertos), siguiendo las indicaciones que encontrarás en el mismo documento. Guárdalo modificando el nombre como corresponde, por ejemplo, `BerasategiMiren-20181002.xlsx` (con `Archivo > Guardar como`)
4. En la terminal, guarda, confirma y envía a tu copia personal en la nube los cambios realizados:
    ```
    git add .
    git commit -m "Evaluar reunión del día 20181002"
    git push origin evaluaciones
    ```
5. Vuelve a tu branch de trabajo para seguir generando el contenido que te corresponde en este borrador: `git checkout TUNOMBRE-TEMA`

Estas autoevaluaciones no necesitan incorporarse al repositorio central, por lo que no es necesario que crees un pull request para esto. Las recogeré del repositorio personal de cada estudiante.

-->

Como probablemente no tendremos tiempo durante la clase dedicada al trabajo en grupos de expertos de finalizar la redacción, será necesario que cada uno de los miembros del grupo continúe aportando al documento conjunto durante el resto de la semana. Para esto, cada vez que vayas a iniciar el trabajo en tu ordenador:

1. Asegúrate de que tu copia local está actualizada con los últimos cambios del repositorio central: `git pull origin TEMA`
2. Cámbiate al branch de trabajo para vuestro tema: `git checkout TEMA`
3. Utilizando Sublime Text, realiza tus contribuciones a la sección que te corresponda de vuestro tema
4. En la terminal, guarda, confirma y envía a la nube los cambios realizados utilizando un mensaje descriptivo de los cambios que has estado haciendo:
    ```
    git add .
    git commit -m "Un mensaje descriptivo de lo que has estado haciendo"
    git push origin TEMA
    ```

Recuerda guardar y confirmar los cambios cada vez que finalices un bloque de modificaciones (con `git add .` y `git commit -m "Mensaje descriptivo"`). Puedes subir a la nube  (`git push origin TEMA`) solo de vez en cuando, por lo menos cuando vayas a dejar de trabajar temporalmente. Cuando vuelvas al trabajo, sigue los pasos empezando otra vez desde el 1.

Además de contribuir al contenido, todos los miembros del grupo de expertos tenéis también que revisar y comentar el contenido de los demás. Podréis ver las contribuciones de las otras personas en el documento de trabajo, y utilizad la página del pull request para comentar y discutir sobre el contenido.

Puedes añadir tu revisión haciendo clic en el botón **Add your review** que aparecerá en la parte superior de la página del pull request. Tienes varias opciones:

- Simplemente añadir un comentario. Escríbelo, selecciona **Comment** y haz clic en **Submit review**
- Aprobar las contribuciones. Puedes escribir un comentario si quieres. Selecciona **Approve** y haz clic en **Submit review**
- Solicitar algunos cambios. Escribe qué cambios crees que son necesarios y, a ser posible, menciona con @ a la persona encargada de realizarlos. Selecciona **Request changes** y haz clic en **Submit review**


