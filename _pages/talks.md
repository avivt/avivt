---
title: "Selected Talks"
layout: gridlay
excerpt: "Selected Talks"
sitemap: false
permalink: /talks/
---

# Selected Talks


## Selected Talks
{% assign number_printed = 0 %}
{% for talk in site.data.talks %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-12 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/talks/{{ talk.photo }}" class="img-responsive" width="35%" style="float: left" />
  <h4>{{ talk.title }}</h4>
  <i>{{ talk.title }}<br>link: <{{ talk.link }}><br>abstract: <{{ talk.abstract }}><br>venue: <{{ talk.info }}></i>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}






