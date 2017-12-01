---
date: 2017-11-20
title: 美大・音大系学生イベントのWebサイトどうにかなんないのか問題
---

突発的な話ですがオチのない憂いについて書きます。

タイトルの通り、美大・音大系学生イベントのWebサイトの製作、あと運用についてどうにかなんないのか?と言う話です。

<!--more-->

# 美術系なのにWebにW◯xの広告が出ててダサい。

いきなり申し訳ありません。これは何もW◯xを責めているわけでは無く主に全国の美大生の個人HPとかで気になる作品を作っている人とかでWebで作品見てみよっかな〜と思った時にドカン！とWixの広告が出てくると作品見る気とか一気に萎えるという私の個人的な感想です。いや趣味の園芸とかのWebページならまだいいですけど、仮にも記録とはいえ人に作品見せるのに対して全然関係ない広告とかがWebにあるの、展示備品に派手な色の値札が貼ってあるよりも個人的には嫌です。

# 本題、学生イベントの話

さて本題は実はちょっと違いまして、美大生が個人Webサイトでそれをやっているのはまあ美大生の責任だとして、問題は集団で企画運営しているイベントです。主に学祭とか。

この場合Web運営としては特徴的な点があって、

- 毎年サイトの運営者が半分以上入れ替わる
- そして毎年Webのテクニカルな面出来る人がいるかいないかにバラつきがある
- （場合によっては半ば授業として半強制的に運営している場合もあるのでモチベーションにもバラつきがある）

ということです。

ある一例を考えましょう。

- ある音楽系大学の年1回の学生運営の作品・研究発表回のWebサイト
- イベントとして継続的に運用しているドメインとFTPサーバーがある
- 2008~09ぐらいから続いてるイベントなので、その頃は細々と学生がHTMLを組んで運用していた
- 2012~13、少しモダンなWeb環境も出てきたし、イベントとして成熟もしてきたので外注してでももうちょっと綺麗なWebを作ったほうがいいのでは？という徴候が現れる

## 2013年

昨年はデザインはまぁ悪くもないんだけど、、今年はデザイナーに依頼したいですね・・・！でもプロに依頼するのもお高いだろうし気が引けるな・・・ということで実行委員の幹部の友達にデザイン系の学生がいるので、彼に依頼しよう、ということになりました。

デザイナーはちょいちょい連絡が遅いけどまぁなんとかなりそうかな・・・

本番が3週間前に迫りそろそろ公開しないといい加減やばいんだけど・・・と焦ってせっついたところ**デザイナーは蒸発しました。**

そこで高校時代文化祭のWebサイトをHTMLとCSSで組んだことはあるけど・・・という一年生に白羽の矢が立ち、2週間前から作り始めどうにか公開にこぎつけました。

当然デザインらしいデザインなどしているヒマが無かったので去年のをほぼほぼコピペ・・・しようと思ったらなんと去年のサイトがWordのHTML出力でソースも何もかもグッチャグチャな事がわかり、基本構造だけは目でトレスしてイチからHTMLを組むハメになりました。

本当は作品の個別紹介とかタイムテーブルとかも載せたかったけど時間がなかったのでパンフレットをPNG化した画像をペタリ（しかもトンボがついてる）。

一年生のWebコーダーは来年はもっとまともなデザインにしたいなあと思うのでした。

## 2014年

去年はパンフレットやチラシを大学関係のイベントをよく引き受けているプロのデザイナーさんがいて、そっちはWebよりは上手く行っていたししかもその方はWebデザインも出来るらしい・・・！とのことで去年の失敗を省みてプロに頼むことにしました。

さて問題は、

- 作品情報をパンフベタ貼りじゃなくてちゃんと個別に情報見られるようにしたい

のですが、なんせ学生イベント、学生の作品情報が（説明書きとかね）があがってくるのが遅いこと遅いこと。これではデータを貰ってデザイナーさんに渡してとやり取りしては間に合いそうにありません。

そこで作品情報だけは2年生に進級した去年のWebコーダーが担当することに。

しかしデザイナーさんも本業は紙の人なのでソースを貰ってみると結構jQueryがいろいろ大変なことになっており、部分的に改造するにも結構苦労します。それにサーバーの権限とか素材のやり取りだけで時間がかかってしまうのもやはり大変ですね。

加えて大量の作品情報を全部テキストファイルでもらい一つ一つHTMLに埋め込んでいくという職人技をしていたので流石にWebコーダーは疲弊しました。

そして悲しくもタイムテーブルはスケジュールが間に合わなかったのでこの年もパンフレットベタ貼りになってしまいました。

## 2015年

Webコーダーは3年生になりました。3年生はもう運営の中心なのでできれば全体の運営を見つつWebの運営は2年生とかの後輩に任せたいなあ、などと思っています。ていうかこの時Webコーダーは全体の実行委員長になってたのでいやいやWebは無理でしょ…などと思っています。

今年はデザイナーは去年と別の人にお願いしており、その人もWebができなくはないが・・・と言う感じだったので去年の事を考えて、カンプだけお願いして実装はこっちでやりましょう。という形になりました。

イベントは冬なので夏休みを使って簡単なWebレクチャーできればな〜・・・

**無理でした。**学生は忙しいんだ。

過去2年の経験に加えてプログラミングを始めていたWebコーダーは手動入力していた学生の作品情報を、Googleアンケートで集めたデータからスプレッドシートをCSVでDL、JSONに変換してHTMLテンプレートに出力する完璧なワークフローを確立したりしていました。

しかしそれでも製作が一人に集中してしまうのでタイムテーブルについてはパンフレットべた張りを回避することが出来ませんでした。

こうしてWebの運用はほぼ全てWebコーダー兼運営委員長という謎の役職が行うことによってどうにか乗り切れたのでした。もう4年生はこのイベントには参加しないので頑張って技術的な引き継ぎをするぞ！と誓います。

## 2016年

しかし時既に遅し。

基本的な引き継ぎはしたもののやっぱりいろいろな伝え漏れがあり本番2週間前ぐらいにしてドメインを更新し忘れ失効してしまいました（口座とか予算とか色んな都合でドメインは毎年銀行振込で1年更新にしていたのです）。

その後追加のフォローアップで後輩にドメインやFTP操作を教えたりhtmlを教えることで昨年の構造を上手く使いまわして難を乗り切ったのでした。

## 2017年

今年もドメインが切れた。

# 何が問題なのか

- 無料サービスを使うと広告が出てきてダサい、ドメインがダサい
- サービスにお金を払って広告を消す、独自ドメイン取るのにちょっと知識がいる
- 外注するとクオリティは上がるがコミュニケーションコスト&時間ロスがある
- たまたま技術がある人間が自作すると上手くいくがそいつがいなくなって以降よりヤバくなる（かつ技術力だけあってデザイン力がないとダサくなるというリスクも）

という、**Web知識、お金、コミュニケーションコスト、製作期間**あたりが絶妙なバランスで上手く行かず、加えて**継続運用**の問題というのがあって、

- 無料サービスを使うとエクスポートが殆どできない、出来てもWordpressとか
- 一度静的サイトを普通のサイトでホストしてしまうと、途中からもっと簡単にやりたい！と思って無料サービスとかに乗り換えたとき過去のサイトが閲覧できない
- Wordpressとかを導入して、過去のサイトは静的ページで見られるようにしてそれ以降はWordpressで、、、というのも不可能ではないが果たしてWordpressのバックエンドを継続的に学生が運用できるだろうか・・・？

という辺りで、Web作成サービス使うと永遠にそのサービスを使い続けることになる、やめたらサイトは消えて永遠に見られない、しかし静的Webをホストし続けるには毎年一人はそれなりに知識を持っている人がいる必要がある、、、といったジレンマがあります。

過去の情報が消えるのは結構問題だと思っていて、美術展のサイトが全然残ってない問題とかも最近指摘され始めていますが、特に毎年継続してやっているイベントなのに過去の情報に自分たちでアクセスできなくて毎年同じ試行錯誤を繰り返す・・・とかは結構バカっぽいと思います。

# 結論

静的Webをとにかくイージーに扱えるサービスがあればそれで十分なんじゃないだろうか。

最近だとそういうジェネレータ用のフロントエンドがいくつかあって商用サービスもあり

<https://appernetic.io/>

<https://www.datocms.com/>

<https://www.netlify.com/>

この辺が日本語化されてサーバーの導入移行あたりまでスムーズにサポートしてくれればそれなりにお金払う価値もあるよね・・・などと思ったりした。

# 余談

なお4年になったWebコーダー兼運営委員長は自分の卒業制作展のWebサイトは出来るとこまで好き放題にやった結果Riot.jsを使った妙にモダンなSPAサイトを作ったのだった。タイムテーブル⇔作品情報の双方向の行き来と無駄に凝ったレイアウトのインタビューページを作ったりとやりたかったことを全部詰め込んだので満足して卒業したそうです。本当に反省している

[これ](http://onkansotsuten.com)

本題の方のサイトのURLも別に貼ってもいいんですがやめておきます、なぜならドメインが切れてて見られないから…（主に関係者の方、うろ覚えなので一部歴史の捏造が発生してたかもしれませんがあくまでこういうことって発生するよねというのを伝えたかっただけなので・・・全体的に自分の引き継ぎ不足がだいたい悪いです・・・ごめんなさい・・・）