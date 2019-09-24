---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
---

{% include home-hero.html %}



<div class="recent-work">
<h2>Recent Work</h2>
{% for item in site.portfolio %}
  <h2>{{ item.title }}</h2>
  <p><a href="{{ item.url }}">{{ item.title }}</a></p>
{% endfor %}
</div>