---
layout: splash
permalink: /
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/splash/grand-canyon-pano-hi-res.jpg
  cta_label: "Get Started"
  cta_url: "/about"
  caption:
excerpt: 'Get the most from your National Park visit<br />'
---

<div class="grid__wrapper">
{% for post in site.posts %}
  {% include archive-single.html type="grid" %}
{% endfor %}
</div>
