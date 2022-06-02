
******************************************
CAMBIOS PARA LA ENTREGA
******************************************

1) Se paso todo el codigo de CSS a SASS, quedando asi diferentes archivos partials. Todos los partials fueron incluidos
en un unico archivo de estilos de SASS

2) Para cumplir con el desafio, se creo un archivo _MIXINS, y dentro se definen dos mixins para los media
queries (tablet & mobile). Estos mixins toman un ancho (width) minimo y un ancho (width) maximo, y en base a esos parametros, que se
toman de la variable breakpoints, aplican los cambios. Ejemplo de las llamadas a estos mixins se pueden encontrar en _footer, _aside, 
_containers, y algunos archivos más. Se las llama mediante un include y una vez llamado el mixin se aplica el codigo especifico
para esa seccion.

3) Dentro de _MIXINS, se definio un ultimo mixin llamado set-fav-bg-color, el cual esta aplicado en el archivo _footer. 
Este mixin hace uso de una lista, la cual se recorre para crear unas clases, y a cada una de esas clases se le aplica un 
color.

4) En lo que respecta al apartado de SEO, se coloco una descripcion para todos los "alt" de cada imagen que hay en el sitio. 
Tambien se dejo un unico H1 por html. Por otro lado se aplico a cada archivo html el tag "meta description" y el 
tag "meta keywords". 

5) OTRAS MEJORAS: Se aplicaron estilos a los titulos que acompañan cada foto (se los hizo links). Asimismo
se le aplico un estilo a las fotos de los articulos, la cuales al poner el mouse encima (hover) se ponen mas claras.



