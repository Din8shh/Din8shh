---
layout: page
title: blog
permalink: /blog/
---
[Go Back]({{ site.baseurl }}/)
<h5>(Last updated on October 27, 2024)</h5>
{% assign sorted_entries = site.data.blogs_data | reverse %}
{% for entry in sorted_entries %}
  {{ entry.date }} [{{ entry.title }}]({{ entry.link }})  
{% endfor %}