# Read 10: Arreglos y Control de Flujo

1. **¿Qué es “Control Flow” (Control de Flujo)?**  
   Es el orden en que se ejecutan las instrucciones de un programa, incluyendo condicionales (`if`, `switch`), bucles (`for`, `while`) y funciones.  

2. **¿Qué es una “function” (Función) de JavaScript?**  
   Es un bloque de código reutilizable que se ejecuta cuando se llama. Se define con `function nombre() {}` o con funciones de flecha `() => {}`.  

3. **¿Cuántas veces se ejecutará un bucle “while”?**  
   Se ejecutará mientras la condición sea `true`. Puede ser 0 veces (si la condición es `false` desde el inicio) o indefinidamente si no cambia la condición.  

4. **¿Qué método usarías para agregar un elemento al final de un array y cómo se utiliza?**  
   Se usa `.push()`. Ejemplo:  
   ```js
   let array = [1, 2, 3];  
   array.push(4);  // Ahora el array es [1, 2, 3, 4]
