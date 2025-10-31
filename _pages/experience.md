---
title: "Experience"
layout: homelay
sitemap: false
permalink: /experience/
---

### Research

<div class="jumbotron">

</div>


### Professional

<div class="jumbotron">
{% for job in site.data.jobs %}
<b>{{job.title}}, {{ job.jobstart }} - {{ job.jobend }}</b>

{{ job.company }}
{% endfor %}

</div>

### Volunteering

<div class="jumbotron">

</div>
