---
layout: post
title: Escribe en markdown
subtitle: Una introducción de sintaxis
tags: [Introducción]
comments: true
---

Markdown, a grandes rasgos, es una herramienta de conversión de texto plano a HTML. Es muy común encontrar hoy en día esta herramienta en varios escenarios como en los últimos diseños web (como beautiful-jekyll) o en implementaciones de "live-code" de lenguajes de programación, que permiten realizar un código mucho más presentable, pues permite insertar texto y/o fórmulas, además de el código, que es ejecutable. 

Veamos algunas sintaxis básicas del programa.

Para escribir en negrilla, basta con poner dos asteriscos al inicio y dos asteriscos al final de lo que se desea poner en negrilla **Como esta oración.**

Para poner titulos o subtitulos, se utiliza el numeral (#) Entre más numerales seguidos se usen, más pequeño será el título, en este caso, se utilizarán dos: 

## Esto es un subtítulo.

La creación de tablas es un poco más intuitiva, para realizar espacios horizontalmente, basta con separar las casillas que quiero con el simbolo "|" y para realizar la separación vertical, basta con dar enter y pasar a la siguiente linea, veamos un ejemplo:


| Nombre | Edad | Altura |
| :------ |:--- | :--- |
| Pedro | 18 | 1.83 |
| Gabriel | 22 | 1.73 |
| Camila | 15 | 1.65 |
| Ana | 20 | 1.75 |


También se pueden insertar imágenes, solo necesitamos un link. La estructura es la siguiente: 

~~~
![nombre de la imagen](link)
~~~

![F1Vettel](https://e0.365dm.com/19/07/768x432/skysports-charles-leclerc-f1_4729577.jpg?20190727114805)

También puede ser centrada, basta agregar el código > {: .center-block :}

![F1Vettel](https://e0.365dm.com/19/07/768x432/skysports-charles-leclerc-f1_4729577.jpg?20190727114805){: .center-block :}

Ahora, para mostrar códigos se debe agregar > ~~~ < al inicio y al final del código

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

Ahora, para que se meustre con sintaxis, se debe poner ` ```javascript ` al comienzo. 

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

Ahora, para que muestre el número de lineas en el código, se utiliza en vez de `~~~ ` al inicio y al final, se usa ` {% highlight javascript linenos %}` al comienzo, y ` {% endhighlight %}` al final.

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Cápsulas
Se pueden añadir cápsulas de notificación, de advertencia y de error también.

### Notification

Se utiliza el comando ` {: .box-note}` y en la linea de abajo, el mensaje que se quiere indicar.

{: .box-note}
**Nota:** Esta es una cápsula de notificación.

### Warning

Se utiliza el comando ` {: .box-warning}` y en la linea de abajo, el mensaje que se quiere indicar.

{: .box-warning}
**Advertencia:** Esta es una cápsula de emergencia.

### Error

Se utiliza el comando ` {: .box-error}` y en la linea de abajo, el mensaje que se quiere indicar.

{: .box-error}
**Error:** Esta es una cápsula de error.
