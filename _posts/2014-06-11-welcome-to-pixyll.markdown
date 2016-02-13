---
layout:     post
title:      Reveal.js
date:       2014-06-11 15:31:19
summary:    Reveal.js is a javascript library which allows us to create beautiful minimalist presentations 
categories: javascript 
---

Reveal.js is a javascript framework to create beautiful presentations. 
![Cover](https://cloud.githubusercontent.com/assets/1424573/3378137/abac6d7c-fbe6-11e3-8e09-55745b6a8176.png)
It allows us us to create presentations in form of html pages which include a broad range of features. I like the the framework mostly because it allows to create presentation related to web development and also show the excecution of code then and there. Though some of you may feel that it is tedious to create presentation using 
reveal.js for such people there is a [online editor](http://slides.com/) which allows you to use reveal.js without the need to code anything.
you can see the demo slide [here](http://lab.hakim.se/reveal-js/#/).
{% highlight html %}
<html>
    <head>
        <link rel="stylesheet" href="css/reveal.css">
        <link rel="stylesheet" href="css/theme/white.css">
    </head>
    <body>
        <div class="reveal">
            <div class="slides">
                <section>Slide 1</section>
                <section>Slide 2</section>
            </div>
        </div>
        <script src="js/reveal.js"></script>
        <script>
            Reveal.initialize();
        </script>
    </body>
</html>
{% endhighlight %}

