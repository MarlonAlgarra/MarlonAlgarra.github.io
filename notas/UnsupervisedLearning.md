---
layout: post
title: Entrenamiento no supervisado
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
En el tipo de entrenamiento no supervisado (unsupervised learning) el tipo de training set es muy distinto. En este, solo se tienen datos sin nungún tipo de etiquetas, clasificación o estructura fácil de ver, así, el algoritmo tendrá entonces que buscar características diferenciadoras en los datos y separarlos en distintos grupos o clusters. Este proceso es también conocido como cluster algorithm o clustering.
</p>

<p style='text-align: justify;'>
En este entrenamiento, también es utilizada la técnica de non-clustering, que está relacionado con el famoso [problema de la fiesta de coctel](https://en.wikipedia.org/wiki/Cocktail_party_effect) que posee las mismas bases que el clustering, pero se diferencia de este porque este método modifica los datos
del training set, y los separa en grupos, mientras que el clustering unicamente los separa, pero no los modifíca.
</p>
[clustering](https://miro.medium.com/max/2636/1*iOPVU49imNwtZGT9dSP3JQ.jpeg)
