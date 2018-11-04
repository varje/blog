---
layout: post
title:  "Django Tutorials"
date:   2017-12-20 21:49:14 +0200
categories: django
comments: true
---

Django is a web-framework for Python. It gives a certain layout to your project and let's you to write Python in web-development enviroment. It might be a bit oberwhelming for small projects as all MVC (model-view-controller) frameworks, but for bigger project it gives a certain structure and is really worth learning.

Here I list some tutorials, which have been useful for me to getting started with Django:

1) [Official Getting Started Tutorial](https://docs.djangoproject.com/en/1.11/intro/tutorial01/)

This you can use each time you want to start a new project. It has a tutorial for every Django version, so be sure to select the version you are using.


2) [Django Girls Tutorial](https://www.gitbook.com/book/djangogirls/djangogirls-tutorial/details)

Tutorial about creating blog in Django. Useful for getting familiar with forms and models (Django version 1.10, but works fine for 1.11 as well).


3) [Blog "Simple is better than complex"](https://simpleisbetterthancomplex.com/tutorial/2016/08/01/how-to-upload-files-with-django.html)

This blog is all about Python, Django and Web development, so many useful posts. I particularly liked posts about testing, file upload and user registration.


{% if page.comments %}
 <div id="disqus_thread"></div>
<script>
// var disqus_config = function () {
// this.page.url = "{{ page.url }}"
// };
 (function() { // DON'T EDIT BELOW THIS LINE
 var d = document, s = d.createElement('script');
 s.src = 'https://varjekass-com-blog.disqus.com/embed.js';
 s.setAttribute('data-timestamp', +new Date());
 (d.head || d.body).appendChild(s);
 })();
 </script>
 <noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
{% endif %}
