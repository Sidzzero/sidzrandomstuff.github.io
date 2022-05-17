---
title: "Welcome Traveller"
---

A minimalistic blog posting area on Programming , Life and anything else that pops up in my head !
<header>
<h1>{% for post in site.posts %}   
<h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
<p><small><strong>{{ post.date | date: "%B %e, %Y" }}</strong> . {{ post.category }} . <a href="http://myname.github.com{{ post.url }}#disqus_thread"></a></small></p>            
{% endfor %}</h1>
</header>
