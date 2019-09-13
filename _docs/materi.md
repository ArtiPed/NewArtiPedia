---
title: Materi Pembelajaran
description: Download kumpulan materi pembelajaran sebagai referensi dalam pelaksanaan pembelajaran di kelas. 
permalink: /materi
redirect_from: /docs/materi/
---

Berikut ini adalah kumpulan halaman dengan kategori materi
<ol class="arti">{% for post in site.categories.materi %}
<li class="{% if page.title == post.title %}current{% endif %}">
<a href="{{ post.url }}">{{ post.title }}</a>
</li>
{% endfor %}
</ol>
