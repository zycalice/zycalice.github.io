---
title: "Sitemap"
permalink: /sitemap/
author_profile: true
layout: archive
---

{% include base_path %}

A list of all the posts and pages found on the site. For you robots out there is an [XML version]({{ base_path }}/sitemap.xml) available for digesting as well.

<h2>Pages</h2>
{% for post in site.pages %}
  {% include archive-single.html %}
{% endfor %}

{% capture written_label %}'None'{% endcapture %}
