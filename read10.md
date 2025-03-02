## ¿Qué es "Control Flow" (Control de Flujo)?
El **Control de Flujo** en programación se refiere al orden en que las instrucciones de un programa se ejecutan. En JavaScript, esto implica cómo se procesan las declaraciones, funciones y estructuras de control (como bucles y condiciones) para determinar el camino que sigue el programa durante su ejecución. Por ejemplo, las declaraciones condicionales (`if`, `else`) y los bucles (`for`, `while`) permiten que el programa tome decisiones y repita acciones basadas en condiciones específicas. 

## ¿Qué es una "function" (Función) de JavaScript?
Una **función** en JavaScript es un bloque de código diseñado para realizar una tarea específica. Se puede definir una función utilizando la palabra clave `function`, seguida de un nombre, una lista de parámetros entre paréntesis y un bloque de código entre llaves. Por ejemplo:
```javascript
function saludar(nombre) {
  return `Hola, ${nombre}`;
}
```

## ¿Cuántas veces se ejecutará un bucle "while"?
Un bucle while en JavaScript continuará ejecutándose mientras la condición especificada sea verdadera. La estructura básica es:
```javascript
while (condición) {
  // código a ejecutar
}
```
Si la condición es inicialmente falsa, el código dentro del bucle no se ejecutará ninguna vez. Si la condición es verdadera, el bucle se ejecutará repetidamente hasta que la condición se vuelva falsa. Es importante asegurarse de que la condición eventualmente se vuelva falsa para evitar bucles infinitos.

## ¿Qué método usarías para agregar un elemento al final de un array y cómo se utiliza?
Para agregar un elemento al final de un array en JavaScript, se utiliza el método push(). Este método añade uno o más elementos al final de un array y devuelve la nueva longitud del array. Por ejemplo:
let frutas = ['manzana', 'plátano'];
frutas.push('naranja');
console.log(frutas); // ['manzana', 'plátano', 'naranja']
En este ejemplo, el método push() añade 'naranja' al final del array frutas.

