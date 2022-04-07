---
title: Home
---

# SARS-CoV-2 Research Initiative at OHSU

[devin schoen](https://github.com/devin-schoen) is testing out webpages


{:.center}

{% include section.html full=true %}

{% include banner.html image="images/ohsu3.png" %}

{% include section.html %}

# Highlights

{% capture text %}
short description of our research

{%
  include link.html
  link="research"
  text="See what we've published"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/research.png"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}
short description of the tools we use

{%
  include link.html
  link="tools"
  text="Browse our tools"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/resources.png"
  link="resources"
  title="Our Resources"
  flip=true
  text=text
%}

{% capture text %}
short description of our team

{%
  include link.html
  link="team"
  text="Meet our team"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/team.png"
  link="team"
  title="Our Team"
  text=text
%}

