---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

<div>
  <h2>It’s no use going back to yesterday because I was a different person then.</h2>
  <p><i> —— Alice, Alice's Adventures in Wonderland </i></p>
</div>
<hr>
<article>
  {% for post in site.posts %}
    <h2>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    </h2>
    <p>{{ post.excerpt }}</p>
    <hr>
  {% endfor %}
</article>
