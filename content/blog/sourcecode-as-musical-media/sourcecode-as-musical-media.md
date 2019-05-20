+++
date = "2019-05-19T08:00:00+00:00"
draft = true
ogpimage = ""
title = "ソースコードがそのまま音楽メディアになるルートの未来はあるか？"

+++
最近、Macのハードディスクをぶっ壊した。幸いなことにバックアップは完璧だったので75GBくらいある音楽のデータファイルも無事だった。

と言ってもここ2、3年はApple Musicでしか新しい音楽を手に入れることはなく、音楽CDを読み込んだのも随分前だ。

それでも何かの抵抗感からAppleMusicの曲をライブラリに追加してDLすることはほぼなく、毎回検索欄から探しては聴いている形にしている。

eメールで手紙から紙が消えたように、音楽もレコードからデータを記録したCDになり、データの直接配信になり、ストリーミングになり。音楽はモノの時代からコトの時代へ。だからこれからはライブとかに回帰する傾向も強くなるでしょう。

その言い方は今っぽくはある。が、個人的には納得しきれないとこもある。

だってデータあるじゃん。少なくとも産業的に音楽を支えて音を記録した何かを作ってそれをベースに配布したりライブをしたりするという行為のルーチンで成り立っている訳で。

大概の曲は5分くらいで終わるし、大概2Chステレオだし、だいたいみんな五線譜で楽譜を書いてDAW（いわゆる音楽制作ソフトウェア全般）で録ったり作り込んだりミックスをして書き出し、という記録をする。

何も出力されたWavファイルだけじゃなくても、楽譜だってDAWのプロジェクトファイルも、みんな音を記述したデータである。

とりあえずそのなんかの記録物を元にして音楽を作る文化は配布の形態よりも根っこにあるところで、まだまだ考える余地がある部分だと思う。

***

と、いうところで一つあり得るのではないか？と思っている音楽配布の形態が、「音楽を生成するプログラム自体が音楽の配布フォーマットになる」というルート。

どういうことかというと、今の音楽のイメージで言えば音楽プレイヤー自体にDAWのようなソフトウェアが搭載されていて、データとしてはプロジェクトファイルがはじめから完成物としてそのまま配布されてくるようなこと。

そうなると今より良くなるであろうことが2つ。

まず、リミックスがめちゃくちゃしやすくなる。これは初めからステムファイルが配られているようなものというか、ステムどころか葉っぱの一枚まで取り出せるようになっているのだから、今より随分ラディカルな作り手側のカルチャーができるかもしれない。

もう一つはアーカイブの問題。音楽のアーカイブは完成品のデータについてばかり言われているけど、その音楽がどうやって作られたかのアーカイブはこれからどんどん問題になると思う。DAWのバージョンもプラグインのバージョンもOSのも上がって昔のファイルはどんどん開けなくなるだろう。Sonarみたいにソフトごと死ぬことも全然ある。DAWのプロジェクトファイルは基本的にメーカーごとに仕様が違って、公開もほとんどされてないし、だいたいバイナリファイルなので読めない。

このプロジェクトファイルが共通化されていて、しかもある程度テキストとしての可読性があって複数種のソフトで開けるようになっていれば、どれかのソフトが死んでも最悪テキストから意図を読み取るぐらいはできるようになる。それを担えるような楽譜フォーマットがあるのかというと、現実的には、ない。なぜなら大概の楽譜記述用言語はドレミの12音と2分音符4分音符のように割っていくリズムを記述するのに特化していて、特殊奏法がどうとかもそうなんだけどDAWで使われているようなエフェクトやシンセサイザーの信号処理が書けない。一つのソースコードから音楽を全て復元できるように言語体系が一つに完結しているとなると、それはもうマークアップというよりプログラミング言語だ。

デメリットについて。

普通に考えると送信するデータは冗長だろうし、携帯プレイヤーにDAWらしきものが乗っかるのは処理も負担だろう。

でも、再生ソフトウェアはプロジェクトファイルを読み取る機能（＝コンパイラ/インタプリタ）だけ持っていれば良いので、実際にはもっと軽量なソフトウェアで良くなる。

それに、フィルターやプラグインなど、使われる物が多い処理は標準ライブラリとしてプレイヤー側で持っておくようにすれば、その分データのやり取りは少なくできる。言い方によっては音質劣化の無い圧縮とも言える。

より深刻なのは、制作データが公開”できてしまう”とこだろう。

配布が容易になることは実質的にコピーすることも容易になるということで、これで音楽を作って売るにしてもどうやってきちんとお金になるのか、というあたり。

それと、エフェクトなどのプラグインはアルゴリズムが隠ぺいされていることで商売が成り立っている側面もある。信号処理のアルゴリズム一つ一つまでソースコードとして配布されるということは、アーカイブしやすさとの引き換えではあるがその商売が成り立たなくなるということでもある。

***

で、実際そんなことが起きる余地があるんだろうか？という話。

古くを辿ればTristan Perichの[1bit Music](http://www.1bitmusic.com/ "1bit music")でやってたようなことが現代のマシンパワーなら48kHz16bitだろうができんじゃね、って話でもあるのですが。

あとは、[Brian EnoのBloom](https://www.generativemusic.com/ "GenerativeMusic")みたく、iPhoneアプリとして音楽を配布しようみたいなのも近い。

もっと身近になりつつある例としては[ゲームのインタラクティブミュージック](https://note.mu/geekdrums/n/naeac6465b1a5 "ゼルダの伝説ブレスオブザワイルドのサントラを買う人が知らないゼルダBGMの裏側")もある。実際Wwise初めゲーム用のオーディオミドルウェアはDAWっぽい雰囲気にもなりつつあるし、こっち側の発展からプログラムとしての音楽配布がライトな形で実現する可能性は無くもないかも。

***

とはいえ一番の問題はそのプロジェクトファイルに当たる音楽プログラミング言語に何使うよ？という話で、

* 楽譜（イベント）レベルの処理と信号処理レベルの処理を一つの言語体系でシームレスに書けて
* 処理の基本的な部分（オシレータとかフィルタとか）を他の低レベルな言語（C++とか）に依存せずに
* かつソースコードが可読性がある

これ全部実現している言語はまだありません（文句は受け付けます）。