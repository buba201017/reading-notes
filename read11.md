
## ¿Qué es el DOM?
El **DOM (Document Object Model)** es una representación estructurada del contenido de un documento HTML o XML en forma de árbol. Cada elemento en la página web se convierte en un nodo dentro de este árbol, permitiendo que los scripts, como los escritos en JavaScript, interactúen con la estructura y el contenido del documento.



## Relación entre el DOM y JavaScript
JavaScript usa el DOM para manipular dinámicamente los elementos de una página web. A través del DOM, JavaScript puede:
- Modificar el contenido de los elementos HTML.
- Cambiar atributos y estilos CSS.
- Responder a eventos como clics y cambios de entrada.

El DOM actúa como una interfaz que conecta JavaScript con la estructura de la página web, permitiendo que los desarrolladores creen experiencias interactivas y dinámicas.



## Seleccionar un elemento del DOM por su ID
Para seleccionar un elemento del DOM por su ID, se usa el método `document.getElementById()`. Su sintaxis es:

```javascript
let elemento = document.getElementById("miElemento");
```
let titulo = document.getElementById("titulo-principal");
console.log(titulo.textContent); // Muestra el texto dentro del elemento con ID "titulo-principal"


## cambiar el color de fondo de un elemento en el DOM
Para cambiar el color de fondo de un elemento en el DOM, se usa la propiedad style.backgroundColor. Ejemplo de implementación:

let caja = document.getElementById("miCaja");
caja.style.backgroundColor = "blue";

Esto cambiará el color de fondo del elemento con ID miCaja a azul.