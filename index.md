---
title: "Welcome Traveller"
---

A minimalistic blog posting area on Programming , Life and anything else that pops up in my head !
<div class="blog-index">  
  {% assign post = site.posts.first %}
  {% assign content = post.content %}
  {% include post_detail.html %}
</div>
