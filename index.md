
--- 
layout: page 

---

</span></p>
<h1 style="margin: 0.0px 0.0px 16.1px 0.0px; font: 24.0px Times; color: #000000; -webkit-text-stroke: #000000"><span class="s1"><b>Posts</b></span></h1>
<ul class="ul1">
  <li class="li1"><span class="s2"></span><span class="s1">{% for post in site.posts %}</span></li>
  <li class="li1"><span class="s2"></span><span class="s1">{{ post.date | date: "%b %-d, %Y" }} <a href="file:///Users/lixialin/lxlkkj.github.io/%7B%7B%20post.url%20%7C%20prepend:%20site.baseurl%20%7D%7D"><span class="s3"><b>{{ post.title }}</b></span></a></span><span class="s4"><b> <br>
</b></span></li>
  <li class="li1"><span class="s2"></span><span class="s1">{% endfor %}<span class="Apple-converted-space"> </span></span></li>
</ul>
<p class="p3"><span class="s1">subscribe <a href="file:///Users/lixialin/lxlkkj.github.io/%7B%7B"><span class="s5">via RSS</span></a></span></p>
</body>
</html>
