[![basic](../../img/home.png)](https://calypsobronte.github.io/basicprogramming/)
# Primeros pasos en el navegador con alert

![basicProgrammig][basico]

1. Abrir nuestro navegador de preferencia `Google`, `Firedox`, `Opera`

2. Das click derecho en el mouse e `Inspeccionar`

3. Despues nos vamos para la `Consola`, desde ahí puedes escribir `JavaScript` sin tener que crear un archivo.

Escribe:
```console
alert("Hola mamá, estoy programando");
```
 Miremos un poco de Algebra Basica.
*No te asustes sera muy basico.* 

> ***Notas:*** 

>>- *`Funciones`Lo que has hecho es ejecutar una función, estas son colecciones de código que hacen algo y van dentro de paréntesis `()`.* 

>>- *`alert` es una orden.*

>>- *`Las comillas` `""` delimitar un texto libre o sea una cadena de texto `(String)`.*

>>- *`Parámetros` información de una función para lograr un proceso, y van dentro de los paréntesis `()` y con comillas `""`.*

>>- *`Punto y coma` `;` alguno de los lenguajes sus codigos terminan en punto y coma, y es para decirle al navegador que hasta ahí termina la instrucción.*

>>- *`Concatenar` unir o sumar caracteres y/o variables. Cuando sumamos un número a un texto ambos se vuelven textos y eso se llama concatenación*

>>- *`bloque` es un conjunto de lineas de codigo con una estructura definida-*

>>- `Codigo de linea independiente` lleva `;`
>>- `{ }` este no lleva `;`.* 


- `var es igual a  variable` *declara la existencia de una variable en memoria.*

- *`Operador =` el igual es para asigna el valor de la variable.*


Variables (var)
La palabra var declara la existencia de una variable. 
```javascript    
var x = 1;
var y = 2;
var z = x + y;
```

la palabra `var` declara que es una variable,
el nombre de la variable, en este caso es “x”
luego viene el operador (=), que asigna el valor de la variable
y por último tenemos el valor, en este caso es el número 1. Lo mismo en la segunda línea. 

En la tercera línea hemos asignado como valor una operación matemática.  Lo que sucede aquí es que primero se realiza la operación matemática y luego se le asigna como valor a la variable. 

```javascript
alert(“el valor de z es” + z);
```
En esta grafica lo visto anteriormente:
![console:var][gif_page]

***Version Html si te encuentras en Markdown :arrow_upper_right:***    [HTML](https://calypsobronte.github.io/basicprogramming/programmingFundamentals/first-steps-in-the-browser-with-alert/Notes.html)

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


<!-- Enlaces de Gifs -->
[gif_page]: ../../gif/alert.gif "Pasos con alert"

[basico]: ../../img/ProgBasica-06.jpg  "Programacion Basica"
