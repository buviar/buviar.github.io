---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

We have a collaborative research team from diverse backgrounds. The team includes students at all levels,

{% include section.html %}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: graduate"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: programmer"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: undergrad"
%}
{:.center}

{% include section.html background="images/banner.jpg" dark=true%}

If you are interested to join us, send your CV and cover letter to buviar@boun.edu.tr

{% include section.html %}


## Funding

Our work is made possible by funding from several organizations.
{:.center}

{%
  include gallery.html
  style="square"

  image1="images/photo.jpg"
  link1="https://nasa.gov/"
  tooltip1="Cool Foundation"

 
%}
