---
layout: default
title: Owen Horwitz
---
Welcome to my website.

{% if site.posts.size > 0 %}
## Blog
{% for post in site.posts %}
1. {{ post.date | date_to_long_string }} - [{{ post.title }}]({{ post.url }})
{% endfor %}
{% endif %}

## Contact
E-mail: [owen@owenhorwitz.com](mailto:owen@owenhorwitz.com)

PGP fingerprint: 1F49 58A5 32C8 FEE0 1295  517C 85B9 565B 6DDB B66A
