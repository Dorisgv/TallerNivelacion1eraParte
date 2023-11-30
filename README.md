# TallerNivelacion1eraParte
DORIS GUERRERO
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
MODULO #1 -Preguntas!!

1.	¿Qué es lógica en el contexto de la programación? Y explicar por qué es importante en el desarrollo web Frontend.
  Rta: Es la manera de organización y planificación coherente de instrucciones para realizar una tarea específica y que su fin sea logrado.
  -	Es importante, porque es una parte fundamental para este tipo de desarrollo, ya que determina como interactúan y se comportan los elementos de una interfaz de usuario.
  Permitiendo construir interfaces atractivas visualmente, pero más aun aplicándoles funcionalidad de una manera eficaz y eficiente en la interacción con los usuarios.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
2.	¿Definir el concepto de “Algoritmo” y proporcionar un ejemplo sencillo de un algoritmo relacionado con la lógica de programación?
  Rta: Es una secuencia de instrucciones finitas que llevan a cabo una serie de procesos para dar respuesta o solución a determinados problemas.
  Ejemplo:
  Determinar el número máximo de una lista.
  -inicio
  -definición de una lista: listaNum= [3,4,2,1,7]
  -inicializamos una variable para almacenar el num max: numMax=listaNum
  -para cada número en la lista:
	  -si el número actual es mayor que el numMax:
		  -actualizar el valor de numMax con el número actual.
  -imprimir el numero encontrado: numMax
  -Fin.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
3. ¿Que son estructuras de control en la programación?, ¿Cuáles  son  los  tipos  de estructuras de control y las estructuras más comunes de cada tipo?, Describir al menos 
  dos  tipos  de  estructura  de  control,  explicar  por  qué  son  importantes  y  proporcionar ejemplos de cada uno de cómo se utilizan en el desarrollo web Frontend.
  Rta: Son estructuras que controlan las secuencias lógicas de un algoritmo para cumplir con cierta condición, evaluar un error o repetir varios procesos.
  Existen 2 tipos de estructuras de control: condicionales y ciclos.
  CONDICIONALES:
  Los condicionales evaluán si una expresion se cumple o no, dependiendo de esto realiza una determinada sentencia en el algoritmo.
  Existen tres tipos de condicionales:
    * if/else: evalúa si la expresión es verdadera o falsa.
    * switch: evalúa si la expresión es igual a diferentes casos.
    * try/catch: evalúa si un algoritmo contiene errores.
  CICLOS:
  Los ciclos o tambien llamados bucles evalúan si una expresión  cumple o no y repite una serie de sentencias que conforman el algoritmo.
  Existen 3 tipos de ciclos:
    * for: repite una serie de sentencias con un límite conocido.
    * while: repite una serie de sentencias con un límite desconocido.
    * do-while: ejecuta una primera sentencia y después repite una serie de sentencias con un límite desconocido.
  EJEMPLOS:
  Condicional (if/else)

<script>
  var usuarioConectado = true;
  
  if (usuarioConectado) {
    document.write("<p>Bienvenido, usuario. ¡Disfruta de tu experiencia!</p>");
  } else {
    document.write("<p>Por favor, inicia sesión para acceder a todas las funciones.</p>");
  }
</script>

Ciclos (for)

<script>
  // Estructura de ciclos para generar una lista de números
  document.write("<ul>");
  for (var i = 1; i <= 5; i++) {
    document.write("<li>Número " + i + "</li>");
  }
  document.write("</ul>");
</script>
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
4. Describir cómo se declaraban variables y constantes en JavaScript antes de la introducción de ECMAScript 6 (ES6). Explicar cómo ES6 mejoró la declaración de 
   variables y constantes, y mencionar los problemas que esta mejora resuelve en el desarrollo web Frontend.
   Rta:
   Antes de la introduccion de ECMAScript6 (ES6), la forma de declarar variables y constantes en JavaScript se realizaba utilizando las palabras clave 'var' para variables y 'const' 
   para constantes.
   
   ECMAScript 6 (ES6) mejoró la declaración de variables en JavaScript de las siguientes maneras:
   let para Ámbito de Bloque:
      Antes de ES6, var tenía ámbito de función. let permite declarar variables con ámbito de bloque, evitando problemas asociados con var.
   
   const para Constantes:
      Antes de ES6, no había una forma clara de definir constantes. ES6 introdujo const, que declara variables que no pueden ser reasignadas después de la inicialización.

   Evita Problemas de Elevación (Hoisting):
      Con let y const, las variables no se elevan al inicio de su ámbito, evitando comportamientos inesperados asociados con el hoisting de variables declaradas con var.
      Estas mejoras aumentan la claridad del código, reducen errores potenciales y facilitan la escritura de programas más robustos.

   Ámbito Controlado:
      let y const ofrecen ámbitos más precisos, evitando problemas de contaminación global.
   Evita Reasignaciones Indeseadas:
      const previene cambios no deseados al declarar constantes inmutables.
   Código Más Predecible:
      let y const proporcionan claridad en la intención del código, facilitando la comprensión.
   Protección contra Hoisting:
      Evita sorpresas causadas por el hoisting al declarar variables con let y const.
   Fomenta Desarrollo Estructurado:
      Facilita prácticas de desarrollo más estructuradas y comprensibles.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
5. ¿Cómo  se  declaran  las  funciones  en  JavaScript  y  cuál  es  la  diferencia  entre  una 
   declaración  de  función,  una  expresión  de  función  y  una  función  de  flecha  (arrow 
   function)? Proporcionar ejemplos de cada una.

   Rta: 
   En JavaScript, las funciones se declaran usando la palabra clave function. La sintaxis básica para declararla es la siguiente:
   function nombreFuncion([parametros]) {
  // código de la función
}
nombreFuncion= es el nombre de la función.
[parametros]= es una lista opcional de parámetros que la función aceptará. Los parámetros se separan por comas.
// código de la función= es el código que la función ejecutará.

La principal diferencia es la sintaxis entre ellas.
Ej: Declaraciones de función.
    function sumar(a, b) {
  return a + b;
}
Ej: Expresiones de función.
    (a, b) => a + b
Ej: Funciones de flecha.
    (param1, param2, ...) => expression
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
6. ¿Por qué es necesario el uso de funciones en el desarrollo web Frontend? Enumerar al 
menos tres razones fundamentales y proporcionar ejemplos de situaciones en las que 
las funciones son esenciales. Además, mencionar la ventaja de las funciones flecha en 
el contexto de estas razones.

1. Organización del código:
   Las funciones permiten organizar el código en bloques lógicos, lo que facilita su comprensión y mantenimiento. Por ejemplo, una función podría utilizarse para cargar un conjunto de 
   datos, validar un formulario o realizar una operación matemática.
   Ej:
      Un desarrollador está creando una aplicación web que permite a los usuarios registrarse. Para organizar el código, podría crear una función que valide los datos del formulario de 
      registro. Esta función podría llamarse validarFormularioRegistro().
3. Reutilización de código:
   Las funciones se pueden reutilizar en diferentes partes de una aplicación web, lo que ahorra tiempo y esfuerzo a los desarrolladores. Por ejemplo, una 
   función que se utiliza para mostrar un mensaje de error podría utilizarse en varias páginas de una aplicación.
   Ej:
      Un desarrollador está creando una aplicación web que utiliza un menú desplegable en varias páginas. Para reutilizar el código, podría crear una función que cree el menú 
      desplegable. Esta función podría llamarse crearMenuDesplegable().
5. Mejora de la mantenibilidad del código: Las funciones ayudan a mejorar la mantenibilidad del código al hacer que sea más fácil encontrar y corregir errores.
   Ej:
      Un desarrollador está creando una aplicación web que utiliza una función para aplicar un estilo de negrita a un texto. Si el desarrollador necesita cambiar el estilo de negrita, 
      puede hacerlo fácilmente porque el código relacionado con el estilo está agrupado en la función.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
7. ¿Cuál es la diferencia entre parámetro y argumento?
    Rta:
    La diferencia es que el parámetro es una variable que se declara en la definición de una función, procedimiento o método, mientras que el argumento es 
    el valor que se pasa a la función, procedimiento o método cuando se llama.
    En otras palabras, el parámetro es la variable que recibe el valor del argumento.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
8. Definir el concepto de Callback y proporcionar un ejemplo práctico.
   Rta:
   Una callback es una función que se pasa como argumento a otra función. La función externa invocará a la función callback cuando se complete la operación para la que fue creada.
   Las callbacks se utilizan a menudo en programación asincrónica para permitir que una función se ejecute de forma independiente de la función que la llamó.
   Ej:
      const boton = document.querySelector("button");

      boton.addEventListener("click", function() {
         console.log("Botón pulsado");
      });
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
9. ¿Qué  es  el  hoisting  en  JavaScript  y  cómo  afecta  a  las  variables  y  funciones? 
   Proporcionar ejemplos de hoisting en declaraciones de variables y funciones.
   Rta:
   el hoisting es un comportamiento en el que las declaraciones de variables y funciones se mueven al principio del ámbito en el que se encuentran, antes de que se ejecuten otras 
   líneas de código en el mismo ámbito.
   
   El hoisting afecta a las variables y funciones de la siguiente manera:

   Variables: Las variables declaradas sin inicialización se inicializan con el valor undefined.
   Funciones: Las funciones declaradas se mueven al principio del ámbito en el que se encuentran, pero no se ejecutan.

   EJEMPLOS:
   	function saludar() {
  console.log("Hola");
}

saludar();
console.log("Hola");
-----------------------------------
	var x;
console.log(x); // Error: ReferenceError: x is not defined

x = 1;
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
10.  Definir brevemente el concepto de objeto en JavaScript y cuál es la visión general sobre este concepto. Indicar, también cómo se declaran estas estructuras de datos.
     Rta:
     un objeto es una colección de datos relacionados y/o funcionalidad (que generalmente consta de algunas variables y funciones, que se denominan propiedades y métodos cuando están 
     dentro de objetos).
     es una forma de agrupar datos y funcionalidad relacionados. Los objetos se pueden utilizar para representar cosas del mundo real, como personas, lugares o cosas.
     se declaran con const o let.
     const persona = {
  	nombre: "Juan Pérez",
  	edad: 30,
  	sexo: "masculino",
	  };
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
11. ¿Qué son propiedades?, y ¿Cuál es la diferencia entre una propiedad y un método en un objeto?
    Rta:
    Las propiedades son una caracteristica de un objeto. Representa un dato o un valor que está asociado con el objeto. Las propiedades se pueden usar para almacenar datos, como el 
    nombre, la edad o la altura de una persona.
    La principal diferencia entre una propiedad y un método es que una propiedad almacena datos, mientras que un método realiza una acción. Las propiedades se pueden usar para 
    almacenar datos relacionados con un objeto, como el nombre, la edad o la altura de una persona. Los métodos se pueden usar para realizar acciones relacionadas con un objeto, como 
    caminar, hablar o correr.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
 12. Explicar las dos formas de acceder a una propiedad de objetos e indicar las situaciones en que conviene usar una manera sobre la otra.
     Rta:
     hay dos formas principales de acceder a las propiedades de un objeto: la notación de punto (dot notation) y la notación de corchetes (bracket notation).
     
     






















