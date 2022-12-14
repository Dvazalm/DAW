
###### DAW
```Esta actividad de DAW es de David Vázquez Almenara```


# Fase de Implementación
## Revisión de código
La revisión de código es una de las fases más importantes de todo desarrollador, ya que una
vez finalizada una primera versión local de nuestro desarrollo, es necesario revisar el código
para identificar posibles problemas o soluciones a otros problemas. Para ello existen diferentes
métodos para depurar el código


## Método de depuración del patito de goma
El método de depuración del patito de goma es un término informal utilizado en ingeniería de
software para describir un método de revisión de código. El nombre hace referencia a una
historia del libro **“The Pragmatic Programmer”** en donde un programador toma un patito de
goma y revisa su código forzándose a sí mismo a explicarlo, línea por línea, al pato. Existen
otros muchos términos para esta técnica, que a menudo tienen que ver con objetos inanimados.

Muchos programadores han tenido la experiencia de explicar un problema de programación a
alguien más, posiblemente a alguien que no sabe nada sobre programación, y encontrar la
solución en el proceso de explicar el problema. Al comparar lo que supuestamente hace el
código con lo que hace en realidad, cualquier incongruencia resulta evidente. Usando un objeto
inanimado, el programador puede tratar de lograr el mismo efecto sin tener que hablar con otra
persona


# Herramienta de control de versiones: Git
Es un software de *control de versiones* diseñado pensando en la **eficiencia, la confiabilidad y
compatibilidad** del mantenimiento de versiones de aplicaciones cuando estas tienen un gran
número de archivos de código fuente.

#### GIT
**Git** es un software de control de versiones diseñado por ***Linus Torvalds***, pensando en la eficiencia, la confiabilidad y compatibilidad* del mantenimiento de versiones de aplicaciones cuando estas tienen un gran número de archivos de código fuente.
![Esto se ve si el GIF no carga](https://raw.githubusercontent.com/gist/ManulMax/2d20af60d709805c55fd784ca7cba4b9/raw/bcfeac7604f674ace63623106eb8bb8471d844a6/github.gif)

Su propósito es llevar registro de los cambios en archivos
de PC incluyendo coordinar el trabajo que varias personas realizan sobre archivos compartidos
en un repositorio de código.
El diseño de Git mantiene una enorme cantidad de código distribuida y gestionada por mucha
gente, que incide en numerosos detalles de rendimiento, y de la necesidad de rapidez en una
primera implementación.

**Entre las características más relevantes se encuentran:**

- Fuerte apoyo al desarrollo no lineal, por ende rapidez en la gestión de ramas y mezclado
de diferentes versiones. Git incluye herramientas específicas para navegar y visualizar
un historial de desarrollo no lineal.

- Gestión distribuida. Git le da a cada programador una copia local del historial del
desarrollo entero, y los cambios se propagan entre los repositorios locales. Los cambios
se importan como ramas adicionales y pueden ser fusionados en la misma manera que
se hace con la rama local.

- Almacenamiento de la información menos pesada debido al guardado de cambios y no
de archivos completos.

- Los almacenes de información pueden publicarse.

- Gestión eficiente de proyectos grandes, dada la rapidez de gestión de diferencias entre
archivos, entre otras mejoras de optimización de velocidad de ejecución.

- Compatibilidad con una amplia gama de herramientas de desarrollo.

**Existen muchas órdenes de git que nos sirven para realizar diferentes funcionalidades:**

- git init: Esto crea un subdirectorio nuevo llamado .git, el cual contiene todos los
archivos necesarios del repositorio – un esqueleto de un repositorio de Git. Todavía no
hay nada en tu proyecto que esté bajo seguimiento.

- git fetch: Descarga los cambios realizados en el repositorio remoto. Comprueba el
estado del repositorio local en comparación con el repositorio remoto.

- git merge: Impacta en la rama en la que te encuentras parado, los cambios realizados en
la rama “nombre_rama”.

- git pull: Unifica los comandos fetch y merge en un único comando

- git commit: Confirma los cambios realizados. El “mensaje” generalmente se usa para
asociar al commit una breve descripción de los cambios realizados.

- git push: Sube la rama “nombre_rama” al servidor remoto.

- git status: Muestra el estado actual de la rama, como los cambios que hay sin
commitear.

Entre muchas otras órdenes que no son necesarias para este apartado teórico. Se adjuntan
plantillas resumen de estas funcionalidades.


## .gitignore

### ¿Que es un ".gitignore" ?
Un archivo local **.gitignore** generalmente se coloca en el directorio raíz de un proyecto. También puedes crear un archivo global ***.gitignore***, y cualquier entrada en ese archivo se ignorará en todos tus repositorios de Git.

Para crear un archivo **.gitignore** local, crea un archivo de texto y asígnale el nombre ".gitignore" (recuerda incluir el . al principio). Luego, edita este archivo según sea necesario. Cada nueva línea debe incluir un *archivo o carpeta adicional* que quieras que ***Git*** lo ignore.
![Esto se ve si la imagen no carga](https://i0.wp.com/www.alphr.com/wp-content/uploads/2020/08/Whats-a-GITIGNORE-File-How-To-Use-One.jpg?fit=1200%2C666&ssl=1)


# Formatos de texto
> #[TEXTO] = Titulo 1

> ##[TEXTO] = Titulo 2

> ###TEXTO] = Titulo 3

> **[TEXTO]** = Negritas

> *[TEXTO]* = Curbadas

> ***[TEXTO]*** = Negritas y curbadas

> ~~[EXTO]~~ = Tachar texto

> <sub> [TEXTO] </sub> = SubTexto

> - [TEXTO] = Punto negro
>   - [TEXTO] = Punto blanco

```
> #[TEXTO] = Titulo 1

> ##[TEXTO] = Titulo 2

> ###TEXTO] = Titulo 3

> **[TEXTO]** = Negritas

> *[TEXTO]* = Curbadas

> ***[TEXTO]*** = Negritas y curbadas

> ~~[EXTO]~~ = Subrallar texto

> <sub> [TEXTO] </sub> = SubTexto

> - [TEXTO] = Punto negro
>   - [TEXTO] = Punto blanco
```

