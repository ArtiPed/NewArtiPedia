---
title: Soal
description: Download kumpulan soal pembelajaran sebagai referensi dalam pelaksanaan penilaian di kelas. 
permalink: /soal
redirect_from: /docs/soal
---

Berikut ini adalah kumpulan halaman dengan kategori soal
<ol class="arti">{% for post in site.categories.soal %}
<li class="{% if page.title == post.title %}current{% endif %}">
<a href="{{ post.url }}">{{ post.title }}</a>
</li>
{% endfor %}
</ol>
