# HTML

Elemento con contenido:

```html
<tag attribute="value"></tag>
```

Elemento de cierre automático:

```html
<tag attribute="value" />
```

https://developer.mozilla.org/es/docs/HTML/HTML5/HTML5_lista_elementos

- `tag` - El nombre del elemento HTML. Ejemplos:
  - `<div>`
  - `<title>`
  - `<table>`
  - `<body>`
- `attribute` - Los atributos que están suportado por el elemento. Ejemplos:
  - `class`
  - `style`
  - `id`
- `value` - El valor que está asignado para el atributo. Los posibilidades son dependientes en el atributo.

Ejemplos completos:

```html
<div id="algo-unico" class="clase-css-1 clase-css-2">
  Esto es el contenido
</div>

<h1 style="font-size: 2em; margin-top: 1.5em;">Un titulo</h1>
```

# Javascript

JavaScript es case-sensitive (distingue mayúsculas y minúsculas).
En JavaScript, las instrucciones son llamadas Sentencias y son separadas por un punto y coma (;).

## Tipos de datos:

```js
const cuerda1 = "Hola"; // String
const cuerda2 = 'Hola'; // String
const cuerda3 = `Hola`; // String

const booleano1 = true; // Boolean
const booleano2 = false; // Boolean

const nulo = null; // null

const indefinido = undefined; // undefined

const número1 = 1; // Number
const número2 = -2; // Number
const número3 = 3.14159; // Number
```

### Objectos y funciones

Los otros elementos fundamentales en el lenguaje son los Objects y las funciones. Puedes pensar en objetos como contenedores con nombre para los valores, y las funciones como procedimientos que puede realizar tu aplicación.

```js
const objecto1 = { clave: "valor" }; // Object

const objecto2 = {
    claveParaUnValorDeCuerda: "Esto es una cuerda",
    clavaParaUnValorDeNúmero: 42,
}; // Object

const carro = {
    fabricante: 'Toyota',
    año: 2019,
    color: 'roja',
}; // Object
```

```js
const funcion1 = function(argumento1, argumento2) {
    console.log('argumento1 = ' + argumento1);
    console.log(`argumento2 = ${argumento2}`);
    /*
    Puede hacer lo que quiera con los argumentos dentro de la funcion 
    y devolver el resultado.
    */
}; // Function

const add = function(número1, número2) {
    return número1 + número2;
}; // Function
```

### Arrays

Un literal array es un lista de cero o más expresiones, cada uno representa un elemento array, entre corchetes ([]). Cuando crea un array usando un literal array, se inicializa con los valores especificados como sus elementos, y su longitud se establece por el número de argumentos especificados. 

El siguiente ejemplo crea el array cafes con tres elementos y una longitud de tres:

```js
const cafes = ["Tostado Frances", "Colombiano", "Kona"]; // Array
```

Un array puede contener cualquier tipo:

```js
const arrayMixto = [
    "Esto es una cuerda", // String
    42, // Number
    { color: "roja" }, // Object
]; // Array
```