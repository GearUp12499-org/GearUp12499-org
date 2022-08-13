---
title: "Gear Up - Team"
layout: gridlay
excerpt: "Gear Up: Team members"
sitemap: false
permalink: /team/
---

# Team

## Members
{% assign number_printed = 0 %}
{% for member in site.data.team_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} <!--<br>email: <{{ member.email }}></i> -->

  {% if member.number_educ == 1 %}
  <p> {{ member.education1 }} </p>
  {% endif %}

  {% if member.number_educ == 2 %}
  <p> {{ member.education1 }} </p>
  <p> {{ member.education2 }} </p>
  {% endif %}

  {% if member.number_educ == 3 %}
  <p> {{ member.education1 }} </p>
  <p> {{ member.education2 }} </p>
  <p> {{ member.education3 }} </p>
  {% endif %}
  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

## Coaches
{% assign number_printed = 0 %}
{% for member in site.data.coaches %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} <!-- <br>email: <{{ member.email }}></i> -->

  {% if member.number_educ == 1 %}
  <p> {{ member.education1 }} </p>
  {% endif %}

  {% if member.number_educ == 2 %}
  <p> {{ member.education1 }} </p>
  <p> {{ member.education2 }} </p>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}
