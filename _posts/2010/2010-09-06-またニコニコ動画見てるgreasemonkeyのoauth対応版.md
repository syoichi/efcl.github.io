---
title: またニコニコ動画見てるGreasemonkeyのOAuth対応版
author: azu
layout: post
permalink: /2010/0906/res1930/
SBM_count:
  - '00012<>1355446135<>10<>0<>1<>1<>0'
  - '00012<>1355446135<>10<>0<>1<>1<>0'
dsq_thread_id:
  - 300802726
categories:
  - Greasemonkey
  - ニコニコ動画
tags:
  - Greasemonkey
  - twitter
  - ニコニコ動画
---
2010.8月末にTwitterのBASIC認証が終わったので、今までのまたニコぐりもんは動かなくなっていると思います。  
なのでOAuth認証に対応してるまたニコニコ見てるを作ってみました。(作ったのは結構前だけどね)

*   [mataniconicomiteru for Greasemonkey][1]

### 使用方法

まずはニコニコ動画の動画ページでステータスバーのGreasemonkeyアイコンを右クリック→ユーザースクリプトコマンドからOAuth認証をする必要があります。   
[<img class="alignnone size-medium wp-image-1938" title="ss-2010-09-06-1" src="http://efcl.info/wp-content/uploads/2010/09/ss-2010-09-06-11-300x95.png" alt="" width="300" height="95" />][2]

コマンドを実行するとOAuth認証のパネルが出てくるので、ボタンからTwitterへ行きOAuth認証してPINコードをコピーしてテキストエリアに入力すると準備完了です。  
[<img class="alignnone size-medium wp-image-1939" title="large" src="http://efcl.info/wp-content/uploads/2010/09/large-300x192.png" alt="" width="300" height="192" />][3]

認証済みだったら動画タイトル部分にまたニコのボタンが出るので、それをクリックしてコメントを入力してまたボタンを押せばTwitterへ投稿できます。(nico.msのURLを使って投稿します。  
[<img class="alignnone size-full wp-image-1940" title="input_mata" src="http://efcl.info/wp-content/uploads/2010/09/input_mata.png" alt="" width="482" height="78" />][4]

オリジナルの機能としてはコメント入力欄の右側に文字数のカウンターが付いてるぐらいです。

**mataniconicomiteru for Greasemonkey**
:   [http://userscripts.org/scripts/show/83795][5]

&nbsp;

 [1]: http://userscripts.org/scripts/show/83795
 [2]: http://efcl.info/wp-content/uploads/2010/09/ss-2010-09-06-11.png
 [3]: http://efcl.info/wp-content/uploads/2010/09/large.png
 [4]: http://efcl.info/wp-content/uploads/2010/09/input_mata.png
 [5]: http://userscripts.org/scripts/show/83795 "mataniconicomiteru for Greasemonkey"