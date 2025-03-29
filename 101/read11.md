
# Read 11: Introducción al DOM y Proyectos

## ¿Qué es el DOM?
El DOM (Document Object Model) es una representación estructurada del documento HTML  que permite   interactuar con él. 

## Relación entre el DOM y JavaScript
JavaScript puede acceder y modificar el DOM para cambiar dinámicamente el contenido, la estructura y el estilo de una página web. Gracias a los métodos proporcionados por el DOM, JavaScript puede actualizar elementos sin necesidad de recargar la página.

## ¿Qué método usarías para seleccionar un elemento del DOM por su ID y cómo se utiliza?
Para seleccionar un elemento del DOM por su ID, se usa el método `document.getElementById("id")`. Ejemplo de uso:

```javascript
let elemento = document.getElementById("miElemento");
console.log(elemento.textContent); 
```

## ¿Qué método utilizarías para cambiar el color de fondo de un elemento en el DOM y cómo se implementaría?
Para cambiar el color de fondo de un elemento, se puede modificar la propiedad `style.backgroundColor` del objeto seleccionado. Ejemplo:

```javascript
let elemento = document.getElementById("miElemento");
elemento.style.backgroundColor = "blue"; 
```
```

