---
title: Home
---
<span style="font-size:1.5em;">
We are researchers at the [Kennedy Institute of Rheumatology, University of Oxford](https://www.kennedy.ox.ac.uk/). We develop statistical methods and computational software to better understand the genetic contribution to immune-mediated traits.</span>
{% include section.html full=true %}
<!-- {% include banner.html image="images/Oxford_DNA.jpg" %} -->
{% include section.html %}
<!-- # Hightlights -->
{% capture text %}
Find out about what we have published and our ongoing research projects.

{%
  include link.html
  link="research"
  text="Find out what we have published"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/research.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}
We believe in open and reproducibility in science. We publish free software, bioinformatic pipelines and datasets.

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
  image="images/HLA-TAPAS-pipeline.png"
  link="resources"
  title="Our Tools"
  flip=true
  text=text
%}

{% capture text %}
We are a team of researchers that want to push the frontier of data science. We strive to build an inclusive environment for research, and recognize the value of diversity in the process of discovery.

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




