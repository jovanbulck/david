---
permalink: /
#title: "About me"
#excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
{% include base_path %}

{% if page.author and site.data.authors[page.author] %}
  {% assign author = site.data.authors[page.author] %}{% else %}{% assign author = site.author %}
{% endif %}

# About me

I am a postdoctoral researcher at the Department of Business Informatics and Operations Management at [Ghent University](https://www.ugent.be/en), Belgium.
My main research interests are in the design and analysis of operations management tools for optimization problems, with a special focus on fairness issues, algorithm benchmarking, and the integration of machine learning within operations management.

<a name="pubs"></a>
# Publications

{% include fmt-pub.html %}

<a name="teaching"></a>
# Teaching

{% include fmt-edu.html %}

<a name="talks"></a>
# Talks

{% include fmt-talk.html %}

<a name="awards"></a>
# Awards and Grants

{% include fmt-award.html %}

<a name="service"></a>
# Academic Service

{% include fmt-service.html %}

<a name="projects"></a>
# Selected Community Projects

{% include fmt-foss.html %}