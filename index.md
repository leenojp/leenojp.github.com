---
layout: page
title: ✧*。ヾ(｡>﹏<｡)ﾉﾞ。*✧
---
{% include JB/setup %}


## member
---

### soplana
##### バトルマスターLv64です。イオナズンは得意ではありません。

### happs
##### Linuxも胃腸も、大切な身体の一部なんです。

### hash
##### ねぇ、知ってる？ 秒速5センチなんだって。うどんを啜るスピード。

### criff
##### いい？ アナタの目に映る全ての物が、PHPだと思ってはダメ。

### tomitomiclub
##### 永久欠番

### azunyan bot
##### この瞬間も、死んでゆくのは、いつだって他人ばかり。

### ishiki_check bot
##### ティッシュの一枚目が上手に取れない奴は、大体何をやらしてもダメ。


## irc
---
特に誰もいないけど、azunyan botとishiki_check botがお出迎えしてくれるirc部屋  
「ishiki_check」とか「ペロペロ」とかに反応する可愛いbot達

irc://irc.leeno.jp:6667 / #guest
    
## blogs 
---

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

