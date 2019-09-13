---
title: Kumpulan Berita Seputar Pendidikan
description: Halaman ini berisi kumpulan artikel, ataupun lainnya yang sangat berguna bagi para pembaca.
permalink: /artikel
redirect_from: /docs/artikel/
---

Halaman ini berisi kumpulan artikel lainnya yang sangat berguna bagi para pembaca.
<ol class="arti">{% for post in site.categories.artikel %}
<li class="{% if page.title == post.title %}current{% endif %}">
<a href="{{ post.url }}">{{ post.title }}</a>
</li>
{% endfor %}
</ol>
