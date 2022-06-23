******************************************
ACERCA DEL SITIO
******************************************

El proyecto web que presento consiste en un BLOG, o sitio de artículos, donde
la temática principal o de fondo es el "Trading". El sitio consta de cinco páginas,
la cuales se detallan a continuación:

1) HOME: Pagina con un listado de artículos varios, cada uno 
acompañado por su respectiva foto, como así también por un título
y una breve descripción. 

2) HERRAMIENTAS: Pagina con un listado de artículos relacionados 
con herramientas para el Trading.

3) ESTRATEGIAS: Pagina con un listado de artículos relacionados
con estrategias para el Trading.

4) CONTACTO: Pagina con un formulario para contacto.

5) ACERCA: Pagina con una descripcion personal y del Blog.



******************************************
ESTRUCTURA DEL SITIO // LAYOUT
******************************************

La estructura del sitio -que se repite en cada pagina- consta de: 
1- Un menu principal. 
2- Una sección de titulo de pagina. 
3- Una seccion principal o main.
4- Un sidebar con enlaces varios
5- Un footer 
6- Un BONUS EXTRA (ver mas abajo!)

******************************************
TECNOLOGÍAS APLICADAS Y/O UTILIZADAS
******************************************

-Para la construccion del menu se utilizo BOOTSTRAP. 
-Se aplicaron conceptos de GRID.
-Se aplicaron conceptos de FLEXBOX.
-Se utilizaron animaciones (En el formulario del Footer y en el Home, en el box de suscripcion)
-Se utilizaron -en algunos casos- unidades EMs
-SASS (con diferentes partials)
-variables SASS
-MIXINs para los media querys (Se definieron dos mixins para los media querys (tablet & mobile). Estos mixins toman un ancho 
(width) minimo y un ancho (width) maximo, y en base a esos parametros, que se toman de la variable breakpoints, aplican los 
cambios. Ejemplo de las llamadas a estos mixins se pueden encontrar en _footer, _aside,  _containers, y algunos archivos más. 
Se las llama mediante un include y una vez llamado el mixin se aplica el codigo especifico para esa seccion).  Se definio 
tambien un ultimo mixin llamado set-fav-bg-color, el cual esta aplicado en el archivo _footer. Este mixin hace uso de una 
lista, la cual se recorre para crear unas clases, y a cada una de esas clases se le aplica un  color.



******************************************
SEO
******************************************

En lo que respecta al apartado de SEO, se coloco una descripcion para todos los "alt" de cada imagen que hay en el sitio. 
Tambien se dejo un unico H1 por html. Por otro lado se aplico a cada archivo html el tag "meta description" y el 
tag "meta keywords". 




******************************************
BONUS EXTRA
******************************************

Para mostrar como seria un articulo del BLOG, se creo una pagina adicional, 
la cual puede verse al hacer click en el primer enlace (o articulo) del HOME. 
El articulo que puede verse, es el que se titula: 
"Trading Psychology: A Non-Cynical Primer (trading's affected by psychology)"



******************************************
ULTIMAS CONSIDERACIONES & AGRADECIMIENTOS
******************************************

Si bien el BLOG esta aplicado y oriendtado al Trading, el sitio es totalmente flexible
para ser utilizado con cualquier otro tipo de contendio. Cambiando los textos
e imagenes, puede convertirse en un BLOG de cualquier otra tematica.

Agradecer a todo el equipo de Coder House, haciendo especial hincapie en mi Profesor:
Santiago Acosta y en mi tutor particular: Pedro, sin los cuales el desarrollo de este site
no podria haber sido posible. A ellos todo mi agradecimiento.





