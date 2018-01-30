---
layout: post
title:  "Welcome to my blog!"
date:   2017-12-05 19:49:14 +0200
categories: welcome
comments: true
---
Welcome!

I'll write about programming and IT. Some posts will be more like tutorials and others my personal opinion.
I'm studying IT and working in the area as well. I feel most comfortable with Python and Django, but I have experience with JavaScript, Java and PHP as well.

My first code-snippet.
{% highlight ruby %}
def print_hi(name):
  return ("Hi, ", name)

print_hi('Visitor')
# prints 'Hi, Visitor' to console.
{% endhighlight %}

{% if page.comments %}
 <div id="disqus_thread"></div>
 <script>

 /**
 *  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
 *  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables*/
 /*
 var disqus_config = function () {
 this.page.url = PAGE_URL;  // Replace PAGE_URL with your page's canonical URL variable
 this.page.identifier = PAGE_IDENTIFIER; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
 };
 */
 (function() { // DON'T EDIT BELOW THIS LINE
 var d = document, s = d.createElement('script');
 s.src = 'https://varjekass-com-blog.disqus.com/embed.js';
 s.setAttribute('data-timestamp', +new Date());
 (d.head || d.body).appendChild(s);
 })();
 </script>
 <noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
{% endif %}