---
layout: post
title: Welcome to Jekyll!
date: '2020-05-13 11:30:00 +0800'
author: socket778
categories: Jekyll
tags: jekyll welcome
cover: assets/nsfsvg.jpg
published: true
---

### Code Snippets
One of the really cool things about Jekyll is how easy it is to include code snippets.  From Ben Centra:
You can use [highlight.js][highlight] to add syntax highlig code snippets:

<pre><code class="hljs javascript">function demo(string, times) {
  for (var i = 0; i < times; i++) {
    console.log(string);
  }
}
demo("hello, world!", 10);</code></pre>

### Images are also easy in Jekyll, thanks to [Lightbox][lightbox].


<a href="{{ site.baseurl }}assets/logo2.jpg" data-lightbox="falcon9-large" data-title="Logo">
  <img src="{{ site.baseurl }}assets/logo2.jpg" title="Logo">
</a>



Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll’s dedicated Help repository][jekyll-help].


### Latex inserts

We will not be able to completely recreate the beauty of Latex (hell, can anything really?), but we can do pretty well using MathJax.  See the following expression:

$$ \pi(\theta|\mathbf{x})\propto \pi(\theta)f(\mathbf{x}|\theta) $$ 
(Bayes, for those who don't know)

[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help
[highlight]:   https://highlightjs.org/
[lightbox]:    http://lokeshdhakar.com/projects/lightbox2/
[jekyll-archive]: https://github.com/jekyll/jekyll-archives
