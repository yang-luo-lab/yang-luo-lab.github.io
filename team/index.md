---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

We are actively looking for talented people with interests in statistical modelling, transcriptomics, proteomics, genomics and immunology to join the team.

We are creative, hard-working, open and fun!


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
  filters="role: postdoc"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd"
%}


{:.center}

{% include section.html %}


## Join us
**We are hiring!**

- 📌 *Postdoctoral Fellows*: Send your CV, a summary of research accomplishments, and ideas for future research.  
- 🎓 *DPhil candidates*: Contact us to discuss project opportunities.  

{% include link.html type="email" link="yang.luo@kennedy.ox.ac.uk" text="Apply Now" icon="" style="button" %}
{:.center}

{% include banner.html image="images/lab_jump.JPG" %}

{% include section.html %}

## Alumni
{% include list.html data="members" component="portrait" filters="role: alumni" %}
{:.center}

{% include section.html %}