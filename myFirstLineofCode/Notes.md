
[![basic](../img/home.png)](https://calypsobronte.github.io/basicprogramming/)

# Explicacion de video Mi primera linea de cogigo

Con este pordras conocer un poco la base de como crear codigo de una manera sencilla. [Ingresa al curso ¡Aca!][]

Para esto abrimos cual quier navegador el de tu preferencia. ([`Mozilla`][],[`Chrome`][])

En la siguiente grafica encontraras una forma resumidad de los que basicamente se maneja en la programacion. 
![basicProgrammig][basico]

Despues de esto abrimos nuestro navegador y abrimos una pestaña en blanco como se muestra acontinuacion:
![About:black][gif_page]

Despues de a ver ingresado la pagina en blanco le damos click derecho y le damos `inspeccionar` o por teclado Ctrl+Mayús+I

Alli encontraras en primer plano como esta estructurado una pagina web pero eso se vera mas adelante nos vamos a donde esta `consola`
![console:about][console]

Ya abierta la consola escribimos: 

```bash
alert("Mi nombre es Lina");
```
y debe aparecer una ventana emergente:
![console:alert][alert]

Despues vamos a guardar nuestro nombre por medio de las variables:

```bash
var nombre = "Lina";
```
le damos enter y se vera  `undefined` no te preocupes despues copias `nombre` y te saldra el nombre que almacenamos en la anterior variable:
![console:alert-var][gif_alert-var]

En esta siguiente grafica veras los demas pasos a seguir y te diviertas un poco 👩‍💻  👨‍💻
![console:var][gif_var]

Despues de esto vermos otra forma de mostrarnuestro nombre con `prompt`

```bash
nombre = prompt("Cual es tu nombre?");
```
este te pedira que ingreses tu nombre, te parece divertido pues intentalo :smiley:.
![console:prompt][gif_prompt]

Aqui te muestro un poco de la estructura de como se veria con html 💁‍

```html
<!DOCTYPE html>
<html>
<head>
	<title>Mi primer Codigo con Platzi</title>
</head>
<body>
<script type="text/javascript">
// aca empieza el codigo, es un lenguaje llamado javascript
	
//alert ("hola mundo :v");

//var nombre = "Lina";

// alert ("mi nombre es " + nombre);

//nombre = "juana la alpaca"

// de aca para arriba son bocetos, abajo es el codigo que se muestra

nombre = prompt ("Cual es tu nombre?");

alert ("mi nombre es " + nombre);

</script>

</body>
</html>
```

Por ultimo para seguir con las demas sesiones descargamos nuestro editor de codigo, existe una infinidad de editores, entre ellos esta:

Estos los utilizo yo 👩‍💻

**Vs Code**
![vscodedo][vscode]
[Descargas -> Vs code][]

**Atom**
![atomio][atom]
[Descargas -> Atom][]

Tambien esta estos editores 
![editores][editor]
![editores-1][editor-1]

[**Brackets**](http://brackets.io/ ),
[**Coda**](https://panic.com/coda/),
[**Sublime Text**](http://www.sublimetext.com/3), 
[**Dreamweaver**](https://www.adobe.com/products/dreamweaver.html),
[**Notepad++**](https://notepad-plus-plus.org/),
[**Netbeans**](https://netbeans.org/downloads/)
[**PhpStorm**](https://www.jetbrains.com/phpstorm/download/#section=linux)
[**Eclipse**](https://www.eclipse.org/downloads/)

***Version Html si te encuentras en Markdown :arrow_upper_right:***    [HTML](https://calypsobronte.github.io/basicprogramming/myFirstLineofCode/Notes.html)

  [![basica](../img/siguiente.png)](https://calypsobronte.github.io/basicprogramming/programmingFundamentals/what-is-html-css-js/Notes.html)

 <br />
 <br />
 <br />
 <br />
 <br />
 <br />
 <center>
   <footer>
      <a style="float: left" rel="license" href="https://creativecommons.org/licenses/by-sa/3.0/deed.en_US"><img alt="Creative Commons License" style="border-width:0" src="../img/cc.png"></a>
 <p>
 <br />
 <br />
       © 2018  -
         <a href="https://github.com/calypsobronte">Lina María Montaño Ramírez</a>
     </p>

   </footer>
   </center>




<!-- Enlaces de Webs -->
[Ingresa al curso ¡Aca!]:https://platzi.com/clases/programacion-basica/ "Basico de Programacion"
[`Mozilla`]:https://www.mozilla.org/es-ES/firefox/new/ "Firefox-Mozilla"
[`Chrome`]:https://www.google.es/chrome/index.html "Chrome"
[Descargas -> Vs code]:https://code.visualstudio.com/download
  "Vscode"
[Descargas -> Atom]:https://atom.io/
"Atom.io"


<!-- Enlaces de Imagenes -->
[basico]: ../img/ProgBasica-02.jpg  "Programacion Basica"
[vscode]: ../img/vscode.png  "Editor Vs Code"
[atom]: ../img/atom.png  "Editor Atom"
[console]: ../img/console.png "Console"
[alert]: ../img/alert.png "Ventana Emergente"
[editor]: ../img/editor.jpg "Editores"
[editor-1]: ../img/editor1.png "Editores"


<!-- Enlaces de Gifs -->

[gif_page]: ../gif/blackPage.gif "Paso a paso como ingresar a una pagina en blanco"
[gif_alert-var]: ../gif/console.gif "Variable"
[gif_var]: ../gif/consolename.gif "Name Var"
[gif_prompt]: ../gif/consoleprompt.gif "prompt"