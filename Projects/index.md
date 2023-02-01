---
title: Projects
nav:
  order: 6
  tooltip: Projects
---

# <i class="fas fa-microscope"></i>Projects
The lab has several ongoing projects.

{% include search-info.html %}

{% include section.html %}

## Projects

{% include list.html component="card" data="projects"%}


# Highlights

{% capture text %}
Three studies were conducted in our lab in last year. These includes: The effect of distorted avatar capabilities on perceived affordances, Body schema during tool-use via VR technologies and Studying preservice teachers’ SRL via VR technologies .

{%
  include link.html
  link="research"
  text="See our projects"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/buviar_projects.PNG"
  link="research"
  title="Our Research"
  text=text
%}
