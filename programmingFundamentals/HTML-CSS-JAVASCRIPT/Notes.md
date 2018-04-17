[![basic](../../img/home.png)](https://calypsobronte.github.io/basicprogramming/)
# HTML, CSS, JavaScript de verdad

***Los programadores pasan el 80% de su tiempo leyendo código y 20% escribiendo código, por esto es importante **SEGUIR BUENAS PRACTICAS**.***

*Primero que todo antes de arracar debes de guardar con antelacion el archivo antes de que empiezes a programar en el editor porque sino este no te marcara la `sintaxis` que quieres programar.*

***Nota:*** *Los programadores por ley deben de ver las extenciones de los archivos `.html` `.js` `.css`*
![html:page][gif_page]

**HTML** *funciona con etiquetas. como lo muestra la imagen.*
![html:etiqueta][img_etiqueta] 
*Entonces con la etiqueta se veria asi:*
```html
<strong>Hola Mama</strong>
```
Muchas de estas etiquetas no tienen contenido por ejemplo `.br`.
```html
<br/> <!--Esta es una etiqueta de salto de linea-->
```
La mayoria de las etiquetas se muestra cuando se abre `<>` y se cierra `</>`
```html
<code> <!--Esta es una etiqueta abre para ingresar el contenido-->
  Contenido
</code> <!--Essta es una etiqueta cierra para mostrar que se finalizo el ingreso del contenido-->
```
**Funcion de cada etiqueta**

***STRONG - B:*** *Estas dos etiquetas sirven para poner negrita a tu contenido cualquiera de estas dos te puede servir.*
```html
<!--Poner Letra en negrita-->
<strong> contenido </strong>
 <b> contenido </b> 
```
![html:etiquetas][img_etiquetas]
___

***P:*** *Sirve para crear un parrafo.*
```html
<p> Este es un parrafo y es texto regular </p> 
```
---
***COMENTARIOS:*** *En cada uno de estos se puede hacer diferentes formas de hacer comentarios*
  - **HTML**:
    ```html
    <!-- Comentarios en HTML -->
    ```
  - **CSS**:
    ```css 
    /* Comentarios en CSS */
    ```
  -  **JS**:
      ```js
      // Comenrio de una sola linea en JS
      /* Comentarios multilineas en JS*/
      ```
---
***OTRAS ETIQUETAS***
  
  ```html
  <h1>Texto muy grande</h1>

  <h2>Texto grande</h2>

  <h3>Texto algo más grande de lo normal</h3>

  <h4>Texto normal</h4>

  <h5>Texto pequeño</h5>

  <h6>Texto muy pequeño</h6>

  <big> Texto grande </big>

  <i> Texto en cursiva </i>

  <small> Texto pequeño </small>

  <strong> Texto fuerte </strong>

  <sub> Texto subíndice </sub>

  <sup> Texto superíndice</sup>

  <ins> Texto insertado </ins>

  <del> Texto borrado </del>

  <em> Otra forma de invocar cursiva</em>
  ```
---

![browser:html][img_html] 
```html
<!DOCTYPE html>
<!-- Esto es una buena practica para indicar el estandar de HTML 5 -->
<html>
<head><!-- Contiene todos los elementos no visuales de la pagina,metadatos, etc... -->
  <meta charset="utf-8"/>
  <!-- - Algunas etiquetas no necesitan ser cerradas como por ejemplo esta, que
  se coloca para que las tildes sean reconocidas por el navegador, pero es una
  buena practica cerrarla, otros ejemplos: <br>"pasaria a esto"<br/>, etc... -->
  <title>Mi primer archivo HTML</title>
  <!-- <title/> Sirve para poner un titulo a tu pagina. El titulo es muy importante
   ya que google le da mucha relevancia para que encuentren tu pagina en los navegadores -->
  <style type="text/css">/* Style es utilizada para definir un codigo en CSS, se coloca dentro de head */
  /* type="text/css" Esto es un atributo de la etiqueta */
  body
  {
    background-color: #AAAAFF;
    /* background-color es el atributo que cambia el color de fondo de tu pagina */
    color: white;
    /* Color es el atributo que cambia el color del texto de tu pagina */
    font-family: Helvetica;
    /* font-family es el atributo que cambia la fuente de tu pagina */
  }
  strong
  {
    background-color: #FFAAAA;
    /* Para ver el codigo hexagecimal del color que deseas escribe en google: #ffffff */
  }
  </style>
</head>
<body><!-- Contiene todos los elementos visuales de la pagina -->
  <p>Hola <strong>mama ya casi</strong> aprendo</p>
  <!-- <strong/> sirve para poner negrita -->
  <p>Esto es un parrafo</p>
  <!-- <p/> es un parrafo, RECUERDA: Todos los textos en HTML deben estar envueltos
  por etiquetas, la mas sencilla es <p/> -->
  <script type="text/javascript">
    // Script es utilizada para definir un codigo JavaScript, se coloca antes de terminar el body
    var $x = 1;
    // var declara una variable, como let o const
    var _y = 2;
    // Las variables tienen reglas: No pueden empezar con numeros (solo con letras), se diferencian mayusculas y minusculas, y no se pueden usar caracteres raros (como ñ o tildes) ni espacios.
    var Freddy_Vega1 = $x + _y;
    document.write("El valor de Z es " + Freddy_Vega1);
    // document.write es una funcion que escribe strings dentro de html, es como body pero dentro de JavaScript
  </script>
</body>
</html>
```
*Muy importantes las reglas para nombrar variables en JavaScript:* 
- *No pueden empezar con números.* 
- *Sólo con letras.*
- *Se diferencian mayúsculas y minúsculas.*
- *No se pueden utilizar caracteres "raros" como ñ o tildes.*
```js
var num = 10; // correcto
var num1 = 20;  // correcto
var n0m = "string"; // correcto
var 5num = 40; // ERROR INCORRECTO 
```
**YA CON ESTOS CONCEPTOS MAS CLAROS ESTAS LISTO PARA REALIZAR NUESTRO PRIMER PROYECTO 🤼‍**


***Version Html si te encuentras en Markdown ↗️***    [HTML](https://calypsobronte.github.io/basicprogramming/programmingFundamentals/HTML-CSS-JAVASCRIPT/Notes.html)

[![basica](../../img/siguiente.png)]()

 <br />
 <br />
 <br />
 <br />
 <br />
 <br />
 <center>
   <footer>
      <a style="float: left" rel="license" href="https://creativecommons.org/licenses/by-sa/3.0/deed.en_US"><img alt="Creative Commons License" style="border-width:0" src="../../img/cc.png"></a>
 <p>
 <br />
 <br />
       © 2018  -
         <a href="https://github.com/calypsobronte">Lina María Montaño Ramírez</a>
     </p>

   </footer>
   </center>


<!-- Enlaces de Imagenes -->
[img_html]: ../../img/html.png "Navegador"
[img_etiqueta]: ../../img/etiqueta.png "Etiquetas"
[img_etiquetas]: ../../img/etiquetas.png "Funcion de la etiquetas"

[gif_page]: ../../gif/page_html.gif "Gif .html"