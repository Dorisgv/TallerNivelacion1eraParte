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
     - Notacion de punto:
       En esta forma, utilizas un punto seguido del nombre de la propiedad para acceder a su valor.
     - En que caso podemos utilizar cada una.
       Cuando el nombre de la propiedad es conocido y está compuesto por caracteres válidos para identificadores en el lenguaje (como letras, números y guiones bajos).
       En situaciones generales donde la claridad y la concisión son importantes.
     - Notacion de corchetes:
       En esta forma, utilizas corchetes y el nombre de la propiedad como una cadena para acceder al valor de la propiedad.
     - En que caso podemos utilizar cada una.
       Cuando el nombre de la propiedad es dinámico o se determina durante la ejecución del programa.
       Para acceder a propiedades cuyos nombres contienen espacios, caracteres especiales o son palabras reservadas.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

13. ¿Existe alguna forma de recorrer las propiedades de un objeto? En caso negativo, explicar por qué no es posible y en caso positivo proporcionar un ejemplo. Mencionar
    una situación en la cual sea muy útil recorrer las propiedades de un objeto.
    Rta:
    Sí, es posible recorrer las propiedades de un objeto en muchos lenguajes de programación, incluyendo JavaScript. Una de las formas más comunes de hacer esto es mediante un bucle, 
    como el bucle for...in. Sin embargo, es importante destacar que no todos los lenguajes de programación admiten esta funcionalidad directamente.
    EJEMPLO:
             let persona = {
              nombre: "Juan",
              edad: 25,
              profesion: "Desarrollador"
            };

            for (let propiedad in persona) {
            console.log(propiedad + ": " + persona[propiedad]);
         }
SITUACION UTIL:
Recorrer las propiedades de un objeto puede ser muy útil en situaciones en las que necesitas realizar operaciones en todas las propiedades del objeto dinámicamente. Por ejemplo, podrías querer imprimir todas las propiedades y sus valores, realizar cálculos basados en los valores de las propiedades, o copiar ciertas propiedades de un objeto a otro.
EJEMPLO:
function imprimirPropiedades(objeto) {
  for (let propiedad in objeto) {
    console.log(propiedad + ": " + objeto[propiedad]);
  }
}

let persona = {
  nombre: "Ana",
  edad: 30,
  profesion: "Ingeniera"
};

imprimirPropiedades(persona);

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
14. ¿Por qué son útiles los objetos en la programación web y qué tipos de datos pueden almacenar?
    Rta:
    Los objetos son fundamentales en la programacion web ya que permiten organizar y estructurar datos de manera eficiente. En javascript, los objetos son un tipo de estructura de 
    datos clave, aqui tenemos algunas razones:
    - Organizacion de datos, flexibilidad, acceso eficiente, encapsulamiento, interaccion con el DOM.
    Los tipos de datos que almacenan los objetos en javascript son colecciones de pares clave - valor, y las claves (o propiedades) pueden ser cadenas de texto simbolos pueden ser:
    - Cadenas de texto.
    - Numeros
    - Booleanos
    - Otros objetos
    - Arreglos
    - Funciones
    - Null y Undefined
    - Expresiones regulares.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
15. ¿Qué es un array en JavaScript y por qué son esenciales?
    Rta:
    Es un tipo de estructura que permite almacenar y organizar datos de manera secuencial. es una coleccion ordenada de elementos , donde cada elementopuede ser de cualquier tipo de 
    datos, incluyendo numeros, cadena de texto, objetos, funciones y otros arrays.
    Aqui, tenemos algunas razones por las cuales son esenciales en javascript:
    - Almacenamiento de datos estructurados
    - Iteraccion y acceso eficiente
    - Manejo de conjuntos de datos dinamicos
    - Operaciones de transformacion y manipulacion sencillas
    - Estructuras de datos comunes
    - Interaccion con API's y datos externos.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
16. ¿Cómo acceder a un elemento dentro de un array? Explicar con un ejemplo.
    Rta:
    Para acceder, puedes usar la notacion de corchetes '[]' con el indice del elemento que deseas obtener. Recuerda que los indices en javascript comienzan desde cero.
    EJEMPLO:
    
    // Definir un array de números
       let numeros = [10, 20, 30, 40, 50];

    // Acceder al primer elemento (índice 0)
       let primerElemento = numeros[0];
       console.log("Primer elemento:", primerElemento);

    // Acceder al tercer elemento (índice 2)
       let tercerElemento = numeros[2];
       console.log("Tercer elemento:", tercerElemento);

    // Acceder al último elemento (longitud - 1)
       let ultimoElemento = numeros[numeros.length - 1];
       console.log("Último elemento:", ultimoElemento);

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
17. Mencionar al menos tres funciones de arrays y describir su utilidad en la programación
    web.
    Rta:
    1. map():
       La función 'map' crea un nuevo array con los resultados de llamar a una funcion proporcionada en cada elemento del array original. Es util para transformar o mapear cada 
       elemento del array de una forma especifica.
    2. filter():
       La función filter crea un nuevo array con todos los elementos que pasan la prueba implementada por la función proporcionada. Es útil para filtrar elementos que cumplen ciertos 
       criterios.
    3. reduce():
       La función reduce aplica una función acumuladora a cada elemento de un array, de izquierda a derecha, para reducirlo a un único valor. Es útil para realizar operaciones de 
       agregación o resumen en los elementos del array.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
18. Proporcionar un ejemplo de cómo se utiliza una función de array para transformar y filtrar datos en un array.
    Rta:
    Supongamos que tenemos un array de objetos que representan productos y deseamos realizar dos operaciones:
    	1. TRANSFORMAR:
           Duplicar el precio de cada producto.
    	2. FILTRAR:
           Obtener solo los productos que tienen un precio mayor o igual a $50.
EJEMPLO:
    
// Array de productos
let productos = [
  { nombre: "Laptop", precio: 800 },
  { nombre: "Teléfono", precio: 300 },
  { nombre: "Tablet", precio: 150 },
  { nombre: "Smartwatch", precio: 80 },
  { nombre: "Cámara", precio: 200 },
];

// Transformar: Duplicar el precio de cada producto usando map
let preciosDuplicados = productos.map(function(producto) {
  return { ...producto, precio: producto.precio * 2 };
});

console.log("Productos con precios duplicados:", preciosDuplicados);

// Filtrar: Obtener solo productos con precio mayor o igual a $50 usando filter
let productosFiltrados = productos.filter(function(producto) {
  return producto.precio >= 50;
});

console.log("Productos con precio mayor o igual a $50:", productosFiltrados);
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
PREGUNTAS PRACTICASSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSS.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
...MODULO SOBRE HTML, CSS Y RESPONSIVE DESIGN...
Preguntas teóricas.

1. ¿Qué significa HTML y cuál es su función en el desarrollo web?
   Rta:
   Significa "Hipertext Markup Language" (Lenguaje de Marcado de Hipertexto). Es un estandar que se utiliza para la creacion y el diseño de paginas web.
   Su funcion principalmente en el desarrollo web es definir y estructurar el contenido de una pagina web. Aqui tenemos algunos puntos clave sobre la funcion de HTML:
   - Estructuracion del contenido, Definicion semantica,Enlaces y navegacion, Inclusion de multimedia, Formularios y recoleccion de datos, compatibilidad y accesibilidad.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
2. ¿Cuál es la estructura básica de un documento HTML? Describir las etiquetas esenciales.
   Rta:
   La estructura de un documento HTML sigue un formato estandar que incluye ciertas etiquetas esenciales:
   Aqui un ejemplo de un formato HTML:
   <!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Título de la Página</title>
</head>
<body>
    <!-- Contenido de la página va aquí -->
</body>
</html>

Algunas etiquetas esenciales son las siguientes:

<!DOCTYPE html>:
Esta declaración define la versión de HTML que estás utilizando. En este caso, html indica que estás utilizando HTML5.

<html>:
La etiqueta raíz que envuelve todo el contenido del documento HTML. El atributo lang se utiliza para especificar el idioma de la página, lo que puede ser útil para accesibilidad y motores de búsqueda.

<head>:
Contiene meta información sobre el documento, como la codificación de caracteres, la declaración del viewport (para diseño responsivo), y el título de la página.

<meta charset="UTF-8">:
Especifica la codificación de caracteres del documento. UTF-8 es una codificación ampliamente utilizada que es capaz de representar una amplia gama de caracteres.

<meta name="viewport" content="width=device-width, initial-scale=1.0">:
Esta etiqueta es crucial para el diseño responsivo. Define cómo el contenido debe ser renderizado en dispositivos con diferentes anchos de pantalla (width=device-width) y establece la escala inicial (initial-scale).

<title>:
Define el título de la página, que se muestra en la barra de título del navegador o en las pestañas de la página. También es importante para el SEO (Optimización de Motores de Búsqueda).
	
<body>:
Contiene todo el contenido visible de la página web, como texto, imágenes, enlaces, formularios, etc.
	
Comentarios HTML:
Los comentarios en HTML se escriben entre <!-- y -->. Son útiles para agregar notas en el código que no afectan la visualización del contenido y son especialmente útiles para documentar o desactivar temporalmente partes del código.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
3. ¿Qué es CSS y cuál es su propósito en el desarrollo web?
   Rta:
   CSS, significa "Cascading Style Sheets" (Hojas de estilos en cascada) es un lenguaje de diseño utilizado para describir el aspecto y el formato de un documento HTML. CSS permite 
   preparar la presentacion (estilos) del contenido(estructura y semantica) en el desarrollo web.
   - Su proposito principal es controlar el diseño visual y la apariencia en las paginas web.
   Algunas principales propositos y funciones de css y en el desarrollo web son:
   - Estilo visual, Diseño responsivo, Consistencia y mantenimiento, Accesibilidad, Facilita la implantacion de diseños, Impresion y medios, Animaciones y transiciones.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
4. ¿Qué son selectores CSS, cuáles son los principales tipos de selectores y porqué es importante entender la especificidad en el contexto de las hojas de estilo en cascada(CSS)? 
   Describir al menos tres tipos de selectores CSS y cómo la especificidad afecta a la aplicación de estilos en un proyecto de desarrollo web Frontend. Proporcionar
   ejemplos de situaciones en las que se utiliza la especificidad de selectores para resolver conflictos de estilos.
   Rta:
   


    























