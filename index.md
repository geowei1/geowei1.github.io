---
title: Home
---

# Schorschis page


{:.center}

{% include section.html full=true %}

<!--{% include banner.html image="images/banner.jpg" %} -->

{% include section.html %}

# Highlights

{% capture text %}
In order to contribute to the scientific field of Geographic Information Science we focus on
*	Modeling Indoor Space with focus on Production Environments
*	Ontologies and Semantics related to Geoinformation
*	(spatial) Linked (open) Data 
*	Numerical Methods (Operations Research) in Geography 
*	Agent-based Modeling 
*	Geolinguistics

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
  image="images/osm_graz.png"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

These areas of interest can be of vital interest for a number of application areas 
*	Transport Modeling and Simulation
*	Forest-based Supply Chain: Modeling, Simulation, Optimization
*	DSS for Indoor Production Environments
*	Land Use and Land Cover Modeling
*	Cyberinfrastructuctures and Information sharing 
*	and many more

{%
  include link.html
  link="tools"
  text="Browse our projects"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="resources"
  title="Our Resources"
  flip=true
  text=text
%}
<!--
{% capture text %}
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

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
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
-->
