---
title: myterms.fyi
layout: default
permalink: index.html
---

{% capture include_readme %}
{% include_relative README.md %}
{% endcapture %}

{{ include_readme | remove_first: "# myterms.fyi" }}