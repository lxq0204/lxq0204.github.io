---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if [site.author.googlescholar](https://scholar.google.com/citations?hl=zh-CN&view_op=list_works&gmla=AKKJWFdhMpSqgrWVjiVRRe7tQckxqWFiIfHxommuMQwI6zunIJ2aGSCCdiCy3XsOOOwFXGAMxrqfQ4ZfWONYTrCQNmw&user=a3VWnxoAAAAJ) %}
  <div class="wordwrap">You can also find my articles on <a href="{{[site.author.googlescholar](https://scholar.google.com/citations?hl=zh-CN&view_op=list_works&gmla=AKKJWFdhMpSqgrWVjiVRRe7tQckxqWFiIfHxommuMQwI6zunIJ2aGSCCdiCy3XsOOOwFXGAMxrqfQ4ZfWONYTrCQNmw&user=a3VWnxoAAAAJ)}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
