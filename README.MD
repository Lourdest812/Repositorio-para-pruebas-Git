# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6


# Underlines

Underline 1
-----------

Underline 2
===========


# Formatos de énfasis

- formato itálica *primer* forma.
- formato itálica _segunda_ forma.
- formato **bold o strong** primer forma.
- formato __bold o strong__ segunda forma.
- formato ~~tachado~~, formato normal.

- acá podemos usar formato _itálico_, pero también **bold** o ~~tachado~~.


# Listas

1. Esto es un item de lista ordenada.
1. Esto es un item de lista ordenada.
1. Esto es un item de lista ordenada.

- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.


# Links

- <a href="http://google.com">Esto es un link HTML</a>
- [Esto es un link en Markdown](http://www.google.com)
- [Esto es un link en Markdown](index.html)


# Imágenes

![Logo GitHub](https://imgs.search.brave.com/ZhnjgP77uCVODTUNfQsQZAKkIlit2uyYFB_luKGVCJw/rs:fit:512:512:1/g:ce/aHR0cHM6Ly93d3cu/aWNvbnNkYi5jb20v/aWNvbnMvZG93bmxv/YWQvcGluay9naXRo/dWItOS01MTIucG5n)


# Code Snipets

###  Código en JSON

```JSON

[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```


###  Código en JavaScript

```Javascript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}
export  $initHighlight;
```

# Tablas
| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
|  Maxi  |  Burgos  |  4345536  |
| Tomás  | Thompson |  3423453  |