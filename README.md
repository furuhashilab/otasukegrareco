# Otasuke GraReco おたすけグラレコ 公式管理リポジトリ


以下は 佐藤かほるの卒論リポジトリのまま（適宜現役生が修正すること！）
---
佐藤かほる　2021年度ゼミ論用レポジトリ　ゼミ論

# おたすけグラレコ（Glideを使用したゼミ生向けグラレコ補助アプリ）のアップデート
地球社会共生学部　地球社会共生学科　4年

学籍番号：1A118082 

氏名：佐藤かほる

指導教員：菊池尚代教授・古橋大地教授

© Kikuchi&Furuhashi Laboratory/KahoruSato, CC BY 4.0





## 概要
本研究は[川嶋彩香さんの研究](https://github.com/furuhashilab/2020gsc_AyakaKawashima)を参考に、川嶋さんが作成した、古橋研究室生（以下ゼミ生）向けグラフィックレコーディング補助アプリ「[おたすけグラレコ](https://spacial-harmony-4996.glideapp.io/)」（以下旧アプリ）をアップデートした「[おたすけグラレコ　vol.2](https://otasukegrareco.glideapp.io/)」（以下本アプリ）の制作過程について説明する。本アプリの作成目的は、ユーザーがグラフィックレコーディング時（以下グラレコ）に衝突する障壁を無くすことである。研究課題は、以下の2点だ。・旧アプリの課題を解決するため、ゼミ生と川嶋彩香さんにアンケート調査・聞き取り調査を行う。・調査の結果を踏まえ、アプリの実用性を高めるための改良を行う。アプリ制作ツールは従来同様、Glideを使用した。調査によって明らかになった旧アプリの課題は、ゼミ生の求めている機能が無いことやアプリの認知度が低いこと等が挙げられた。そこで、より実用的なアプリにするためのアップデートと、アプリを使ってもらうための施策を行った。
 

***対象者***
- 既に所属しているグラレコ部以外のゼミ生
- 新しく古橋ゼミに入ってきたゼミ生
- グラレコをやってみようかなと思っている人

***対象環境***
- 人数：1人
- 方法：アナログ・デジタル
-　グラレコ対象：オンライン会議やイベント、動画
 
 
対象者は旧アプリと同一、対象環境について、旧アプリはアナログ方法のグラレコのみが対象とされていたが、iPad等のタブレットを用いたグラフィックレコーディングの需要が増えているため、デジタル方法のグラレコも対象とする。



## Introduction:
本研究は、ゼミ生・グラレコ初心者を対象とした、グラレコ時のお役立ちアプリである「おたすけグラレコ」をアップデートしたアプリ作成を目的としている。アプリの制作目的は、グラレコ初心者やグラレコに苦手意識がある人が感じる困りごとをグラレコの基礎を学べるコンテンツなどを提供することで解消し、グラレコ上級者にはグラレコやイラストなどをまとめる場所を提供することだ。　　グラレコとは会議やワークショップ等の場にて、議論を絵や文字で可視化する手法のことである。グラレコをリアルタイムで行うことで、認識のすり合わせによる深い内容理解や、活発な議論を促すことが期待されている。実際、脳神経細胞の75％は視覚情報を処理するために使われており、視覚を使って物事を理解することは学習や円滑な協働に大きく役立つとされている（Brand 2017）。そのため、グラレコは多様なビジネスシーンで役立つコミュニケーション技術として、近年注目されている　（久保田　2020）。古橋研究室でも、数年前からグラレコを取り入れており、多くのゼミ生がイベントやミーティング時に実施している。しかし、新型コロナウィルスが流行して以降、ゼミ生が対面でグラレコの手法を学ぶ機会が減り、グラレコに対して苦手意識を持つ学生がいることが判明した（川嶋　2020）。そのため昨年川嶋さんは、グラレコ時のおたすけツールとして、アプリ「おたすけグラレコ」を開発した。グラレコ初心者にも上級者にも有益なコンテンツを提供していると思われた旧アプリだが、ユーザーが増えなかったことを疑問に感じた。その原因を解明し、アプリをアップデートすることができれば、多くのゼミ生がグラレコに取り組みやすくなるのではないかと考えた。研究目的のために、ゼミ生にアンケート調査を、開発者である川嶋さんに聞き取り調査を行い旧アプリの課題を解明した。調査結果から、旧アプリはゼミ生が求めるコンテンツが不足していること、アプリ自体を知らない人がいることが判明した。そのため、次段階として、より実用的なアプリにするためのアップデートと、アプリを使ってもらうための施策を試みた。結果として「おたすけグラレコ v2」が制作され、多方面から改良がなされた。

## Methods:
まず、現状分析を行うために以下の二つの調査を行った。

### (1)ゼミ生を対象とするグラレコ/旧アプリについてのアンケート調査
***調査目的***
- なぜ旧アプリを使わないのかを明らかにすること。
- 「おたすけグラレコ v2」に求めるコンテンツ/機能を明らかにすること。等。

***アンケート結果***
- https://docs.google.com/forms/d/1MIX_xy2ThEiSJAeikNelf3fnZU9Qm4VrFbodpwS9tPk/edit#responses

アンケートに回答したゼミ生全員が旧アプリを使ったことがなかった。その理由は、アプリの存在が3年生に知られていない、使い方・リンクが不明、使う機会がない等だった。本アプリを使ってもらわない限り、研究目的は達成されないため、アプリを使ってもらうための施策を立てる必要があると考える。また、旧アプリにはなく、本アプリに求めるコンテンツや機能は数多くあることが判明した。


### (2)川嶋彩香さんへの聞き取り調査
***調査目的***
- 　各種引き継ぎ
- 　旧アプリの修正希望点の洗い出し

***旧アプリの課題***
- [How to’s] タブ内に画像を追加できず、SpeakerDeckとGoogleSlideのリンクを貼っていて使いづらい。
- [How to’s]　　アナログ式グラレコの方法しか記載していないためタブレットを使用した際のグラレコのコツがわからない。
- [Template]　　レイアウトの種類が少ない
- [Illustration]　タブ内のイラスト量が少ない。（古橋研究室では専門性が高いワードが頻出し、すぐにイラスト化出来ないため、イラストが豊富だと利便性が上る）




上記2つの調査から、①より実用的なアプリにするためのアップデート、②アプリを使ってもらうための施策　を考案した。



### ①実用的なアプリにするためのアップデート

開発には昨年同様、Googleスプレッドシートと連携してノーコードで簡単にアプリを作れるGlideを使用した。Glideで生成できるのは、プログレッシブウェブアプリ（以下PWA）と言われるスマホのアプリのように見えるウェブサイトのことでApple Storeでインストールする様なスマホアプリではなく、サファリなどのブラウザから使える形式である。


***具体的なアップデート箇所と、その手法***

|タブ| 旧アプリの課題・希望コンテンツ　| 本アプリ | 方法 | 発案者 |
|:---|:---|:---:|---:|---:|
|Grareco How to's|詳しい内容がスライドURLを開かないと見れない。|縦スクロールで閲覧可能|SCREENにimageを追加し、該当画像を差し込む。（スライドURLは削除）|川嶋・佐藤|
|Grareco How to's|アナロググラレコの手法のみ記載|デジタルグラレコのコンテンツ追加|GoogleSlideにて作成したデータを追加する。|佐藤|
|Grareco How to's|グラレコを描いてる動画を見たい。|デジタルグラレコの作成動画追加|iMovieで作成した動画をYoutubeにアップ、動画URLを追加する。|ゼミ生|
|Template|レイアウトの種類が少ない|レイアウト種類の追加|安田遥さんのNoteを参考に、レイアウト参考画像を作成・追加した。|川嶋|
|Template|議題テーマやシーンに合わせたテンプレートやイラストの提案|場面に応じたレイアウト例の追加|レイアウトのカテゴリーを追加、推奨場面を記入|ゼミ生|
|Illustration|イラストが少ない。|イラスト・ロゴの追加|ハッカソンで各サークルが作成したイラストを追加|川嶋・佐藤|
|Portfolio|参考になる上手な人のグラレコのおすすめとか関連作品・サイトに飛びたい。|元グラレコ部の作品を例として追加した。|作品を探し、画像を追加。|ゼミ生|
|Portfolio|タブMy Grarecoの称変更|Portfolioに（作品を載せていることから、こちらが相応しいと考えた。）|タブの書き換え|佐藤|
|Portfolio|作品が見つけにくい|カテゴリー、タイトルの表示、スタイルの変更|portfolio→style→orientationを横スライドに変更|佐藤|


### ②アプリを使ってもらうための施策

***具体的な施策と、目的***

| 施策 | 目的 | 方法・メモ　　|
|:---|:---:|---:|
|URLを簡潔な文字列に変更した。（https://spacial-harmony-4996.glideapp.io/　→　https://otasukegrareco.glideapp.io/）　|覚えやすさ、伝えやすさが増し、アプリ認知を広げる為|Shareを押した際に出てくるデフォルトのURLを簡潔な文字列に差し替えた|
|諸々古橋研究室と共同編集可能に設定した。 |引き継ぎしやすくして、後代のゼミ生にも使ってもらう為|Glideの設定、スプレッドシートの共有|
|おたすけグラレコを使ってもらうイベントを開催する。|使い方・使う機会をレクチャーし、今後グラレコ時に役立ててもらう為|2022年2月22日予定（新型コロナウィルス感染拡大防止のため要検討）|



## Results:

#### 作成アプリQR


![alt](https://user-images.githubusercontent.com/64342648/152600439-372f9fbf-ef1d-463d-b99e-89726b875bc7.png)

#### 作成アプリURL

https://otasukegrareco.glideapp.io/

旧アプリ(比較用)：　https://sudden-coat-8413.glideapp.io/　

Glideで使用したGoogleスプレッドシート　

　https://docs.google.com/spreadsheets/d/1nEciQ1ZPe-PdgLz0mjSW3Bh2bAXfg8WxUKetmNK7Q8s/edit?usp=sharing

おたすけグラレコアップデート案チェックリスト

https://docs.google.com/spreadsheets/d/18RzXA4Qs6SVixVelMbscuK5wl3mIm102_mScq61PtO4/edit?usp=sharing


## Discussion:

### 「おたすけグラレコ　 v2」について
2つの調査で希望された機能を多数追加し、アプリのアップデートが行われた。また、アプリを使ってもらうための施策が行われた。
本研究の一連の過程で、AIDMAというモデルを使って購買決定プロセスを説明できると考えた。

| 段階 | 本アプリで言うと |
----|---- 
| Attention  | 中間発表・最終発表でアプリの存在を知る。 |
| Interest | アプリに興味を持つ。 |
| Desire | 新機能を知り欲しいと思うようになる。 |
| Memory | 覚えやすいURLも合間ってが記憶される。 |
| Action | インストールする |


このような理想的な購買決定プロセスを経るか否かは解明されていないため、今後の課題としたい。
また、追加したかったが、未だ実行できていない機能もあるので、今後の課題としたい（チェックリスト参照）。





### - 旧アプリのアップデートの必要性について

本研究を行う上で、グラレコ時の補助はアプリ「おたすけグラレコ」が本当に適切なツールなのか、そして旧アプリアップデートの必要性の有無を理解する必要があった。ゼミ生を対象に行った、グラレコについてのアンケート調査の結果を見ると、以下の回答が得られた。

***グラレコはやる意味があると思うか***
***
![alt](https://user-images.githubusercontent.com/64342648/152509534-86304f8d-4243-48e8-ac84-9de097ea685e.png)

***上記回答の理由***
***
![alt](https://user-images.githubusercontent.com/64342648/152509866-ef9595e1-2546-4ca4-9d54-52ed897b4c92.png)



***「おたすけグラレコ」を参考にしたいか***
***
![alt](https://user-images.githubusercontent.com/64342648/152510299-86734b4d-f593-4d6e-93cf-91dff015075e.png)




  上記の結果から、ゼミ生はグラレコの有用性を理解しており、グラレコ補助アプリを参考にしたいと考えていることが明らかになった。
  また、旧アプリの課題点も回答していることを踏まえると、旧アプリアップデートの必要性は有ると推測できる。
  しかし、アプリ制作という手段が本当にゼミ生に役立つのかは現在もなお不明であるため、今後の課題としたい。
  
   
   
今回のアップデートにより、アプリの利便性が高まったと考える。今後使った人からのアンケートを集計し、アップデートの有効性を確かめていきたい。また、Glide、Googleスプレッドシートを共同編集可能にしたので、この研究が受け継がれていくことが期待される。



## Conclusion:
本アプリを制作する過程で、「おたすけグラレコ」がゼミ生にとって需要のあるアプリであることが認められた。また、アプリコンテンツに関して多くのアイディアが出るほど、開発の余地があることも判明した。「おたすけグラレコ v2」ではゼミ生の意見を取り入れ、複数のアップデートがされたため、少しでもグラレコ難民の快適なグラレコライフに貢献出来たと考える。
次に引き継ぐべき課題はイベントの実施・①機能のアップデートが役立ち、グラレコ難民を救えたか②使ってもらうための施策によって、ユーザーが増えたかの検証だ。
この研究を通じて、グラレコに関する新たな知見を得れただけではなく、ノーコードでアプリを制作するノウハウが身に付いた。また、アプリ内のコンテンツを増やしていく上で、グラレコスキルが上がり、さらに動画制作まで経験することができたので、個人としても多方面で学びを深める機会となった。






## Reference/参考文献:
https://docs.google.com/spreadsheets/d/1l70O47JlMSO01KnH_sPY8IhMeBc9VzU7UZTzvXHGk74/edit#gid=0

## Acknowledgements/謝辞:
本研究を進めるにあたり地球社会共生学部の菊池尚代教授、古橋大地教授をはじめ多くの方々より多大な助言を賜りました。厚く感謝を申し上げます。


本論文で記載されている登録商標・商標をはじめ、会社名、システム名、製品名は一般に各社の登録商標または商標です。なお、本文および図表中では、「™」、「®」は明記しておりません。



## 資料
**2020年度ゼミ論本文**  
https://docs.google.com/document/d/15ezuXFtbp9k-WkyxLEopBYkaFAwaP_gebzmIw1RAzQM/edit?usp=sharing


**進捗管理用プロジェクト**  
https://github.com/furuhashilab/2021gsc_Kahoru-Sato/projects/2


**最終プレゼン資料**  
https://docs.google.com/document/d/15ezuXFtbp9k-WkyxLEopBYkaFAwaP_gebzmIw1RAzQM/edit?usp=sharing   


**参考文献リスト**   
https://docs.google.com/spreadsheets/d/1l70O47JlMSO01KnH_sPY8IhMeBc9VzU7UZTzvXHGk74/edit?usp=sharing


**作成アプリ**  
https://otasukegrareco.glideapp.io/


**作成動画**
https://youtu.be/nXEop9_5kc0


**ゼミ生向けグラレコに関するアンケート回答**  
https://docs.google.com/spreadsheets/d/12wZKnddUm3eTR7aqETrj6w9F-NqVCYk8GsYbUJiAJO8/edit?resourcekey#gid=1306717794
