# EPE1_Fly-Away
Proyecto web, carrera Ing Inf, IPCHILE

Changelog
Push realizado el 14- Marzo -2022
-	Se ha creado las distintas carpetas y archivos que seran utilizados para la producción de la aplicación
-	Se ha creado un repositorio en Github con el objetivo de respaldar y controlar los cambios en la página (https://github.com/waflex/EPE1_Fly-Away)
-	Se utilizo imagen de ejemplo para pruebas con un background
-	Se creo archivo “Styles.css” para el estilizado general de ciertos elementos

Nota: Durante el transcurso de la tarde se realizo un push, con el objetivo de continuar el progreso desde otra ubicación.

Push realizado el 15- Marzo -2022
-	Se agrego un footer en página Index.

Nota: No hay más cambios.

Push realizado el 20-Marzo-2022
Primera actualización de código

-	Se cambio casi todo el contenido en la página “Index.html”, se mantuvo lo que es el Navbar y se eliminó los elementos flotantes de contacto entre otros.

-	Se agrego un elemento de tipo “carousel” de Bootstrap, el cual permite presentar distintas imágenes y textos a los usuarios.

-	En “index.html” se reorganizaron los enlaces referentes a los estilos de Bootstrap y sus respectivos documentos Javascript.
-	Se agrego link JavaScript público “AOS” el cual permite una presentación más dinámica del contenido dentro de “Index.html” logrando efectos de fade-up o fade-left para ciertos contenidos

-	Se redujo el contenido de Footer a solo un elemento html

-	Se creo una base para la pagina “Destinos.html” en la cual se presentan distintos elementos “card” de Bootstrap, con el objetivo de poder identificar de forma más ágil los distintos “destinos”

-	El elemento “card” contiene un título (nombre destino, País), un texto (descripción destino Lorem Ispum) y una imagen en la parte superior para identificar de forma visual algún elemento referente a la ubicación.

-	Se cargaron distintas imágenes referentes a los destinos a publicar, cada una ubicada en la carpeta destinos

-	En “style.css” se modificaron varios aspectos del comportamiento de navbar y carousel, también se agrego un efecto “::before” al Navbar con el fin de dar un efecto de “Blur” en la parte inferior de navbar

-	Se elimino background-image de “style.css” por el momento la página se mantendrá sin imagen de fondo.

-	Se agrego cambios en el comportamiento de “carousel” en pantallas inferiores a 640px, 

-	En pantallas inferiores a 920px se ajusto un poco el margin-top de carousel


Push realizado el 21-marzo-2022
2da Actualización del proyecto

-	Se agrego un “esqueleto” a todas las páginas.

-	Se actualizo todo el proyecto a Bootstrap 5.1  (algunos elementos estaban implementados en Bs4)

-	Se agrego contenido dentro de “hoteles.html”, ahora presenta distintos hoteles “asociados” y una imagen referente a cada uno.

-	Elemento “Carousel” en “index.html” ahora funciona con base Bs5.

-	Se crearon elementos ficheros “Destiny.css” y “Hotels.css”, los cuales controlan los márgenes en pantallas inferiores a 500px, y agregaron efectos y fondo a los títulos de cada página respectiva

-	Ahora los títulos de Destinos y Hoteles presentan un fondo referente a su categoría, en conjunto a un diseño mas llamativo para su Fuente.

-	A cada titulo se le asignó el color principal de la empresa, y estos contienen sombras con el fin de acentuar el texto ingresado.

-	Las propiedades de título que habían sido creadas en “styles.css” fueron transferidas a los distintos archivos “.css” para cada página, con el fin de presentar un mismo formato, pero distinto background-image a cada titulo

-	Se agrego la primera imagen para la página “hoteles.html”

-	Se cambio la disposición de clases en los contenedores de “card” de hoteles y destinos, para poder organizar mejor los contenidos

-	Se creo la página contacto

-	Se creo la página Centro de Ayuda

-	La pagina contacto ahora contiene la información de contacto de la empresa, los elementos también son responsivos según el tipo de pantalla en el que se encuentran,

-	Los iconos respectivos de cada elemento contienen los colores indicados por la empresa

-	Los enlaces en cada icono redirigen a la aplicación correspondiente, numero de teléfono = Llamadas, Correo = aplicación correo seleccionada por usuario

-	Se creo el archivo “contact.css” el cual controla el comportamiento de la “caja” en la que se encuentran los iconos de contacto, junto con las propiedades del título de página y su respectivo fondo

-	La pagina Centro de Ayuda ahora muestra una lista desplegable de preguntas y sus respectivas respuestas

-	Cada pregunta contiene una acción de tipo “collapse” de Bootstrap, con la cual se despliega su respuesta.

-	Los iconos de las preguntas no están funcionando del todo bien, por lo que se está buscando un cdn nuevo para FontAwesome

Push realizado el 22-marzo-2022
-	Se creo un nuevo div con la clase background, su objetivo es controlar la imagen de fondo de forma independiente del resto de elementos en “body”

-	Los elementos “card” ubicados en Destinos y Hoteles fueron modificados ya que estaban presentando problemas en su formato para dispositivos móviles.

-	Los archivos “hotels.css” y “Destiny.css” ahora contienen la clase box-shadow “box-shadow>*” con la cual se le asigno a todos los elementos dentro de esta un efecto de sombra de “.5rem” 

-	Se actualizo la imagen de fondo de todo el proyecto

-	La nueva clase background aun presenta algunos problemas, pero esta ya es visible y no crea conflicto con los demás elementos

Push realizado el 24-marzo-2022
-	Se elimino el Footer en el proyecto, ya que la información de empresa se encontraba en contacto

-	Se elimino el width asignado en cada uno de los elementos “card” del proyecto

-	Se cambio la imagen de fondo

Push realizado el 27-marzo-2022
-	Se agrego destino “Quito, Ecuador” debido a que era uno de los principales indicados en la lista
-	Se modifico la redirección de los botones “saber más” en el elemento “carousel” en la pagina “index.html”
 
Problemas Presentes en el proyecto

	Una vez terminados todos los elementos solicitados aun se encuentran algunos problemas que no se lograron solucionar a la fecha:
	
1-	Los iconos en Centro de Ayuda no están siendo responsivos, si bien se les cambio en algún momento el “Font-size” para cuando la resolución fuese para dispositivos móviles, estos no tomaban las nuevas propiedades, incluso cuando se les quito la clase que permite el aumento de estos
2-	Por alguna razón, el background del body, no esta mostrando la imagen por completo, si bien se le aplicaron propiedades como “center” “no-repeat” entre otros, este no está adaptándose a las distintas resoluciones, ni tampoco esta tomando la forma de la pantalla actual.
3-	Por alguna razón al estar en pantallas tamaño medio, el script “AOS” el cual se usa para las animaciones a medida que uno navega en pantalla, esta actuando un poco atrasado a la posición en la que se encuentra el usuario, logrando una sensación de vacío por unos segundos.
