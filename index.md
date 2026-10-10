---
---

# Pendergrass Lab Website

The Pendergrass Lab at Oberlin College uses satellite data to track pollution back to its source, monitor emissions, and diagnose the drivers of pollution change. By illuminating the social, meteorological, and ecological drivers of pollutant emissions, we identify areas of joint air quality and climate action.

{% include section.html %}

## Highlights

{% capture text %}

We combine physical models of the atmosphere with machine learning and Bayesian statistics. Our goal is to transform remote sensing observations of atmospheric composition into actionable information about the source and fate of reactive air pollutants and greenhouse gases.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

In addition to publishing our findings in peer-reviewed journals, we maintain open-source software called [CHEEREIO](https://cheere.io) used by research groups around the world to quantify emissions of greenhouse gases and air pollutants. We also publish large high resolution pollution maps for use in public health studies, regulation, and other applications.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

We are currently hiring Oberlin College undergraduate students as research assistants! Interested students should contact the principal investigator, Drew Pendergrass, to join.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}
