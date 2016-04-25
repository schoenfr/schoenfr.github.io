---
title: Publications
menu: 2
icon: maps:local-library
imports:
 - paper-input
---

{% for x in site.publications %}

<div class="academia">
<div class="thumb">
<img src="{{x.thumb}}">
</div>
<div markdown="1" class="reference">

{{x.author}} ({{x.year}}): <br>
<a href="{{x.link}}" target="_blank">{{x.title}}</a>. <br>
{{x.published}}, pp {{x.pages}}.

{{x.content}}{:class="abstract"}
</div>
</div>

{% endfor %}
