---
title: Kumpulan Teori
description: Halaman ini merupakan kumpulan pembahasan/artikel definisi, istilah, atau teori-teori tertentu. Tambahkan referensi yang belum ada menurut anda.
permalink: /teori
redirect_from: /docs/teori/
---

Halaman ini merupakan kumpulan pembahasan/artikel yang dimuat dalam blog ini dengan kategori Teori.
<ol class="arti">{% for post in site.categories.teori %}
<li class="{% if page.title == post.title %}current{% endif %}">
<a href="{{ post.url }}">{{ post.title }}</a>
</li>
{% endfor %}
</ol>
