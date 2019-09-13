---
title: Daftar Isi
description: Halaman ini berisi kumpulan arsip / daftar isi dari ArtiPedia. Anda juga bisa berkontribusi dengan menulis artikel di ArtiPedia.
permalink: /daftar-isi
redirect_from: /docs/daftar-isi/
---

<div id="search-container" style="margin-top:20px">
        <form id="search-input" role="search" method="get" action="{{ site.baseurl }}/search/">
        <input type="text" id="search-input" name="cari" placeholder="search..."/>
        <button type="submit" title="Submit your search query." class="searchbox__submit">
        <i class="fa fa-search" aria-hidden="true"></i>
</button></form>
              </div>

<h4><a href="https://artipedia.id/artikel" title="Kumpulan Artikel">Artikel</a></h4>
<ol class="arti">
{% for post in site.categories.artikel %}
<li class="{% if page.title == post.title %}current{% endif %}">
<a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a>
</li>  {% endfor %}
</ol>
<h4><a href="https://artipedia.id/berita" title="Kumpulan Berita">Berita</a></h4>
<ol class="arti">
{% for post in site.categories.berita %}
<li class="{% if page.title == post.title %}current{% endif %}">
<a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a>
</li>  {% endfor %}
</ol>
<h4><a href="https://artipedia.id/buku" title="Kumpulan Buku">Buku</a></h4>
<ol class="arti">
{% for post in site.categories.buku %}
<li class="{% if page.title == post.title %}current{% endif %}">
<a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a>
</li>
{% endfor %}
</ol>
 <h4><a href="https://artipedia.id/rpp" title="Kumpulan RPP">RPP</a></h4>
<ol class="arti">
{% for post in site.categories.rpp %}
<li class="{% if page.title == post.title %}current{% endif %}">
<a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a>
</li>  {% endfor %}
</ol>
  <h4><a href="https://artipedia.id/docs/materi" title="Kumpulan Materi">Materi</a></h4>
<ol class="arti">
{% for post in site.categories.materi %}
<li class="{% if page.title == post.title %}current{% endif %}">
<a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a>
</li>  {% endfor %}
</ol>
  <h4><a href="https://artipedia.id/soal" title="Kumpulan Soal">soal</a></h4>
<ol class="arti">
{% for post in site.categories.soal %}
<li class="{% if page.title == post.title %}current{% endif %}">
<a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a>
</li>  {% endfor %}
</ol>
  <h4><a href="https://artipedia.id/teori" title="Kumpulan Teori">Teori</a></h4>
<ol class="arti">
{% for post in site.categories.teori %}
<li class="{% if page.title == post.title %}current{% endif %}">
<a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a>
</li>  {% endfor %}
</ol>

