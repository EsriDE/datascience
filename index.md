---
layout: default
---

# Unlock the Power of Location <br>to Solve Complex Problems

## Why Spatial Data Science?

Spatial data science is revolutionizing the way we understand and interact with the world. By leveraging the power of location, we can uncover patterns, make informed decisions, and tackle complex challenges across various domains.

## Who Benefits from Spatial Data Science?

### Scripters
Dive into the world of spatial data science and get hands-on experience with real-world data. Learn how to manipulate and analyze spatial data to uncover hidden insights.

### Data Scientists
Enhance your expertise with spatial skills. Integrate geographic data into your analyses to provide deeper context and more accurate predictions.

### Data Engineers
Extract valuable knowledge from spatial data. Optimize data pipelines and ensure the efficient processing and storage of geographic information.

### Developers
Innovate and grow with spatial data science. Build powerful applications that leverage location-based insights to deliver unique solutions and drive growth.

## ArcGIS Living Atlas
Explore the ArcGIS Living Atlas of the World, the premier collection of geographic information from around the globe. Access a vast array of maps, apps, and data layers to support your spatial data science projects and drive impactful results.

{% if site.data.repos.github_users %}

## Open Source Contributors

<div class="flow-layout">
  {% for user in site.data.repos.github_users %}
    {% include contributors.html username=user %}
  {% endfor %}
</div>

{% endif %}

{% if site.data.repos.github_repos %}

## GitHub Repositories

<div class="flow-layout">
  {% for repo in site.data.repos.github_repos %}
    {% include repos.html repository=repo %}
  {% endfor %}
</div>

{% endif %}



