# Cómo usar este repositorio

En este repositorio iremos recogiendo todos los contenidos que generéis durante las reuniones de expertos, en las que trabajaréis contenidos adicionales sobre la asignatura que no presentaremos durante las clases expositivas.

Para incorporar estas aportaciones, utilizaremos el flujo de trabajo que ya has visto en los tutoriales que has realizado: fork a tu cuenta personal, branch con las modificaciones concretas en las que estés trabajando, y pull request para incorporar tus cambios al repositorio central. 

## La primera vez que lo uses

Vamos a aprovechar la configuración del entorno de trabajo con este repositorio para recordar la manera concreta de aplicar este flujo de trabajo y al mismo tiempo dejar ya preparado el repositorio para cuando empecemos con el trabajo _de verdad_. 

1. Crea un fork de este repositorio en tu cuenta personal. Haz clic en el botón **Fork** que tienes en la parte superior derecha de la pantalla.
2. Clona tu copia personal a tu ordenador. 
    1. En tu navegador, asegúrate de que estás viendo tu fork y haz clic sobre el botón verde **Clone or download**. Copia la URL. 
    2. En la terminal, accede a la carpeta en la que almacenes tus repositorios git, y utiliza el comando `git clone URL-COPIADA-ANTES`. Esto creará la carpeta `Elementos-de-la-UX` en tu ordenador.
3. Crea un branch llamado `añadir-TUNOMBREDEUSUARIO` (por ejemplo, `añadir-mberasategi`) para hacer los cambios correspondientes a la incorporación de tu nombre, y cámbiate a esa rama: `git checkout -b NOMBERDETUBRANCH`
4. Accede al directorio `estudiantes` de la carpeta recién creada (`cd Elementos-de-la-UX/estudiantes`) y crea el archivo que contendrá tu nombre:
    - Si estás en Windows, `copy mberasategi.md TUNOMBREDEUSUARIO.md`
    - Si estás en Mac, `cp mberasategi.md TUNOMBREDEUSUARIO.md`
5. Abre el archivo `TUNOMBREDEUSUARIO.md` con Sublime Text y personaliza los datos que aparecen ahí: 
    - Escribe tu nombre y apellido como título de primer nivel (`#`) en la línea 1
    - Modifica el enlace de la línea 3 para que sea tu nombre de usuario de GitHub el que lleve a tu perfil (`:octocat: [@TUNOMBREDEUSUARIO](http://github.com/TUNOMBREDEUSUARIO)`)
    - Añade si quieres más líneas con más información acerca de ti
    - Guarda el archivo. Asegúrate de hacerlo en el directorio `estudiantes` del repositorio `Elementos-de-la-UX`.
6. Vuelve a la terminal, comprueba que git ha reconocido los cambios con `git status`, y añade todos los cambios para el siguiente commit con `git add .`. Después, haz commit utilizando un mensaje descriptivo, por ejemplo, `git commit -m "Añadir TUNOMBREDEUSUARIO al directorio de estudiantes"`
7. Actualiza tu fork en GitHub con los cambios que acabas de hacer en tu ordenador: `git push origin NOMBREDETUBRANCH`
8. Accede al [repositorio central de Elementos de la UX](https://github.com/DeustoPWEB2018/Elementos-de-la-UX) y crea [un nuevo pull request](https://github.com/DeustoPWEB2018/Elementos-de-la-UX/compare) para incorporar tus cambios. 
    - Si aparece tu recién creado branch, simplemente haz clic en **Compare & pull request**
    - Si no, es posible que tengas que hacer clic en _compare accross forks_. En cualquier caso:
        - **Base fork** debe ser el repositorio central (en DeustoPWEB2018), branch `master`
        - **Head fork** debe ser tu fork personal, branch `añadir-TUNOMBREDEUSUARIO`
        - Haz clic en **Create pull request**
9. ¡Sigue las instrucciones en el propio pull request para terminar!

Con esto ya tendrás una copia personal del repositorio de contenidos adicionales en tu cuenta de GitHub, que utilizarás a lo largo de todo el semestre. La manera de trabajar será prácticamente idéntica para las modificaciones futuras en este repositorio, tal y como se detalla en el siguiente apartado.

## Aportaciones del trabajo con expertos

:construction: Detalles en breve :construction:


