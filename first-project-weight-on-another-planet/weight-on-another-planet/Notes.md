[![basic](../../img/home.png)](https://calypsobronte.github.io/basicprogramming/)
# Peso en otro planeta

*¿Cuánto pesas en la tierra?, calculemos tu peso en otro planeta*

*Creemos nuestro primer algoritmo que nos permita saber nuestro peso en otro planeta, luego escribamos esto en código usando JavaScript.*

![basicProgrammig][basico]

***Recuerda:***

- *Los títulos se pueden agregar con la etiquetas `h1`,`h2`,`h3`,`h4`,`h5`,`h6`.*
- *`prompt(“string”);` Muestra un diálogo con mensaje opcional, que solicita al usuario que introduzca un texto. La funcion `prompt` funciona igual que un `alert` y sirve para obtener datos del usuario.*

- *`document.write(“string”);` Escribe texto en el document de mi documento, como se estuviera escribiendo directamente en el `body`.*

- *`parseInt();` Funcion convierte las variables de tipo `float = decimales` a tipo `int = entero`.*

- *`parseFloat();` funcion que convierte las variables de tipo `int = entero `a tipo `float = flotante`.*

- *`.toFixed(parm);` Elimina los decimales que sobran y redondea el numero. En el parametro le indicas el numero de decimales que quieres conservar.*

```html
<script>
    var g_tierra = 9.8;
    var g_marte = 3.7;
    var g_jupiter = 24.8;
    var peso = 77;
    var peso_final;
    peso_final = peso * g_marte / g_tierra;
    peso_final = parseInt(peso_final);
    document.write(peso_final)
</script>
```

Archivo ejemplo: [pages](../../first-project-weight-on-another-planet/weight-on-another-planet/peso.html)
Archivo peso planeta: [pages](../../first-project-weight-on-another-planet/weight-on-another-planet/peso_planeta.html)

***Version Html si te encuentras en Markdown ↗️***    [HTML](https://calypsobronte.github.io/basicprogramming/programmingFundamentals/first-project-weight-on-another-planet/weight-on-another-planet/Notes.html)

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
[basico]: ../../img/ProgBasica-07.jpg  "Programacion Basica"