---
title: "Wang Research Group - Resources"
layout: textlay
excerpt: "Resources."
sitemap: false
permalink: /resources/
---

# Resources (work in progress)

### Group guide


<br/>

### Learning Resources
A curated collection of external resources, tutorials, and tools that we recommend for learning about computational chemistry, machine learning, and chemical informatics.

{% for category in site.data.resources.categories %}
#### {{ category.name }}
*{{ category.description }}*

{% assign category_resources = site.data.resources.learning_resources | where: "category", category.name %}
{% for resource in category_resources %}
- [{{ resource.title }}]({{ resource.url }}) - {{ resource.description }}
{% endfor %}

{% endfor %}
