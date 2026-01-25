---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Home to your favorite home for US-based GodotCon events.
---

{% assign image_files = site.static_files | where: "image", true %}
{% for myimage in image_files %}
  <p style="padding: 5em 0em;"><img src="{{ myimage.path }}" /></p>
{% endfor %}