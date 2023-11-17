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
5. 


