## ¿Cuáles son los diferentes tipos de datos que se pueden utilizar en JavaScript y cómo se diferencian entre sí?
En JavaScript, existen siete tipos de datos primitivos:
- **String**: Representa una secuencia de caracteres. Se define entre comillas simples (`'...'`), dobles (`"..."`) o acentos graves (`` `...` ``). Ejemplo: `'Hola, mundo'`.
- **Number**: Incluye tanto números enteros como de punto flotante. Ejemplo: `42` o `3.14`.
- **BigInt**: Permite representar números enteros de gran tamaño que exceden las limitaciones del tipo `Number`. Se define añadiendo una 'n' al final del número. Ejemplo: `123456789012345678901234567890n`.
- **Boolean**: Solo puede tener dos valores: `true` o `false`. Es útil para representar valores de verdad.
- **Undefined**: Indica que una variable ha sido declarada pero no se le ha asignado un valor.
- **Null**: Representa la ausencia intencional de cualquier valor.
- **Symbol**: Es un valor único e inmutable, comúnmente utilizado como identificador de propiedades de objetos.
Además, JavaScript tiene el tipo `Object`, que es una colección de propiedades y se utiliza para almacenar conjuntos de datos y entidades más complejas. ([developer.mozilla.org](https://developer.mozilla.org/es/docs/Web/JavaScript/Guide/Grammar_and_types))

---

## ¿Cómo se utilizan las estructuras condicionales if y else en JavaScript, y qué propósito cumplen dentro de un programa?
Las estructuras condicionales `if` y `else` permiten ejecutar bloques de código basándose en condiciones específicas. Su sintaxis básica es:
```javascript
if (condición) {
  // Código si la condición es verdadera
} else {
  // Código si la condición es falsa
}
```

## ¿Cuáles son los diferentes tipos de operadores en JavaScript y cómo se utilizan los operadores aritméticos para realizar cálculos?
Tipos de operadores en JavaScript:
Aritméticos:
+: Suma
-: Resta
*: Multiplicación
/: División
%: Módulo (resto de la división)
**: Exponenciación

Asignación:
=: Asignación simple
+=: Asignación con suma
-=: Asignación con resta
*=: Asignación con multiplicación
/=: Asignación con división
%=: Asignación con módulo


Comparación:
==: Igualdad (compara solo valores)
===: Igualdad estricta (compara valor y tipo)
!=: Desigualdad
!==: Desigualdad estricta
>: Mayor que
<: Menor que
>=: Mayor o igual que
<=: Menor o igual que

Lógicos:
&&: AND lógico
||: OR lógico
!: NOT lógico

## ¿Cómo se declara una variable en JavaScript y cuáles son las diferencias entre var, let y const en cuanto a su alcance y mutabilidad?
Declaración de variables en JavaScript:
Las variables pueden declararse con var, let y const:

var:
Alcance: De función.
Hoisting: Se eleva al inicio del contexto de ejecución.
Mutabilidad: Puede reasignarse.

let:
Alcance: De bloque ({}).
Hoisting: Se eleva pero no se inicializa.
Mutabilidad: Puede reasignarse.

const:
Alcance: De bloque ({}).
Hoisting: Se eleva pero no se inicializa.
