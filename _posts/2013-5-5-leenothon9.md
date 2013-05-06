---
layout: page
title: "leenothon #9 のまとめ"
---
{% include JB/setup %}

## 10:00 開始

@soplana宅で開催.  
@crifffしか来ない.  
本日のBGMはドンキャバ, peleなどのマスロック-ポストロック勢. 良い.

## 12:00

やっと全員あつまる.  
今日は新Leenoをリリース予定なので, 現行（5/5現在）Leenoのデータを新Leenoに移行するスクリプトを流し始める.  
ちなみにフルスクラッチで書きなおしたのが本日2度目.

## 12:30 
寿司がやってくる.  

![room1](http://dl.dropboxusercontent.com/u/92653510/blog/leenothon%239/BJeM4d0CAAAEt3o.jpg)

## 13:30 
おかしをくう.  
各々今日のテーマを決めてモクモク作業に入る.
  
@soplana - c++の勉強  
@happs - SSLの勉強  
@crifff - yii2.0の勉強  
@t_hash - jsの勉強とzaimのエラー対応  

## 16:30 
新Leenoへの移行スクリプトが終了したので立ち上げるとデータが重複して登録されているハプニング.  
色々考えた挙句再度修正してスクリプトを流す方が手っ取り早そうなので泣く泣く全削除.  
ちなみにデータ移行の度にS3に数万の画像がpostされるので俺のサイフがマッハ.

![room1](http://dl.dropboxusercontent.com/u/92653510/blog/leenothon%239/le.png)
  
@crifffが飽きてアザゼルさんを読み始める

## 18:30 

はらへ

@soplanaが急に叫びだす


## 19:00 
http://leeno.jp がリリースされる.  
わぁい.


## 19:30
### 本日の発表.

#### @soplana  
[https://gist.github.com/soplana/be09954890281bdcd570](https://gist.github.com/soplana/be09954890281bdcd570)

v8をビルドして, c++で標準入力から受け取った文字をjavascriptのリテラルとして解釈するところまで.


#### @t_hash
[https://gist.github.com/memerelics/5520445](https://gist.github.com/memerelics/5520445)  

sqliteに保存されてるskypeのログをevernoteに日毎に保存するツール. Clojureで実装.

#### @happs
https://gist.github.com/memerelics/5520445  

SSLについて. 通信方式の話と, 暗号化のアルゴリズムに少し触れてた.

#### @crifff

Yii2のソースコード解説. Seleniumを使ったツールの話. あとアイマスやってアザゼルさん読んでた.


## 20:30
毎度おなじみのみずほがまさかの休み.  
急遽馬肉をメインで出してる店に突入.  

![baniku](http://dl.dropboxusercontent.com/u/92653510/blog/leenothon%239/hoge.jpg)


## 23:30
解散.


## #9 ホットワード
- Qiitaは甘え. 男は黙ってmanを見ろ.
- ほっしーの腹からは全くインターネットを感じ無い.
  
##### ※ メンバー全員, Qiitaには感謝しながら使っています


---

<div id="fb-root"></div>
<script>(function(d, s, id) {
  var js, fjs = d.getElementsByTagName(s)[0];
  if (d.getElementById(id)) return;
  js = d.createElement(s); js.id = id;
  js.src = "//connect.facebook.net/ja_JP/all.js#xfbml=1&appId=273010199398913";
  fjs.parentNode.insertBefore(js, fjs);
}(document, 'script', 'facebook-jssdk'));</script>

<script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0],p=/^http:/.test(d.location)?'http':'https';if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src=p+'://platform.twitter.com/widgets.js';fjs.parentNode.insertBefore(js,fjs);}}(document, 'script', 'twitter-wjs');</script>

<div style="float: left; width: 150px;">
<a href="https://twitter.com/share" class="twitter-share-button" data-hashtags="leeno_jp">Tweet</a>
</div>

<div style="float: left; width: 150px;">
<a href="http://b.hatena.ne.jp/entry/" class="hatena-bookmark-button" data-hatena-bookmark-layout="vertical-balloon" title="このエントリーをはてなブックマークに追加"><img src="http://b.st-hatena.com/images/entry-button/button-only.gif" alt="このエントリーをはてなブックマークに追加" width="20" height="20" style="border: none;" /></a><script type="text/javascript" src="http://b.st-hatena.com/js/bookmark_button.js" charset="utf-8" async="async"></script>
</div>

<div style="float: left; width: 150px;">
<div class="fb-like" data-send="true" data-layout="box_count" data-width="150" data-show-faces="true"></div>
</div>

<div style="clear:both;heigth:30px;width:1px"></div>
<div style="clear:both;heigth:300px;width:1px"></div>
<div style="clear:both;heigth:30px;width:1px"></div>

---
