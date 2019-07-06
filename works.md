---
layout: default
title: "Artworks"
---
<img src="/pulitzer.jpg" width="250" height="150"/>

## {{ page.title }} ##

Image goes here:

<img src="/img/thomas.jpg" width="100" height="150"/>
<text>img src="/img/thomas.jpg"</text>
<br><br>
<img src="{{ site.baseurl }}/img/thomas.jpg" width="100" height="150"/>
{% raw %}
<text>img src="{{ site.baseurl }}/img/thomas.jpg"</text>
{% endraw %}
