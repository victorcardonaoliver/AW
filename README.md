# AW

1. Estructura mínima de una Web.
  La estructura mínima de una web es 
  <html>
    <head></head>
    <body></body>
  </html>

2. Explica las 3 formas de usar CSS en HTML.
  CSS Inline: El funcionamiento de este tipo de CSS es el siguiente.
    por ejemplo:
      <h1 style="color: red; font-size: 40px;"></h1>
     Con la linia anterior se editara de color rojo el h1 en el cual es puesto el estilo.
  CSS Interno: Con el CSS Interno antes del <body> debemos poner un style type css, es este ejemplo editaria todos los h1 del codigo HTML, 
     en el caso de que solo queremos un h1 determinador debemos de señalarlo con ID. 
    <style type="text/css">
		h1 {
			color: red;
		}
  CSS Externo: Esta opción es la más se recomienda, ya que tendriamos solamento un 
    documento a parte del .html donde estaria toda la información de la pagina, en un documento .css editariamos la información del .html.
    <link rel="" type="text/css" href=".css">
    
3. Crea una lista sin ordenar con 5 ingradientes de una receta de cocina.
  <ul>
    <li>Aceite</li>
    <li>Huevos</li>
    <li>Harina</li>
    <li>Pan rallado</li>
    <li>Pollo</li>
   </ul>
   
4. Como se puede incluir javascript en HTML.
  Se puede incluir utilizando una etiqueta <script></script> entre las etiquetas <head> o las etiquetas <body>.
  
5. ¿Que diferencia hay entre una clase y una ID?
  class: Lo puedes utilizar mas de una vez en el documento.html
  id: Es único, no se deberia de haber otro id igual en el documento .html con el mismo id.

6. Código para hacer un enlace a otra página y que esta se abra en una nueva ventana.
  Par poder abrir en una página nueva un enlace lo hariamos con target de valor _blank, se quedaria des esta forma:
  <a href="marca.com" target="_blank">aqui pondrimaos el titulo que queremos en el enlace</a>
  
7. ¿Qué son las pseudoclases?, pon ejemplos.
  Son palabras las cuales añadimos al elemento y que nos especifican el estado de un elemento, por ejemplo:
    :hover, :visited, :root, y muchas mas.
    
8. Explica el modelo de caja de CSS (margin, border y padding)
  margin: En margin nos permite establecer los 4 margenes de las cajas en tan solo un margin.
  border: En el border podemos editar el tamaño en el cual queremos los bordes de la caja.
  padding: En el padding podemos estlecer el espacio que hay entre el contenido y el borde de la caja.
  
9. Explica que son los selectores de CSS y pon ejemplos
  Es la unión que hay entre las hojas de los estilos y también los documentos en los cuales aplicamos dichas hojas.
  
10. Di a que afectan:
      p a {color: red;} hace referencia a todos los enlaces de todos los parrafos del documento .html se hagan del color rojo.
      p > a {color: red;} hace referencia a todos los enlaces que sean hijos de los parrafos los haga del color rojo.
      h1 + h2 {color: red;} hace referencia a todos los h1 y h2 que sean de color rojo.
      a [class] {color: blue;} hace referencia a los enlaces y se pinten con el color azul.
      a [class="Externo"] {color: blue;} hace referencia a los enlaces tipo externo los haga de color azul.
      a [href="http://www.ejmplo.com"] {color: blue;} hace referencia al link www.ejemplo.com sea de color azul.
  
  
  
