# 2021gsc_Kahoru-Sato
2021年度 ゼミ論用レポジトリ

# 【2021年度ゼミ論】おたすけグラレコ（Glideを使用したゼミ生向けグラレコ補助アプリ）のアップデート
地球社会共生学部　地球社会共生学科　4年

学籍番号：1A118082 

氏名：佐藤かほる

指導教員：古橋 大地教授

© Kikuchi&Furuhashi Laboratory/KahoruSato, CC BY 4.0





## 概要
本研究は[川嶋彩香さんの研究](https://github.com/furuhashilab/2020gsc_AyakaKawashima) を参考に、川嶋さんが作成した、古橋研究室生（以下ゼミ生）向けグラフィックレコーディング補助アプリ「[おたすけグラレコ](https://spacial-harmony-4996.glideapp.io/)」（以下旧アプリ）　をアップデートした「[おたすけグラレコ　vol.2](https://otasukegrareco.glideapp.io/)」（以下本アプリ）の制作過程について説明する。本アプリの作成目的は、よりユーザーがグラフィックレコーディング時に衝突する障壁を無くすことである。研究課題は、以下の2点である。・旧アプリの課題を解決するため、ゼミ生と川嶋彩香さんにアンケート調査・聞き取り調査を行う。・調査の結果を踏まえ、アプリの利便性を高めるための改良を行う。調査によって明らかになった旧アプリの課題は、ゼミ生の求めている機能が無いことやアプリの認知度が低いことが挙げられた。対象者、アプリ開発ツールについては旧アプリと同一のものとする。対象環境について、旧アプリはアナログ式のグラレコのみが対象とされていたが、iPad等のタブレットを用いたデジタル式のグラフィックレコーディングの需要が増えているため、デジタルグラレコも対象とする。
 
 
***対象者***
- 既に所属しているグラレコ部以外のゼミ生
- 新しく古橋ゼミに入ってきたゼミ生
- グラレコをやってみようかなと思っている人


***対象環境***
- 人数：1人
- 方法：アナログ・デジタル
- グラレコ対象：オンライン会議やイベント、動画





## Introduction:
本研究では、グラレコに興味があるものの、その方法が分からず困っている人を対象に、グラレコ時に参考になるコンテンツをモバイルアプリケーション（以下アプリ）で提供することを目的としている。グラレコとは会議やワークショップ等の場にて、議論を絵や文字で可視化する手法のことである。グラレコをリアルタイムで行うことで、認識のすり合わせによる深い内容理解や、活発な議論を促すことが期待されている。実際、脳神経細胞の75％は視覚情報を処理するために使われており、視覚を使って物事を理解することは学習や円滑な協働に大きく役立つとされている（Brand 2017）。そのため、グラレコは多様なビジネスシーンで役立つコミュニケーション技術として、近年注目されている　（久保田　2020）。古橋研究室でも、数年前からグラレコを取り入れており、多くのゼミ生がイベントやミーティング時に実施している。しかし、新型コロナウィルスが流行して以降、ゼミ生が対面でグラレコの手法を学ぶ機会が減り、グラレコに対して苦手意識を持つ学生がいることが判明した（川嶋　2020）。そのため昨年川嶋彩香さんは、グラレコ時のおたすけツールとして、アプリ「おたすけグラレコ」を開発した。グラレコ初心者に有益なコンテンツを提供していると思われた旧アプリだが、ユーザーは増えなかったため、疑問に感じた。その原因を解明し、アプリをアップデートすることで、多くのゼミ生がグラレコに取り組みやすくなるのではないかと考えた。原因解明のため、ゼミ生にアンケート調査を、開発者である川嶋さんに聞き取り調査を行った。調査結果から、旧アプリはゼミ生が求めるコンテンツが不足していること、アプリ自体を知らない人がいることが判明した。そのため、「おたすけグラレコ」のUser　eXperienceを高め実際に使ってもらえる様、アプリのアップデートとアプリの周知を試みた。



## Methods:
まず、現状分析を行うために以下の二つの調査を行った。

### (1)ゼミ生を対象とするグラレコ/旧アプリについてのアンケート調査
***調査目的***
- グラレコに対する率直な気持ちを知ること
- ゼミ生がグラレコ時に困難に感じる点を明らかにすること
- 「おたすけグラレコ」に求めるコンテンツ/機能を明らかにすること。

ゼミ生がグラレコ時に困難に感じる点については旧アプリ制作時に判明していたこともあるが、今回はより詳細な情報を聞き出した。

***アンケート結果***
- https://docs.google.com/spreadsheets/d/12wZKnddUm3eTR7aqETrj6w9F-NqVCYk8GsYbUJiAJO8/edit?resourcekey#gid=1306717794






### (2)川嶋彩香さんへの聞き取り調査
***調査目的***
- 　Gliedとスプレッドシートの引き継ぎ
- 　旧アプリの課題の洗い出し

***課題***
- [How to’s] タブ内に画像を追加できず、SpeakerDeckとGoogleSlideのリンクを貼っていて使いづらい。
- [How to’s]　　アナログ式グラレコの方法しか記載していないためタブレットを使用した際のグラレコのコツがわからない。
- [Template]　　レイアウトの種類が少ない
- [Illustration]　タブ内のイラスト量が少ない。（古橋研究室では専門性が高いワードが頻出し、すぐにイラスト化出来ないため、イラストが豊富だと利便性があがる）




上記の調査から、①おたすけグラレコを使いやすくするためのアップデート、②おたすけグラレコを使ってもらうための施策　　を考案した。

***おたすけグラレコを使いやすくするためのアップデート***
- [How to’s]タブをスクロールして閲覧可能にした。(方法：imageタブを追加し、使用したい画像を差し込む。)
- [How to’s]デジタルグラレコのコンテンツを追加した。（方法：GoogleSlideにて作成したものをGlideに追加した。）
- [How to’s]デジタルグラレコを実際に行っている参考動画を追加した。（方法：iMovieにて作成したものをYoutubeに載せたURLをGlideに追加した。）
- [Template]　　レイアウトの種類を追加した。（方法：安田遥さんのNoteを参考にレイアウト参考画像を作成しGlideに追加した。）
- [Illustration]タブ内にイラスト・ロゴを追加した。（方法：ハッカソンで各サークルが作成したイラストを追加。）

 

***おたすけグラレコを使ってもらうための施策***
- URLを簡潔な文字列に変更した。(方法：Shareを押した際に出てくるデフォルトのURLを簡潔な文字列に差し替えた。)
- Glideを古橋研究室と共同編集可能に設定した。
- おたすけグラレコを使ってもらうイベントを開催する。(2022年2月22日予定)

開発には昨年同様、Googleスプレッドシートと連携してノーコードで簡単にアプリを作れるGlideを使用した。Glideで生成できるのは、プログレッシブウェブアプリ（以下PWA）と言われるスマホのアプリのように見えるウェブサイトのことでApple Storeでインストールする様なスマホアプリではなく、サファリなどのブラウザから使える形式である。



## Results:
作成したアプリ
　https://otasukegrareco.glideapp.io/

（旧アプリ：　https://sudden-coat-8413.glideapp.io/　）

Glideで使用したGoogleスプレッドシート　
　https://docs.google.com/spreadsheets/d/1nEciQ1ZPe-PdgLz0mjSW3Bh2bAXfg8WxUKetmNK7Q8s/edit?usp=sharing



## Discussion:
- 旧アプリのアップデートの必要性について

本研究を行う上で、旧アプリアップデートの必要性の有無は理解する必要があった。ゼミ生を対象に行った、グラレコについてのアンケート調査の結果を見ると、以下の回答が得られた。

***グラレコはやる意味があると思うか***
![alt](https://user-images.githubusercontent.com/64342648/152509534-86304f8d-4243-48e8-ac84-9de097ea685e.png)

***上記回答の理由***
![alt](https://user-images.githubusercontent.com/64342648/152509866-ef9595e1-2546-4ca4-9d54-52ed897b4c92.png)



***「おたすけグラレコ」を参考にしたいか***
![alt](https://user-images.githubusercontent.com/64342648/152510299-86734b4d-f593-4d6e-93cf-91dff015075e.png)

上記の結果から、ゼミ生はグラレコの

今回のアップデートにより、アプリの利便性が高まったと考える。今後使った人からのアンケートを集計し、アップデートの有効性を確かめていきたい。また、Glide、Googleスプレッドシートを共同編集可能にしたので、この研究が受け継がれていくことが期待される。



## Conclusion:
アプリを制作することで、コミュニティ内の知見の共有が可能になることを実感できたので、グラレコだけでなく、様々な分野においてアプリ開発をしてみたい。




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
