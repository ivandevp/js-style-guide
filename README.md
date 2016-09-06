# Guía de Estilo - JavaScript

Esta guía da a conocer los estándares y alineamientos para llevar un código ordenado y legible al momento de desarrollar proyectos que involucren JavaScript.

## Contenido

  1. [Nomenclatura](#nomenclatura)
  2. [Indentación](#indentación)
  3. [Puntuación](#puntuación)
  
## Nomenclatura

En esta guía usaremos la convención **[camelCase](https://en.wikipedia.org/wiki/CamelCase)** para nombrar las variables y funciones.

```javascript
// Declaración de variables usando camelCase
var miVariable = "";
  
// Declaración de funciones usando camelCase
function miFuncion() {
    // código
}
```

## Indentación

Usaremos indentación de *4 espacios* o *tabs* para todos los statements que se encuentren dentro de un bloque (condicionales, bucles, funciones).

```javascript
// Esta variable no lleva indentación debido a que es una variable global y no está dentro de un bloque.
var miVariable = "";

// Los statements van indentados por 4 espacios o un tab debido a que se encuentra dentro de un bloque {}

// Statements dentro de un condicional
if (condicion) {
    statement; 
}

// Statements dentro de un bucle
for (var i = 0; i < array.length; i++) {
    statement;
}

while (true) {
    statement;
}

do {
    statement;
} while (true);

// Statements dentro de una función
function miFuncion() {
    statement;
}
```

## Puntuación

Si bien JavaScript hace omiso a los **;** en algunos casos, usaremos **;** al final de cada statement.

```javascript
var miVariable = "";

miVariable = "Punto y coma siempre!";

for (var i = 0; i < 10; i++) {
    console.log("Punto y coma al final de cada statement!");
}
```
