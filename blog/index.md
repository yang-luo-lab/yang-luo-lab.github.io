---
title: News
nav:
  order: 4
  tooltip: Musings and miscellany
---

# <i class="fas fa-feather-alt"></i>News

{:.center}

{% capture col1 %}
{%
    {% include search-info.html %}

    {% include list.html data="posts" component="post-excerpt" %}

%}
{% endcapture %}
{% capture col2 %}
{%
  include figure.html
  image="https://cdn.britannica.com/03/117103-050-F4C2FC83/view-University-of-Oxford-England-Oxfordshire.jpg"
  caption="Univeristy of Oxford"
%}
{% endcapture %}
{% include two-col.html col1=col1 col2=col2 %}
<!-- {% include section.html %}

{% include search-info.html %}

{% include list.html data="posts" component="post-excerpt" %}

{% include section.html %}

## News

<!-- Twitter embeds from https://publish.twitter.com/ -->

<!-- <a class="twitter-timeline" data-width="400" data-height="400" href="https://twitter.com/yluo86">Tweets by Yang Luo</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
{:.right}

<a href="https://twitter.com/yluo86?ref_src=twsrc%5Etfw" class="twitter-follow-button" data-show-count="false">Follow @yluo86</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
<a href="https://twitter.com/intent/tweet?screen_name=yluo86&ref_src=twsrc%5Etfw" class="twitter-mention-button" data-show-count="false">Tweet to @yluo86</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
{:.center} --> 
