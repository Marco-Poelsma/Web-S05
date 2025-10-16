# Web. Sesión 5.

Para ir al ejercicio, haz clic [aquí](https://github.com/Marco-Poelsma/Web_S05-Ex)

---

## CSS: propiedades

### `text-decoration`

Sirve, entre otras cosas, para subrallar texto.

### `box-sizing`

Es para definir si el programa debe contar el border o el contenido (padding) como guía para ajustar el tamaño de los elementos. Es recomendable usar `box-sizing: border-box`

### `text-align`

Permite alinear el texto según queramos

### `display`

Permite canviar como se muestran elementos.

`display:none` sirve para hacer que desaparezca de la página.

`display: inline-block` sirve para convertir un elemento inline en un elemento en bloque. De esta manera, podemos añadir propiedades de bloque a un elemento inline y que, aún así, siga siendo en línea.

### `calc()`

Sirve para hacer cálculos en CSS. 

Si queremos que un elemento tenga un ancho del 100% menos 50 píxeles, podemos usar `width: calc(100% - 50px);`

### `margin: 0 auto`

Sirve para centrar un elemento horizontalmente.

### `display: flex`

Sirve para hacer que los elementos hijos de un contenedor se distribuyan de manera flexible. Permite alinear y distribuir espacio entre los elementos de una manera más eficiente.

### `flex-direction`

Permite definir la dirección en la que se distribuyen los elementos hijos dentro de un contenedor flex. Puede ser `row` (fila), `column` (columna), `row-reverse` (fila inversa) o `column-reverse` (columna inversa).

### `order`

Permite cambiar el orden en el que se muestran los elementos hijos dentro de un contenedor flex. Por defecto, todos los elementos tienen un `order` de 0. Si queremos que un elemento aparezca primero, podemos darle un `order` negativo.

