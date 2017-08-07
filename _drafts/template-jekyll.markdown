---
layout: post
title:  "Template Jekyll"
date:   2017-01-28 22:20:00 +0100
categories: programmazione
---
Come è stato realizzato questo template.

A partire da http://veithen.github.io/2015/03/26/jekyll-bootstrap.html

Scaricato Bootstrap Sass ed estratti i file scss principali

Copiati i file di default dal template minima (individuato tramite il comando ``bundle show minima``).

Riferimento a site.css in head.html

Allineato default.html

Aggiunta la navbar in header.html

Riorganizzata la home

Creato il footer

Immagine
{% highlight scss %}

@mixin background-size($size) {
    -webkit-background-size: $size;
    -moz-background-size: $size;
    -o-background-size: $size;
    background-size: $size;
}

html { 
    background: url(images/skyscrapers.jpg) no-repeat center center fixed; 
    @include background-size(cover);
}
{% endhighlight %}
