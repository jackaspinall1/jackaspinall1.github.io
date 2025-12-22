---
layout: page
title: "Scientific Work"
permalink: /
---

{% capture source %}{% include_relative publications.md %}{% endcapture %}
{{ source | split: "---" | last }}

