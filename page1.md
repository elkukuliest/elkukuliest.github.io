---
layout: page
permalink: /page1/
foobarr: dubi
---

<img src="{{ site.baseurl }}/img/page1.jpg"/>

## Lalala

<p class="nav">
<a href="/">&lArr;</a>
<a href="{{ site.baseurl }}/page2">&rArr;</a>
</p>

{{ page.foobarr }}

{% include nav.html %}
