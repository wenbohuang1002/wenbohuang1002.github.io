---
title: "Wenbo Huang (黄文博) - Homepage"
layout: gridlay
excerpt: "Wenbo Huang"
sitemap: false
permalink: /
---

<div id="top"></div>
<div class="container-fluid">
<div class="row">
<div class="col-sm-8">

### <strong>About Me</strong>
<!-- <a href ="https://wenbohuang1002.github.io/allnews"> <img align="left" src="{{ site.url }}{{ site.baseurl }}/images/Eagle.png" class="img-responsive" width="35%"  /> </a> -->
I was a <del>script kiddie</del> and received the B.S. degree from <a href="http://www.njtech.edu.cn/">Nanjing Tech University</a>, Nanjing, China, in 2019. I am currently 
pursuing the M.S degree of <a href="http://www.njnu.edu.cn/">Nanjing Normal University</a>, Nanjing, China. I am looking for a passionate research group to sutdy for Ph.D.
<br>
My research interests including Machine Learning, Deep Learning, Computer Vision and Human Activity Recognition. My advisor is <a href="http://d.njnu.edu.cn/person/3288.html">A.P Lei Zhang</a> now. 
By the way, I must express my gratitude to <a href="https://sci-hub.se/alexandra">Alexandra Elbakyan</a>. The website built by her helps me much on paper writing and search.
Everyone can find the papers they need <a href="https://sci-hub.st/">here [Sci-Hub]</a>.
<br>
→ <font color="white">The Homepage is designed under my self-righteous aesthetics</font> ← <br>
<!-- <del>Select the part inside the arrow to reveal the hidden content.</del> -->

<!-- <script type="text/javascript" id="clstr_globe" src="//clustrmaps.com/globe.js?w=128&d=Xit1o4P9tPO4V5F-vf13Il6mKflR-sERYSPiKcWoLcM"></script> -->

<!-- ### <strong>Skills & Hobbies (Sort by Proficiency)</strong>

#### <strong>Skills</strong>
* Languages
    - Python (PyTorch, Jittor, Keras, TensorFlow).
	- C#, LaTeX.
	- SQL, Kotlin.

#### <strong>Hobbies</strong>
* Sports
    - Cycling.
	- Rope Skipping.

* Recreation
    - Drum Set.
	- Card Game (OCG like Yo☆Gi☆Oh).
	- Drawing. -->


### <strong>CV</strong>
You can download my latest [CV (English Version)](https://wenbohuang1002.github.io/papers/Wenbo Huang's CV.pdf) and [CV (Chinese Version)](https://wenbohuang1002.github.io/papers/黄文博的简历.pdf).<br>
CV was last updated on October 25, 2021.<br>
<!-- <pre>
                            CV was last updated on October 25, 2021.
　　　　　／＞＿＿＿フ       
　　　　　|  　_　 _|   
　 　　　／  ミ  ˇ ノ  
　　 　 /　　　 　 |
　　　 /　 ヽ　　 ﾉ
　 　 │　　|　|　|
　／￣|　　 |　|　|
　| (￣ヽ＿_ヽ_)__) 
　＼二つ
</pre> -->

### <strong>News</strong>
{% for article in site.data.news limit:8 %}
{{ article.date }} :
<em>{{ article.headline }}</em>
{% endfor %}
#### <a href="{{ site.url }}{{ site.baseurl }}/allnews.html">[See All News]</a>
#### <a href="#top">[Go Back to Top]</a>

</div>

<div class="col-sm-4" style="display:table-cell; vertical-align:middle; text-align:center">

  <ul style="overflow: hidden">
  <a href ="{{ site.url }}{{ site.baseurl }}/experience"> <img src="{{ site.url }}{{ site.baseurl }}/images/adminR.jpg" class="img-responsive" width="100%" /></a>
  </ul>

  <!-- <br clear="all" /> -->

  Wenbo Huang (黄文博)<br>  
  401, Qi Ming Building (<a href="https://j.map.baidu.com/f3/pAk">Maps</a>).<br>  
  <a href="http://d.njnu.edu.cn/research-area/3205.html">Institute of Infirmation and Control Technologies</a>  <br>  
  <a href="http://d.njnu.edu.cn/">School of Electric and Autumation Engineerning</a> <br>  
  <a href="http://www.njnu.edu.cn/">Nanjing Normal University</a> <br>  
  Nanjing, Jiangsu, China. <br>  
  <script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=00acff&w=268&t=tt&d=Xit1o4P9tPO4V5F-vf13Il6mKflR-sERYSPiKcWoLcM&ct=000000&co=ffffff&cmo=f87d00&cmn=00ff10'></script>
  <a href="{{ site.url }}{{ site.baseurl }}/treasures"><font color="white">All failures are my treasures.</font></a> <br>  
</div>

</div>
</div>

<div class="col-sm-12">

### <strong>Publications (<font color="red">Journal Papers</font> <font color="green">&</font> <font color="blue">Conference Papers</font>)</strong>

{% for publi in site.data.publist limit:100 %}

<div class="col-sm-11 clearfix">
 <div class="well">
 <pubtit>{{ publi.title }}</pubtit>

 <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="200px" style="float: left" />

 <p>{{ publi.description }}</p>

 <p><em>{{ publi.authors }}</em></p>

 <p>{{ publi.venue }}</p>
 
 <p>{{ publi.name }}</p>
 
 <p>{{ publi.DOI }}</p>

 {% if publi.number_link == 1 %}
 <p>[<a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>]</p>
 {% endif %}

 {% if publi.number_link == 2 %}
 <p>[<a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>]
 [<a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>]</p>
 {% endif %}

 {% if publi.number_link == 3 %}
 <p>[<a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>]
 [<a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>]
 [<a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a>]</p>
 {% endif %}

 {% if publi.number_link == 4 %}
 <p>[<a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>]
 [<a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>]
 [<a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a>]
 [<a href="{{ publi.link4.url }}">{{ publi.link4.display }}</a>]</p>
 {% endif %}

 {% if publi.number_link == 5 %}
 <p>[<a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>]
 [<a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>]
 [<a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a>]
 [<a href="{{ publi.link4.url }}">{{ publi.link4.display }}</a>]
 [<a href="{{ publi.link5.url }}">{{ publi.link5.display }}</a>]</p>
 {% endif %}

 {% if publi.number_link == 6 %}
 <p>[<a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>]
 [<a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>]
 [<a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a>]
 [<a href="{{ publi.link4.url }}">{{ publi.link4.display }}</a>]
 [<a href="{{ publi.link5.url }}">{{ publi.link5.display }}</a>]
 [<a href="{{ publi.link6.url }}">{{ publi.link6.display }}</a>]</p>
 {% endif %}

 </div>
</div>

{% endfor %}

<br clear="all"/>

#### <a href="{{ site.url }}{{ site.baseurl }}/publications">[See All Publications]</a>

</div>

<div class="col-sm-12">

#### <a href="#top">[Go Back to Top]</a>

### <strong>Theses</strong>

{% for publi in site.data.theseslist limit:6 %}

<div class="col-sm-11 clearfix">
 <div class="well">
 <pubtit>{{ publi.title }}</pubtit>

 <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="200px" style="float: left" />

 <p>{{ publi.description }}</p>

 <p><em>{{ publi.authors }}</em></p>

 <p>{{ publi.venue }}</p>
 
 <p>{{ publi.name }}</p>
 
 <p>{{ publi.DOI }}</p>

 {% if publi.number_link == 1 %}
 <p>[<a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>]</p>
 {% endif %}

 {% if publi.number_link == 2 %}
 <p>[<a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>]
 [<a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>]</p>
 {% endif %}

 {% if publi.number_link == 3 %}
 <p>[<a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>]
 [<a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>]
 [<a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a>]</p>
 {% endif %}

 {% if publi.number_link == 4 %}
 <p>[<a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>]
 [<a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>]
 [<a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a>]
 [<a href="{{ publi.link4.url }}">{{ publi.link4.display }}</a>]</p>
 {% endif %}

 {% if publi.number_link == 5 %}
 <p>[<a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>]
 [<a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>]
 [<a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a>]
 [<a href="{{ publi.link4.url }}">{{ publi.link4.display }}</a>]
 [<a href="{{ publi.link5.url }}">{{ publi.link5.display }}</a>]</p>
 {% endif %}

 {% if publi.number_link == 6 %}
 <p>[<a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>]
 [<a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>]
 [<a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a>]
 [<a href="{{ publi.link4.url }}">{{ publi.link4.display }}</a>]
 [<a href="{{ publi.link5.url }}">{{ publi.link5.display }}</a>]
 [<a href="{{ publi.link6.url }}">{{ publi.link6.display }}</a>]</p>
 {% endif %}

 </div>
</div>

{% endfor %}

<p> &nbsp; </p>

</div>

#### <a href="#top">[Go Back to Top]</a>

### <strong>Academic Related</strong>

#### <strong>Academic Service</strong>
* <strong>Journal Reviewer</strong>
    - <a href="https://www.mdpi.com/journal/sensors">MDPI Sensors</a>, 2021

* <strong>Conference Reviewer</strong>
    - I am working on it...

#### <strong>Award & Honor</strong>
* <strong>Competition</strong> 
    - Provincial Third Prize, The 17th "Challenge Cup" National University Student Extracurricular Academic Science and 
	Technology Works Competition "Science and Technology" Special Competition, 2021

* <strong>Scholarship</strong>
    - National Scholarship for Postgraduate Students in 2021 (rank 1, total 65)
	- First-class Academic Scholarship of Nanjing Normal University in 2021 (rank 6, total 65)


#### <a href="#top">[Go Back to Top]</a>

### <strong>Research Partners (Partial)</strong>

#### <strong>Research Advisors</strong>
<div style="width: 14%; float: left; min-width: 9em;">
<img loading="lazy" width="98%" height="98%" style="border-radius: 10%;" src="../images/partnet/leizhang.jpg"/>
<p style="text-align: center;"> <a href="http://d.njnu.edu.cn/person/3288.html">Lei Zhang</a><br />Associate Professor<br />NNU</p>
</div>

<div style="width: 14%; float: left; min-width: 9em;">
<img loading="lazy" width="98%" height="98%" style="border-radius: 10%;" src="../images/partnet/junhe.jpg"/>
<p style="text-align: center;"> <a href="https://sites.google.com/site/hejunzz/">Jun He</a><br />Associate Professor<br />NUIST</p>
</div>

<div style="width: 14%; float: left; min-width: 9em;">
<img loading="lazy" width="98%" height="98%" style="border-radius: 10%;" src="../images/partnet/haowu.jpg"/>
<p style="text-align: center;"> <a href="http://www.ise.ynu.edu.cn/teacher/805">Hao Wu</a><br />Associate Professor<br />YNU</p>
</div>

<div style="width: 14%; float: left; min-width: 9em;">
<img loading="lazy" width="98%" height="98%" style="border-radius: 10%;" src="../images/partnet/aiguosong.jpg"/>
<p style="text-align: center;"> <a href="https://scholar.google.com/citations?hl=zh-CN&user=RjQ5TrEAAAAJ">Aiguo Song</a><br />Professor<br />SEU</p>
</div>

<div style="clear:both"></div>

#### <strong>Schoolmates</strong>

<div style="width: 14%; float: left; min-width: 9em;">
<img loading="lazy" width="98%" height="98%" style="border-radius: 10%;" src="../images/partnet/qiteng.jpg"/>
<p style="text-align: center;"> <a href="https://github.com/tengqi159">Qi Teng</a><br />Ph.D Student<br />NJU</p>
</div>

<div style="width: 14%; float: left; min-width: 9em;">
<img loading="lazy" width="98%" height="98%" style="border-radius: 10%;" src="../images/partnet/kunwang.jpg"/>
<p style="text-align: center;"> <a href="https://github.com/KennCoder7">Kun Wang (Kenn)</a><br />Ph.D Student<br />SEU</p>
</div>

<div style="width: 14%; float: left; min-width: 9em;">
<img loading="lazy" width="98%" height="98%" style="border-radius: 10%;" src="../images/partnet/yintang.jpg"/>
<p style="text-align: center;"> <a href="https://yinntag.github.io/">Yin Tang</a><br />M.S Student<br />NNU</p>
</div>

<div style="width: 14%; float: left; min-width: 9em;">
<img loading="lazy" width="98%" height="98%" style="border-radius: 10%;" src="../images/partnet/xingwang.jpg"/>
<p style="text-align: center;"> <a href="https://github.com/Chauncey-Wang">Xing Wang</a><br />M.S Student<br />NNU</p>
</div>

<div style="clear:both"></div>

#### <a href="#top">[Go Back to Top]</a>

