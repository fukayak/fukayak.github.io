---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<div class="home">

<div class="site-header-container {% if site.cover %}has-cover{% endif %}" {% if site.cover %}style="background-image: url({{ site.cover | prepend: site.baseurl }});"{% endif %}>
  <div class="scrim {% if site.cover %}has-cover{% endif %}">
    <header class="site-header">
      <h1 class="title">{{ site.title }}</h1>
      {% if site.subtitle %}<p class="subtitle">{{ site.subtitle }}</p>{% endif %}
    </header><br><br>
    <body link="#ffffff" vlink="#ffffff" alink="#ffffff">
    <h1 style="text-align:center"><a href="https://fukayak.github.io/en/">English</a> / <a href="https://fukayak.github.io/jp/">日本語</a></h1>
    </body>
  </div>
</div>

</div>

