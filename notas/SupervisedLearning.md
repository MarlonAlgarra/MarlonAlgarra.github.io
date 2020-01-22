---
layout: post
title: Entrenamiento supervisado
tags: [Machine Learning]
---
<style TYPE="text/css">
code.has-jax {font: inherit; font-size: 100%; background: inherit; border: inherit;}
</style>
<script type="text/x-mathjax-config">
MathJax.Hub.Config({
    tex2jax: {
        inlineMath: [['$','$'], ['\\(','\\)']],
        skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'] // removed 'code' entry
    }
});
MathJax.Hub.Queue(function() {
    var all = MathJax.Hub.getAllJax(), i;
    for(i = 0; i < all.length; i += 1) {
        all[i].SourceElement().parentNode.className += ' has-jax';
    }
});
</script>
<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/MathJax.js?config=TeX-AMS_HTML-full"></script>

<p style='text-align: justify;'>
En general, cada problema de Machine Learning se le pueden asignar dos clasificaciones: Entrenamiento supervisado y no supervisado. Esto se refiere a la manera
en la cual se va a entrenar el algoritmo dado el tipo de experiencia $E$ pertinente, para llevar a cabo la solución del problema dado.
Veamos pues a que se refiere el entrenamiento supervisado:
</p>

<p style='text-align: justify;'>
En este tipo de entrenamiento (supervised learning), el conjunto $E$, también denominado conjunto de entrenamiento o (training set) consiste en un conjunto de elementos
etiquetados. Esto es, un conjunto con ejemplos de entrenamiento, lo cual se puede pensar como pares, donde una entrada o input, tiene su correspondiente salida, u output.
Entonces, el algoritmo de ML, se asimilará a una función, donde los elementos del dominio serían el subconjunto de inputs, y los elementos del codominio serían el subconjunto
de outputs. Así, construida una función que se acomode a estos parametros, al ingresar un nuevo input al algoritmo, este encontraría un output pertinente con base al entrenamiento
dado por las características del training set.
</p>

<p style='text-align: justify;'>
Los problemas de entrenamiento supervisado también se dividen en dos tipos de tareas: clasificación y regresión. La tarea de clasificación se refiere a que en el training set
los outputs serán un subconjuntos de clases finitas, entonces para cada input, el algoritmo lo asociará a una de estas clases, por ejemplo, dada una imagen decir qué objeto aparece
o dada una imagen de un tumor, decir si es maligno o no.
</p>

<p style='text-align: justify;'>
Por otro lado, la tarea de regresión indica que el conjunto de outputs, es un conjunto continuo(se puede decir directamente que el conjunto de numeros reales). Así pues, podemos ver
que esta tarea esta asociada al conteo. Por ejemplo, dada la foto de una persona, decir cuantos años tiene, o a partir  de una imagen de una muestra biológica, contar el número de bacterias
que aparecen en ella.
</p>
