---
layout: default
---

<div>
{% for post in site.posts %}
  <p>
    {{post.excrept}} <a href="{{post.url}}"> Daha fazla...</a>
  </p>
  <hr>
{% endfor %}
</div>