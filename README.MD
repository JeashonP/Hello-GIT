# Version del curso 
Version actual: 1.2.2

# Cabeceras 

# cabecera h1
## Cabecera h2
### cabecera h3
#### cabecera h4
##### cabecera h5
###### cabecera h6

# Underline 
Underline 1
----------
Underline 2
===========

# Formatos de enfasis
- Formato *italica* 1 forma.
- Formato _italica_ 2 forma.

- Formato **bold o strong** 1 forma.  
- Formato __bold o strong__ 2 forma. 

- Formato ~~tachado~~, Formato normal.

--Aqui podemos usar formato *italico*, pero tambien **bold** y ~~tachado~~.

# Listas 
2. Esto es un item de lita ordenada.
1. Esto es un item de lita ordenada.
3. Esto es un item de lita ordenada.

- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.

# Links

- <a href="http://www.google.com">Esto es un link html</a>
- [Esto es un link en markdown](http://www.google.com)
- [Esto es un link a index](index.html)

# Imagenes
![Logo de GitHub](https://th.bing.com/th/id/OIP.ckeUFk-yid0vfWnd56w7wAHaHa?w=175&h=180&c=7&o=5&pid=1.7)

# Code Snippets
Codigo en Json
```` JSON
[
    {
        "title": "apples",
        "count": [12000, 28000],
        "description": {"text": "...", "sensitive": false}
    },
    {
        "title": "oranges",
        "count": [17500, null],
        "description": {"text": "...", "sensitive": false}
    }
] 
````

Codigo en JavaScript
````JAVASCRIPT
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
````

# Tablas 
| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Maxi | Burgos | 1052395927 |
| Tomas | Tomson | 1548799 |

# Citas 
Esto es un texto refeente a unsa cita que pondremos debajo
> Esto es una cita. 

Es to es otro texto que no se relaciona con la cita anterior 
> Esto es otra cita.

# Lineas Divisoras
Esto es un exto que sera dividido por guiones medios. 

--- 
Esto es otro texto dividido por asteriscos.

***
Esto es otro texto dividido por guiones bajos.

___

# Saltos de linea
Esto es nuestro primer parrafo.

Esto es nuestro segundo parrafo.

Esto es nuestro tercer parrafo.
- Lista

 
