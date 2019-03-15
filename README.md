# myFirstGit
# ¿Cómo nace Git?

Como muchas de las grandes cosas en esta vida, Git comenzó con un poco de destrucción creativa y encendida polémica. El núcleo de Linux es un proyecto de software de código abierto con un alcance bastante grande. Durante la mayor parte del mantenimiento del núcleo de Linux (1991-2002), los cambios en el software se pasaron en forma de parches y archivos. En 2002, el proyecto del núcleo de Linux empezó a usar un DVCS propietario llamado BitKeeper.

En 2005, la relación entre la comunidad que desarrollaba el núcleo de Linux y la compañía que desarrollaba BitKeeper se vino abajo, y la herramienta dejó de ser ofrecida gratuitamente. Esto impulsó a la comunidad de desarrollo de Linux (y en particular a Linus Torvalds, el creador de Linux) a desarrollar su propia herramienta basada en algunas de las lecciones que aprendieron durante el uso de BitKeeper. Algunos de los objetivos del nuevo sistema fueron los siguientes:

* Velocidad
* Diseño sencillo
* Fuerte apoyo al desarrollo no lineal (miles de ramas paralelas)
* Completamente distribuido
* Capaz de manejar grandes proyectos (como el núcleo de Linux) de manera eficiente (velocidad y tamaño de los datos)

Desde su nacimiento en 2005, Git ha evolucionado y madurado para ser fácil de usar y aún conservar estas cualidades iniciales. Es tremendamente rápido, muy eficiente con grandes proyectos, y tiene un increíble sistema de ramificación (branching) para desarrollo no lineal 

# ¿Para qué sirve Git y qué se puede realizar con ello?

Git sirve para llevar un control de versiones. Quea su vez se define como control de versiones a la gestión de los diversos cambios que se realizan sobre los elementos de algún producto o una configuración del mismo es decir a la gestión de los diversos cambios que se realizan sobre los elementos de algún producto o una configuración a lo largo del tiempo.
Y esto sirve o se puede utilizar para hacer proyectos en equipo desde su propio ordenador, trabajando en distintas ramas a la vez, ademas de que el equipo tendrá acceso al proyecto sin ningun problema. Git es obviamente la tecnologia que facilita el trabajo en equipo.

# Ventajas
Compartición selectiva : El desarrollo de la aplicación serán únicamente nuestro, pudiendo decidir qué parte de nuestro proyecto compartimos y con quién, restringiendo a que sólo pueda verlo, que tenga la posibilidad de añadir notas, comentarios o que pueda añadir cambios. No todo tiene porque ser público (aunque en la compartición encontramos la riqueza y agilidad que fundamenta el software libre ;).
 
**Velocidad**: Muchas empresas deciden implementar GIT como servicio local en su infraestructura física, por lo tanto el control de versiones se realizaría dentro de la propia red con la consiguiente ganancia en velocidad de acceso y escritura, así como eliminando el requisito de contar con una conexión a internet obligatoria. No obstante (como ya se verá en el curso de Git, GitHub y GitLab , contar con el respaldo de un hosting para estos menesteres siempre es un plus de seguridad pues ganaremos la despreocupación para con respecto de la seguridad y accesibilidad de nuestro trabajo.
 
**Ramificación**: Ya hablamos de la ramificación en una entrada anterior , y como vimos ofrece un amplio abanico de posibilidades a la hora de realizar cambios en la estructura principal, pudiendo crear diferentes ramas sobre las que aplicar nuestras modificaciones en entornos aislados de la línea principal de desarrollo.
 
**Convergencia** : Si en la creación de una rama del proyecto encontramos que uno de los cambios incluidos se integra tal y como deseamos, sin presentar conflictos con las diferentes partes de nuestra aplicación, podremos incluir o hacer converger dicha ramificación con el desarrollo principal de forma sencilla y segura, contando así con una nueva versión o revisión de nuestro proyecto lista para ser distribuida, compartida, liberada…
 
**Sandbox** : Esta sería una ventaja de una ventaja, ya que las ramificaciones nos preparan un entorno aislado de pruebas sobre el desarrollo de la línea central de nuestra app. Los cambios realizados en una de las ramas del proyecto no tendrán consecuencias para los usuarios que actualmente usen o accedan a la versión sin modificar o principal. Muy útil si lo que vamos a hacer es incluir servicios que antes no existían en nuestra aplicación y esto pudiese poner en peligro la estabilidad de otros componentes.
 
**Flujo de trabajo adaptable** : En el sector de los controladores de versiones encontraremos diferentes formas para gestionar el flujo de desarrollo de la aplicación, destacando entre éstos los modelos centralizados y los modelos de libre configuración. Con esto encontramos que trabajemos como trabajemos encontraremos un control de versiones que se adapte a nosotros o nuestra empresa, haciendo uso desde un simple sistema jerárquico hasta un ligeramente más complejo sistema centralizado. En este apartado Git gana puntos sobre la competencia, admitiendo multitud de configuraciones que nos permitirán dentro de su estructura organizar el trabajo tal y como deseemos nosotros, nuestro equipo de desarrollo, etc…
 
**Seguridad** : Pero… ¿y si tengo un sistema de control de versiones instalado en local y tengo una caída de la tensión eléctrica que provoca el apagado de la infraestructura? ¿Los datos se habrán corrompido en el proceso de escritura? La respuesta es que resultaría muy complejo, ya que en su inmensa mayoría, los controladores de versiones cuentan con sistemas de cifrado y otros tipos de medidas de seguridad que se aplicarán para que nuestros datos permanezcan lo más íntegros posible. Por poner un ejemplo, Git hace uso de sistemas de árbol SHA1 , lo que asegurará que hasta que no se realice la comprobación del cifrado o firma, los cambios no se escribirán en el servidor.
 
**Coste** : Obviamente podremos encontrar software de control de versiones que nos ofrezcan las mismas o similares características que nos otorga Git o BitBucket entre otros, pero lo que será complejo es que alguna de estas alternativas sea gratuita. Los sistemas de hosting pueden llegar a presentar algún coste, pero entrará en nuestro juicio contemplar si realizar una pequeña inversión en infraestructura online (asegurando ya de paso un poco más el acceso y seguridad de nuestro proyecto) o adquirir una costosa solución similar a los ejemplos ya citados. Poniéndonos en la piel de un empresario, creo que cuanto más consigamos ahorrar a la empresa mejor para la empresa (y para nosotros demostrando preocupación por los recursos económicos de la misma ).

# Productos de Git

Son aquellas plataformas, herramientas o servicios enfocados a complementar y/o mejorar el trabajo en git, tales como:

Producto  |  ¿Qué es? |  Logo
---------- | ----------- | -------
GitLab   |  Gestor de repositorios  |  ![GitHLab Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/1/18/GitLab_Logo.svg/245px-GitLab_Logo.svg.png)
GitHub   |  Gestor de repositorios  |  ![GitHub Logo](http://mindthegab.com/wp-content/uploads/2014/07/Github_logo.jpg)
GitBooks  |  Herramienta para crear documentación de proyectos y libros técnicos usando Markdown y Git/Github  |  ![GitHub Logo](https://cdn-images-1.medium.com/max/1200/1*hBrAL9CfK9BfqPEyxFLYuQ.png)
GitKraken  |  Interfaz gráfica multiplataforma para git | ![GitKraken Logo](https://dl2.macupdate.com/images/icons256/56930.png?d=1550223382)
BitBucked | Gestor de repositorios | ![GitHub Logo](https://sdtimes.com/wp-content/uploads/2016/07/0722.sdt-atlassian.png)

# ¿Para que sirve Markdown?

Sirve para dar estilo al texto en la web. Ademàs igual se puede controlar la visualización del documento; formatear palabras en negrita o cursiva, agregar imágenes, crear tablas, agregar hipervinculos o url, añadir código de cualquier lenguaje de programación y crear listas. También se puede usar Markdown en la mayoría de los lugares alrededor de GitHub:

* Puños
* Comentarios en cuestiones y solicitudes de extracción
* Archivos con la extensión .md o .markdown
