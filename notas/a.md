---
layout: post
title: ¿Qué es Machine Learning?
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


No hay una definición acordada por los profesionales en el campo, por lo tanto existen unas descripciones que se acercan bastante bien a lo que es el Machine learning (ML). Una de ellas, dada por Arthut Samuel es: "El campo de estudio que le brinda a las computadoras la habilidad de aprender sin ser explícitamente programada". Est descripción, a grosso modo, es bastante acertada, pero antigua. Una definición más reciente es dada por Tom Mitchell: "Un programa de computador se dice que aprende de una experiencia $E$ con respecto a alguna clase de tarea $T$ con un rendimiento medido $P$ ."Podemos ver que esta definición es más formal que la anterior, pues contiene en ella las principales caracteristicas de estudio del ML, que son experiencia, tarea y rendimiento. 

Conforme el estudio vaya avanzando, observaremos detalladamente cada una de las características mencionadas, pues en este campo de estudio se ha logrado desarrollar la teoría en las diferentes características, para atacar diferentes tipos de problemas que han surgido. Primero, estudiaremos la característica  de experiencia, pues nos puede ayudar a crear un panorama más claro de cómo funciona realmente el ML.
