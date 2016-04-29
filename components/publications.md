---
title: Publications
menu: Publications
component: rschoenfelder-publications
order: 2
icon: maps:local-library
---

{% for x in site.publications %}

<div class="academia">
<div class="thumb">
<a href="{{x.link}}" target="_blank"><img src="{{x.thumb}}"></a>
</div>
<div markdown="1" class="reference">

{{x.author}} ({{x.year}}): <br>
<a href="{{x.link}}" target="_blank">{{x.title}}</a>. <br>
{{x.published}}, pp {{x.pages}}.

{{x.content}}{:class="abstract"}
</div>
</div>

{% endfor %}
