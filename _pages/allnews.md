---
title: "Wenbo Huang (黄文博) - News"
layout: gridlay
excerpt: "Wenbo Huang"
sitemap: false
permalink: /allnews
---
<div class="col-sm-4" align="right" style="display:table-cell; vertical-align:middle; text-align:center">

  <ul style="overflow: hidden">
  <a href ="https://wenbohuang1002.github.io"> <img align="right" src="{{ site.url }}{{ site.baseurl }}/images/NewsCloud.png" class="img-responsive" width="100%" /></a>
  </ul>
  The shape of the word cloud is <a href ="https://nishinonanase.com"> Nishino Nanase </a><br>
  <ul style="overflow: hidden">
  <a href ="https://wenbohuang1002.github.io"> <img align="right" src="{{ site.url }}{{ site.baseurl }}/images/ActivityR.png" class="img-responsive" width="100%" /></a>
  </ul>
  The word cloud was made by <a href ="https://wordart.com/"> WordArt </a>
</div>


<div class="col-sm-8">

## News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}

</div>