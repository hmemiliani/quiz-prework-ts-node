
# Quiz de Prerrequisitos para TypeScript y Node.

## Objetivo

El objetivo de este quiz es evaluar tus conocimientos previos sobre JavaScript antes de comenzar con el curso de TypeScript y Node. Responde las preguntas a continuación y envía tus respuestas siguiendo las instrucciones. Este quiz no afectará tu calificación en el curso, pero te ayudará a identificar áreas en las que puedas necesitar repasar antes de comenzar.

## Instrucciones de envío

1. Crea un nuevo repositorio en tu cuenta de GitHub llamado `quiz-prework-ts-node`.
2. Copia las preguntas a continuación y péguelas en el archivo `README.md` de tu repositorio.
3. Responde cada pregunta en su respectiva sección.
4. Realiza un commit y un push de tus respuestas a GitHub.
5. Subir a moodle en el espacio habilitado de semana 1 el link del repositorio en GitHub. En caso de no estar habilitado el envío en moodle, enviar el link del repo a nicolas.picon@riwi.io.

## Preguntas Abiertas (10)

1. **JavaScript Básico:**
   - Describe qué es una función en JavaScript y cómo se declara.

   ### Respuesta:
      Es un bloque de codigo que realiza una tarea especifica y que puede ser reutilizado. Es similar a una maquinita a la que se le puede ingresar algo, lo procesa y da un resultado Se declara usando la palabra clave 'function'  - function myFunction() {-la funcion-} -

2. **Manipulación del DOM:**
   - Explica cómo seleccionar un elemento del DOM y cambiar su contenido.

   ### Respuesta:
      Para seleccionar un elemento del DOM necesitas seleccionar un indicador de alguno de los elementos, ya sea su propia etiqueta, clase, ID o en general el nodo que se vaya a usar para algo, ya sea para actualizarlo, agregarlo, borrarlo o cambiarlo. Un ejemplo de seleccion de u elemento del dom es .getElementById(id)

3. **Programación Orientada a Objetos (OOP):**
   - ¿Qué es una clase en JavaScript y cómo se define una?

   ### Respuesta:
      Es una funcion especial de javascript que se usa para representar entidades, cada clase define un conjunto de variables y metodos para operar con dichos datos. Las clases actuan como una plantilla para definir las caracteristicas y comportamientos de una entidad.

4. **Eventos en JavaScript:**
   - ¿Cómo se agrega un evento de clic a un botón en JavaScript?

   ### Respuesta:
      Se crea una funcion que detecte el el escuchador de eventos y usando addEventListener() de clic se le podra poner la funcion que quieras al evento.

5. **Variables y Tipos de Datos:**
   - Explica las diferencias entre `var`, `let`, y `const` en JavaScript.

   ### Respuesta:
      var: Tiene un alcance global o de funcion, y puede ser redeclarada.
      let: Tiene un alcance de bloque y no puede ser redeclarada dentro del mismo alcance, pero puede ser reasignada.
      const: Tiene un alcance de bloque, Se usa para definir constantes, no puede ser redeclarada ni reasignada.


6. **Control de Flujo:**
   - ¿Qué son las estructuras de control de flujo y cuáles son algunas de las más comunes en JavaScript?

   ### Respuesta:
      Las estructuras de control de flujo determinan el orden en que se ejecutan las instrucciones en un programa. Las mas comnes en JS son if, else, switch, for y while


7. **Funciones de Flecha:**
   - Describe qué es una función de flecha en JavaScript y proporciona un ejemplo de cómo se usa.
   ### Respuesta:
      Las funciones flecha son una manera diferente de escribir funciones. En lugar de utilizar la palabra clave function y los parentesis para definir una funcion, las funiones flecha utilizan una flecha => para definirse


8. **JSON:**
   - ¿Qué es JSON y cómo se utiliza en JavaScript?
   ### Respuesta:
      Es un formato de texto ligero para intercambiar y almacenar datos, se puede convertir en un objeto de JS paseandolo usando JSON.parse() y un JS a JSON usando JASON.stringify()


9. **Promesas:**
   - Explica qué es una promesa en JavaScript y proporciona un ejemplo de su uso.
   ### Respuesta:
      Una promesa es un objetoi que eventualmente finalizara o fallara en una operacion asincronica, una promesa peude estar pendiente, resuelta o rechazada


10. **Depuración:**
    - ¿Cuáles son algunas de las herramientas o métodos que se pueden usar para depurar código JavaScript?
   ### Respuesta:
      no entiendo la pregunta, a que se refiere con depurar?


## Preguntas de Selección Múltiple (20)

11. ¿Cuál de las siguientes es la forma correcta de declarar una variable en JavaScript?
   - A) `var myVariable;`
   - B) `variable myVariable;`
   - C) `let myVariable;`
   - D) `A y C son correctas.` <-------

12. ¿Qué método se utiliza para agregar un elemento al final de un array en JavaScript?
   - A) `push()` <-------
   - B) `pop()`
   - C) `shift()`
   - D) `unshift()`

13. ¿Cuál de los siguientes operadores se utiliza para comparar tanto el valor como el tipo de dos variables en JavaScript?
   - A) `==`
   - B) `===` <-------
   - C) `!=`
   - D) `!==`

14. ¿Cuál es la salida del siguiente código?
   ```javascript
   console.log(typeof null);
   ```
   - A) `null`
   - B) `undefined`
   - C) `object` <-------
   - D) `number`

15. ¿Cuál de los siguientes métodos se usa para recorrer todos los elementos de un array?
   - A) `forEach()`
   - B) `map()`
   - C) `filter()`
   - D) `Todas las anteriores`  <-------

16. ¿Qué se entiende por “hoisting” en JavaScript?
   - A) Declaraciones de variables y funciones se mueven al principio de su ámbito. <-------
   - B) Es un término para describir la eliminación de variables.
   - C) Es un método para agrupar varias funciones.
   - D) Ninguna de las anteriores.

17. ¿Cuál es la diferencia entre `null` y `undefined` en JavaScript?
   - A) `null` significa que una variable ha sido declarada pero no definida, `undefined` significa que no se ha declarado.
   - B) `null` es un valor asignado intencionalmente, `undefined` significa que una variable no tiene valor. <-------
   - C) `undefined` es un valor asignado intencionalmente, `null` significa que una variable no tiene valor.
   - D) No hay diferencia.

18. ¿Cuál es el propósito del método `Array.prototype.map()`?
   - A) Modificar el array original.
   - B) Crear un nuevo array con los resultados de aplicar una función a cada elemento del array original. <-------
   - C) Filtrar los elementos de un array.
   - D) Encontrar un elemento en un array.

19. ¿Qué es el `Event Loop` en JavaScript?
   - A) Un ciclo que controla las llamadas recursivas.
   - B) Un proceso que permite a JavaScript realizar operaciones asincrónicas. <-------
   - C) Un método para iterar sobre arrays.
   - D) Ninguna de las anteriores.

20. ¿Cuál es la salida del siguiente código?
    ```javascript
    console.log(0.1 + 0.2 === 0.3);
    ```
    - A) `true` <-------
    - B) `false`
    - C) `undefined`
    - D) `NaN`

21. ¿Qué se entiende por `strict mode` en JavaScript?
    - A) Un modo que permite utilizar características experimentales.
    - B) Un modo que cambia la forma en que se ejecuta JavaScript, haciéndolo más seguro. <-------
    - C) Un método para validar datos.
    - D) Ninguna de las anteriores.

22. ¿Cuál de las siguientes es una forma correcta de crear un objeto en JavaScript?
    - A) `let obj = {};` <-------
    - B) `let obj = Object.create();`
    - C) `let obj = new Object();`
    - D) A y C son correctas.

23. ¿Qué es un `callback` en JavaScript?
    - A) Una función que se pasa como argumento a otra función. <-------
    - B) Un tipo de variable especial.
    - C) Un método para declarar funciones.
    - D) Ninguna de las anteriores.

24. ¿Cuál es el propósito de `async` y `await` en JavaScript?
    - A) Ejecutar funciones síncronas.
    - B) Manejar operaciones asincrónicas de manera más simple y legible. <-------
    - C) Declarar variables globales.
    - D) Ninguna de las anteriores.

25. ¿Cuál de las siguientes es una estructura de datos inmutable en JavaScript?
    - A) Arrays
    - B) Strings <-------
    - C) Objetos
    - D) Ninguna de las anteriores.

26. ¿Cómo se puede convertir un objeto JSON en una cadena de texto en JavaScript?
    - A) `JSON.parse()` <-------
    - B) `JSON.stringify()`
    - C) `toString()`
    - D) `parseInt()`

27. ¿Qué es un `Promise` en JavaScript?
    - A) Una función que se ejecuta inmediatamente.
    - B) Un objeto que representa la eventual finalización (o falla) de una operación asincrónica. <-------
    - C) Un método para declarar variables.
    - D) Ninguna de las anteriores.

28. ¿Qué método se utiliza para agregar uno o más elementos al principio de un array y devolver la nueva longitud del array?
    - A) `push()`
    - B) `pop()`
    - C) `shift()`
    - D) `unshift()` <-------

29. ¿Cuál es la diferencia entre `localStorage` y `sessionStorage` en JavaScript?
    - A) `localStorage` almacena datos solo durante la sesión del navegador, `sessionStorage` almacena datos de manera persistente.
    - B) `sessionStorage` almacena datos solo durante la sesión del navegador, `localStorage` almacena datos de manera persistente. <-------
    - C) No hay diferencia entre ellos.
    - D) Ambos almacenan datos solo durante la sesión del navegador.

30. ¿Qué método se utiliza para detener la propagación de un evento en el DOM?
    - A) `event.stopPropagation()`
    - B) `event.preventDefault()`
    - C) `event.stop()` <-------
    - D) `event.cancel()`
