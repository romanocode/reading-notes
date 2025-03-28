# Read 09: Introducción a Javascript

### 1. ¿Cuáles son los diferentes tipos de datos en JavaScript?

- **Primitivos**:  
  - `string` → `"Hola"`  
  - `number` → `42`, `3.14`  
  - `boolean` → `true`, `false`  
  - `undefined` → `let x;`  
  - `null` → `let y = null;`  
  - `bigint` → `123n`  
  - `symbol` → `Symbol('id')`  
- **Objetos**: `Object`, `Array`, `Function`  

### 2. ¿Cómo se usan if y else en JavaScript?

Permiten ejecutar código según una condición.  

```javascript
let edad = 18;
if (edad >= 18) {
    console.log("Mayor de edad");
} else {
    console.log("Menor de edad");
}
```

### 3. ¿Cuáles son los tipos de operadores en JavaScript?

**Aritméticos**: +, -, *, /, %, **

```javascript
let suma = 5 + 3; // 8
let potencia = 2 ** 3; // 8
```

**Comparación**: ==, ===, !=, !==, >, <, >=, <=

**Lógicos**: &&, ||, !

**Asignación**: =, +=, -=, *=, /=

**Ternario**: condición ? valor1 : valor2

### 4. ¿Cómo se declara una variable y diferencias entre var, let y const?

- `var`: Alcance de función, permite redeclaración.
- `let`: Alcance de bloque, permite reasignación.
- `const`: Alcance de bloque, no permite reasignación.

```javascript
var a = 10;
let b = 20;
const c = 30;
```
