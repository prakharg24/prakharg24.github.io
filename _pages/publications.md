---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---

Refer to my [Google Scholar profile](https://scholar.google.co.in/citations?user=Xd5QJoEAAAAJ&hl=en&oi=ao) for the most up to date publication record.

## Publications

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Preprints

{% include base_path %}

{% for post in site.preprints reversed %}
  {% include archive-single.html %}
{% endfor %}
