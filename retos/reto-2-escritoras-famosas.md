# Reto 2: Escritoras famosas

¿Sabías que también se puede crear un array de objetos? Hemos creado uno para tí a continuación. Itera por el array asignado a la varibale 'escritoras' y para cada objeto, escribe en la consola \(`console.log()`\) la siguiente frase:

```javascript
'Hola, mi nombre es {nombre} {apellido}. Tengo {edad} años y trabajo como {profesion}.';
```

Ignora las llaves. Solo sirven para marcar las palabras que hay que reemplazar con otros valores. La frase que logueas en la consola debe ser como ésta:

```javascript
'Hola, mi nombre es Virginia Woolf. Tengo 59 años, y trabajo como escritora.';
```

Aquí tienes el array de objetos:

```javascript
var escritoras = [
  {
    nombre: 'Virginia',
    apellido: 'Woolf',
    profesion: 'escritora',
    edad: 59,
    viva: false
  },
  {
    nombre: 'Zadie',
    apellido: 'Smith',
    profesion: 'escritora',
    edad: 41,
    viva: true
  },
  {
    nombre: 'Jane',
    apellido: 'Austen',
    profesion: 'escritora',
    edad: 41,
    viva: false
  },
  {
    nombre: 'Bell',
    apellido: 'Hooks',
    profesion: 'escritora',
    edad: 64,
    viva: true
  }
];
```

Si quieres probar con otro reto, trata de hacer el `console.log()` de las escritoras que siguen vivas \(viva: true\).

### [Ir al reto 3 >>>>](https://github.com/Fa-v/beginners-javascript-spanish/blob/master/retos/reto-3-arregla-el-codigo.md)
