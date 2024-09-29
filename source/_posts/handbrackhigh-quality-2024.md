---
title: Handbrack产品的输出画质下降？揭秘手动配置High Quality设定技巧 - 2024版
date: 2024-08-30T16:53:21.614Z
updated: 2024-08-31T16:53:21.614Z
categories:
  - macxdvd
thumbnail: https://thmb.techidaily.com/3268231cc2e746a9acbe27cd5a06636ae1bf5dfa48dd515083acffe73b657f8a.jpg
---

## Handbrack产品的输出画质下降？揭秘手动配置High Quality设定技巧 - 2024版

[ホーム](https://tools.techidaily.com/macxdvd/products/)[Blog](https://tools.techidaily.com/macxdvd/products/) \>Handbrake高画質設定方法

## 【2024保存版】Handbrakeで出力画質が劣化！Handbrake高画質設定方法を詳しく解説！

**Handbrake 画質悪いに困っているか**

HandBrake（ハンドブレイク/ハンドブレーキ）とは、DVD等の動画ファイルをMPEG-4ビデオに変換するフリーソフトウェア、オープンソース、GPLライセンス、マルチ・スレッド、クロスプラットフォームのトランスコーダーソフトとして広く知られる。独自の使い勝手の良さと魅力で愛用者がたくさんいる。ところが、最近Handbrakeを利用してDVDや動画ファイルを変換する際に、オリジナルと比べて画質が大幅に落ちてしまうという不満な声が多い。出力画質を何より重視している方にとって本当に厄介なことである。

Handbrakeで変換後のファイルの画質劣化や画質悪い状況において、対処法があるか。実に、Handbrakeの高画質設定をすれば、完全無劣化ってほどじゃなくても、スマホやiPhone、iPad、Android、タブレットなどテレビよりも小さな画面で見る時、画質の低下が目に見えないことができる。では、どういう設定をすればHandBrake高画質になるか。次の内容を最後まで読んでください。



## （Part1）Handbrakeのコントロールパネルから利用できる設定項目

「画質」というのは、数値的に判断するべきものではなく、常に結果論である。結果として人が見た感性によって判断されるのが「画質」。Handbrakeのエンコード設定の設定値で画質に影響するのは、「ビデオコーデック（圧縮率）」、「ビットレート」、「フレームレート」、「2パスエンコード（2-Pass Encoding）」、「Turbo first Pass」などがある。

![VR変換フリーソフト](https://www.macxdvd.com/blog/img/smart-handbrake-high-quality-settings01.jpg)

**■ Video**

**1\. Video codec（ビデオコーデック）：**符号化方式を使って動画データのエンコード（符号化）とデコード（復号）を双方向にできる装置やソフトウェアなどのこと。Handbrakeは4つの出力ビデオコーデック（H.264、MPEG-4、MPEG-2とH.265）を搭載している。

MPEG-4はMPEG-2に比べてより高画質・低容量な動画形式とされる。そして、「H.265」は「H.264」の半分のファイルサイズ・ビットレートで同等の画質を実現できる。「H.264」は、MPEG-2の2倍、「H.265」は、MPEG-2の4倍の圧縮率を実現する。つまり、ファイルサイズが決まっているならば、画質の綺麗さはほぼH.265＞H.264 / MPEG-4＞MPEG-2ということである。ちなみに、H.264かなり普及している動画のコーデックで、PCブラウザ、スマホとも全般的に使える。

**2\. Frame rate（フレームレート）：**動画において、単位時間あたりに処理させるフレーム数（静止画像数、コマ数）である。一般的には、フレームレートを高くすると、より動画の動きを滑らかに表現することができる。それにより、動画の容量も増える。だが、フレームレートは高ければ高いほどいいとは言えない。例えば、ネットで動画を視聴する場合、見る人のPC環境によっては、あまりに高いフレームレートだとPCの処理が追いつかずカクつき。また、ネットの回線速度にも影響し回線速度が遅いと同様にカクつき。ご使用用途に合って適宜なフレームレート数値を設定したほうがいい。

**■ Quality**

**1\. Constant Quality（品質固定）：**各フレーム、各シーンを一定の品質に保つようにビットレートを割り振るという。 コーデックに "H.264" を選択した場合は、0から51のスケールになり、値が低いほど高画質。(0=Lossless) 。通常、SDの場合は、 20+/-1 程度、HDの場合は、 22+/-1 程度が適当とされる。 コーデックに "MPEG-4/2" を選択した場合は、1から31のスケールになる、値が低いほど高画質。コーデックに "VP3" を選択した場合は、値が高いほど高画質となる。

**2\. Avg Bitrate (kbps)（平均ビットレート）：**出力ファイルサイズを目標とするサイズに収めたい場合に使用する。2-Passエンコードが推奨される。

**■ Optimise Video**

**1\. Use Advanced Tab Instead：**チェックを入れると、 "Advanced Tab" で表示される設定項目を利用できるようになる。

**2\. Encoder Preset（エンコードプリセット）：**最左端の「Ultra Fast」から右端の「Very Slow」、「Placebo」まで10種類のエンコード速度を選ぶ可能。右に行くほどエンコード速度が遅くなり、圧縮効果が高い。

**3\. Encoder Tune：**それぞれ映像に応じた調整を行う。

filmは実写の動画向きに最適化される。  
animationはアニメ向けに最適化される。  
grainはざらざらが残るような古い映画などをエンコードする際に使われる。  
stillimageは、スライドショーなど、動きのほとんどない場合に使う。

**4\. Fast Decode（デコード高速化）：**再生時の負荷を下げる調整。デコード時の計算量が多いCABACおよびin-loop deblockingを無効にし、デコードの際の負荷を減らす。その分画質は落ちる。 モバイル機器など、貧弱な環境向けにエンコードしたい場合に使う。

**5\. Encoder Profile（エンコーダプロファイル）：**「Auto」, 「Baseline」, 「Main」, 「High」から再生環境に適したものを選択する。

**6\. Encoder Level：**1.0から5.2までの各レベルから再生環境に適したものを選択する。Autoは最適値として推奨される。



<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
## （Part2）上記の詳細設定項目を利用して、Handbrake高画質設定方法を解説！

Handbrakeコントロールパネルから利用できる詳細な設定項目の知識を紹介した後、いよいよ動画のビットレートや、コーデックなどの設定によって、Handbrakeで高画質変換する方法を解説する。

**出力ファイルサイズ：**動画のサイズ（容量）は基本的に動画のビットレートと長さによって決まっている。HandBrakeは、自動的に出力サイズの大きさによって最適したビットレートを推奨してくれる。だが、ソース動画サイスをあまりにも小さくする場合、画質が大幅に落ちることがになる。画質の劣化を極力おさえながら、データサイズを小さくするのは簡単なことではない。

ファイルサイズに厳しい制限がない場合、以下のHandbrake高画質設定方法通り、やってみてください。

ここでは、DVDや動画を変換する際に、動画ビットレート率の具体的な計算方法をご紹介する。ビットレート=出力幅x出力の高さx K x R。 ご注意：ビデオコーデックによって、K数値も異なる。（H.264 k=0.012345、MPEG-4 k=0.0135）、R数値はご望みの画質によって指定するものである（最高画質r=1, 高画質r=0.55, 一般画質r=0.35）。

上記のビットレート率計算式に基づいて、720Pの動画を480PへHandbrakeで高画質変換するには、  
720P(1080 x 720) h.264 最高ビットレート=9599 kbps, 高ビットレート=5279 kbps, 一般ビットレート=3359 kbps  
720P(1080 x 720) mpeg4最高ビットレート=10497 kbps, 高ビットレート=5773kbps, 一般ビットレート=3674kbps

これで、ビデオコーデックと好みのファイルサイズに従って、簡単にビットレートの最適値を計算できる。だが、この最適値はすべてのケースではなく、あくまでも大多数のケースに適用されるのである。場合によっては誤差があるかもしれない。

出力ファイルサイズと平均ビットレートの設定によって、ビデオの画質を犠牲して、ファイルサイズを制御することができるようになる。一方、Constant Quality（品質固定）モードはその逆である。期待の画質に合って、HandBrakeは自動的にビットレートをカスタマイズしてくれる。ビットレート数値が勝手に変わっているため、出力ファイルサイズの大きさもそれぞれである。画質を保ちたいなら、Quality Setting > Constantly Quality > around RF20の順でHandBrakeで設定する。圧縮率を設定したいなら、Quality Setting > Constantly Quality > around RF28の順でHandBrakeで設定する。出力画質の劣化を考えると、RFを32以下に設定したほうがおすすめ。



### 「HandBrake」と「VideoProc Converter AI」の比較

**◆ 変換画質** 

 **HandBrake：**ファイルサイズと画質のバランスを取ることが難しい。ファイル容量を軽くしようとすれば、画質が犠牲になる。逆に、画質の低下をできるだけ避けると、出力力ファイルサイズが大きすぎてしまう。

**VideoProc Converter AI：**高品質エンジン、・デインタレーシング、Force A/C synなどの技術をサポートするため、画質を劣化させずにやってくれる。ファイルサイズと画質のバランスがよく、ファイルサイズを抑えながらオリジナルの画質と違いがわからないほど綺麗に動画を出力できる。その他、AI動画高画質化/AIフレーム補間、AI手ぶれ補正機能も兼ね備え、変換したファイルの画質を4Kまで向上させることができる。 ![DVDをブルーレイにコピー](https://www.macxdvd.com/blog/img/smart-handbrake-high-quality-settings05.png)  

<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**◆ 解除可能なDVDコピーガード** 

 **HandBrake：**リージョン制限

**VideoProc Converter AI：**DVD CSS、リージョンコード、RCE、ソニーArccOS、UOPs、容量偽装、ディズニーX-projection DRM、99つタイトルのあるDVD、日本独自DVD、スポーツ・フィットネス/ワークアウト系DVD。 ![DVDをブルーレイにコピー](https://www.macxdvd.com/blog/img/smart-handbrake-high-quality-settings05.png)

<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
**優秀者：VideoProc Converter AI**

**◆ 出力プロファイル** 

 **HandBrake：**MKV、M4V、MP4

**VideoProc Converter AI：**VideoProc Converter AI：350＋種類の出力プロファイルを搭載して、DVDや動画をMP4、MOV、M4V、FLV、MOV、iTunes、Apple TV、MP3、AAC、AC3などに変換、iPhone 16/15/14/13/12、Galaxy S20/Galaxy Note20、Xperia Z1/Z2/Z3/Z4/Z5/XZ、iPad、Androidへ入れることができる。 ![DVDをブルーレイにコピー](https://www.macxdvd.com/blog/img/smart-handbrake-high-quality-settings05.png)

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633309&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/3_premium-icon.png" border="0"> Take advantage of PREMIUM features for 12 months. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Yearly Membership</a>
<!-- affiliate ads end -->
**優秀者：VideoProc Converter AI**

**◆ その他** 

VideoProc Converter AIはHandBrakeと同じ働きする様なソフトとして、HandBrakeより、豊富な機能を搭載している。例えば、1000以上種類のオンラインサイト、たとえば、ユーチューブダウンロードは勿論、ゲオ、ニコニコ動画、[bilibili（ビリビリ動画）](https://tools.techidaily.com/macxdvd/products/)、ヴィオ・ヴィデオ、デイリーモーション、パンドラティーヴィー、FC2動画、Youku、Pornhubから動画をダウンロードできる。

そして、カット、圧縮、リサイズ、フォーマット変換、クロッピング、[動画回転/反転](https://tools.techidaily.com/macxdvd/products/)、動画連結、字幕/ ログ追加、音声入れ替え、フレームレートの変更、音声抽出などの編集機能も備える。さらに、Mac版は録画機能を搭載しているため、Mac再生画面を無劣化で録画することも可能。



![](https://www.macxdvd.com/blog/../seoimage/videoproc.jpg) 

### HandBrake高画質設定が難しいから易しいやり方へ｜VideoProc Converter AI

この高画質Mac用DVD動画変換ソフトを使って、お気に入りのDVD＆動画を完全無劣化で変換して、Mac・PCパソコン、iPhone 16/15/14、iPad Pro、iPad Mini 4/3/2、iPad Air2、iPod、新型Apple TV/Apple TV、Android、HTC、Samsung、Xperia、ARROWS、Galaxy Tab、PSP、QuickTimeなどに取り込んで、再生できる。

[![](https://www.macxdvd.com/blog/new-fourteen/mac.png)](https://www.videoproc.com/download/videoproc-file.dmg)[![](https://www.macxdvd.com/blog/new-fourteen/winx.png)](https://www.videoproc.com/download/videoproc-file.exe)

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->


## あなたへのおすすめ

![](https://www.macxdvd.com/blog/img/drp-mj-20170508-01.jpg) 

[超簡単でTSUTAYAやゲオなどのレンタルDVDをコピーする方法！](https://tools.techidaily.com/macxdvd/products/)

![](https://www.macxdvd.com/blog/img/macos-10-13-ripper-01.jpg) 

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->
[【最新版】Mac DVDリッピングフリーソフト最新ランキング15選](https://tools.techidaily.com/macxdvd/products/)

![](https://www.macxdvd.com/blog/img/macos-10-13-ripper-02.jpg) 

[市販DVDをiPhone/iPad/Android/ゲーム機に取り込む方法](https://tools.techidaily.com/macxdvd/products/)

![](https://www.macxdvd.com/blog/img/imovie-video-to-dvd-0327.jpg) 

[iMovie DVD焼き方｜iMovieで編集した動画をDVDに焼く](https://tools.techidaily.com/macxdvd/products/)



[ホーム](https://tools.techidaily.com/macxdvd/products/)[Blog](https://tools.techidaily.com/macxdvd/products/) \>Handbrake高画質設定方法

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>


