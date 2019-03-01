# Sección 5: Sentencias de control "if/else"

Ahora vamos a ir agregando algo de lógica a nuestro código. Hasta ahora, hemos estado imprimiendo en la consola lo mismo cada vez que ejecutamos el código. ¿Y si queremos escribir cosas diferentes dependiendo de algunas condiciones? En programación tenemos algo que se conoce como sentencias de control "if/else". Este tipo de sentencia de control comprueba condiciones y ejecuta distintas acciones dependiendo del resultado de las condiciones que recibidas.

En JavaScript, la estructura de una sentencia de control "if/else" es así:

```javascript
if (condición) {
  // haz algo
} else {
  // haz otra cosa
}
```

Esto básicamente se traduce en "si esta condición es verdadera, haz esto, sino haz otra cosa".

#### Pruébalo

¿Cómo hacemos un `console.log()` de "Hola mundo!" si estamos contentas y otra cosa si estamos tristes?

Vamos a definir una variable `happy` y asignarla un valor de tipo "boolean" de `true` o `false` \(dependiendo de si estás contenta o triste\).

```javascript
var happy = true;
```

Ahora vamos a escribir nuestra sentencia de control "if/else". En nuestra condición queremos comprobar si la variable `happy` es igual a `true`. Nota que en JavaScript hay que usar un 'triple equals' \(`===`\) para comprobar si dos cosas son iguales en vez de solo uno \(`=`\). Si tienes curiosidad, puedes leer más sobre eso [aquí](http://www.w3schools.com/js/js_operators.asp).

```javascript
if (happy === true) {
  // haz algo
} else {
  // haz otra cosa
}
```

Ahora, vamos a añadir qué acciones queremos ejecutar cuando las condiciones se cumplen. Los comentarios sirven para explicar qué está pasando; es una especie de pseudo código.

```javascript
if (happy === true) {
  // Si estoy contenta, imprime "Hola mundo!"
  console.log('Hello world!');
} else {
  // Si estoy triste, imprime una cara triste
  console.log(':(');
}
```

¡Vamos a ejecutar este código y ver qué pasa! \(Recuerda que las variables tienen que estar declaradas al princípio del Repl\). Intenta cambiar el valor de la variable de `true` a `false`.

#### Mini reto

---

Escribe una sentencia de control "if/else" que evalúa si un número es par o impar. Si es un número par, debe imprimir la cadena `'par'`, y si es impar, la cadena `'impar'`.

Para este reto, el uso del operador "módulo" - que se escribe así `%` - te puede ser útil. El operador modulo devuelve el resto después de dividir dos números. Por ejemplo:

```javascript
13 % 2 === 1; // 13 dividido por 2 nos da un resto de  1
100 % 10 === 0; // 100 dividido por 10 nos da un resto de 0
```

Un número par tendrá un resto de 0 al ser divido por 2. Puedes leer más sobre el operador módulo [aquí](http://www.w3schools.com/js/js_operators.asp).

### [Ir a la Sección 6 >>>>](https://github.com/Fa-v/beginners-javascript-spanish/blob/master/taller/seccion-6-los-bucles-for.md)
