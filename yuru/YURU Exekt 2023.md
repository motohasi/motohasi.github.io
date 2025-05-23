# 1. 知を働かせるために：ゆる知働化

2023年7月7日  
本橋正成


- [1. 知を働かせるために：ゆる知働化](#1-知を働かせるためにゆる知働化)
	- [1.1. エピソード：共存のジレンマ 問題解決の迷走](#11-エピソード共存のジレンマ-問題解決の迷走)
	- [1.2. 知働化が必要な時代背景](#12-知働化が必要な時代背景)
	- [1.3. 知働研のチャレンジと影響要因](#13-知働研のチャレンジと影響要因)
	- [1.4. 知働化アプローチ](#14-知働化アプローチ)
		- [1.4.1. 知働化1＝実行可能知識@IT](#141-知働化1実行可能知識it)
		- [1.4.2. 知働化1＝実行可能知識](#142-知働化1実行可能知識)
		- [1.4.3. 知働化2＝表現](#143-知働化2表現)
		- [1.4.4. 知働化3＝創造](#144-知働化3創造)
		- [1.4.5. 知働化5＝学習](#145-知働化5学習)
		- [1.4.6. 知働化5＝対話](#146-知働化5対話)
		- [1.4.7. 知働化6＝自律](#147-知働化6自律)
		- [1.4.8. 知働化7＝気付き](#148-知働化7気付き)
	- [1.5. 知働化を飛躍させる ゆる](#15-知働化を飛躍させる-ゆる)
	- [1.6. 知働化による新しい世界](#16-知働化による新しい世界)


<div class="page"/>

## 1.1. エピソード：共存のジレンマ 問題解決の迷走

2023年に、長野市で1軒の住民からの騒音への苦情が公園の廃止につながるニュースを知りました。近隣住民の1世帯が子どもの遊ぶ声がうるさいと訴え、市はその苦情を受けて公園の閉鎖を決定しました。このニュースは大きな波紋を広げ、賛否両論の意見が出されました。

> 長野市は1軒の住民からの騒音への訴えをきっかけに、公園の廃止を決めました。　
> https://www.nhk.or.jp/politics/articles/feature/94042.html

> 「子どもの遊ぶ声がうるさい」。近隣住民1世帯の苦情に端を発し、長野市が「公園」の閉鎖を決めたことが波紋を広げている。市側は地元の意見も踏まえた総合的な判断で「1世帯の意見に流されたわけではない」と釈明するが、子どもが自由に遊べる場を奪うとの見方から、批判の声が殺到。一方で「私たちの苦しみも知ってほしい」と訴える抗議した男性に同情の声も上がる。
> https://sukusuku.tokyo-np.co.jp/hoiku/64235/

一方で、私の住んでいる地域でも同様の問題が存在します。道路で小さな子どもたちが端っこを歩いていると、自転車に乗った近隣のお年寄りから「危ない」と激しい怒声が聞こえます。また、近所の公園ではボール遊びや大きな声を出すことが禁止され、代わりにタバコを吸うお年寄りたちが集まっています。

このような問題は、明確な解決策がなく、どちらの立場にも理解できる主張が存在します。子どもたちが自由に遊ぶことができる環境と、住民の静寂な生活環境の両立は容易ではありません。双方の要求や権利が衝突し、解決が困難なまま平行線になっている現状です。

このエピソードは、知働化による問題解決が必要なケースを示しています。問題が表面化するだけでなく、問題の本質を理解し、異なるステークホルダーの意見や利益を考慮することが重要です。知の働きを通じて、双方の立場や価値観に気付きを得ることが求められます。


<div class="page"/>

## 1.2. 知働化が必要な時代背景

情報革命とは、コンピュータ技術と通信技術の進化によって引き起こされた大規模な社会変革です。情報の収集、処理、伝達がデジタル化され、インターネットやモバイル通信などの技術が普及したことにより、情報のアクセス性や共有性が劇的に向上しました。

現在は、VUCAの時代と言われています：

1. 不確実性（Volatility）:
   - 環境が急速に変化すること
   - 予測が難しくなること
   - 予期せぬ出来事や変動が頻繁に起こること

2. 複雑性（Complexity）:
   - 要素や関係が多数存在すること
   - 相互依存関係が複雑に絡み合うこと
   - 問題の理解と解決が難しくなること

3. 曖昧さ（Ambiguity）:
   - 情報や要件が不明確であること
   - 複数の解釈があり、一意に定まらないこと
   - 期待や要求のズレが生じること

4. 急速な変化（Uncertainty）:
   - 技術や市場の進化が速いこと
   - 既存のベストプラクティスが陳腐化すること
   - 新たな要求や制約が出現すること

VUCAを伴って、ソフトウェアエンジニアリングの本質的な困難 [^NoSilverBullet] を解釈してみました。

[^NoSilverBullet]: 『人月の神話 狼人間を撃つ銀の弾はない (20周年記念増訂版、新装版)』ピアソン・エデュケーション、2002年, ISBN 978-4-89471-665-0.

1. **不確実性（Volatility）:** ソフトウェアエンジニアリングは、技術やビジネス環境の急速な変化によって不確実性が高まっています。新しいフレームワークやプログラミング言語の登場、セキュリティ上の脅威、ビジネス要件の変更などがソフトウェア開発プロジェクトに影響を与える可能性があります。

2. **複雑性（Complexity）:** ソフトウェアシステムは通常、多くの要素の相互作用から構成されます。これにより、システム全体の複雑性が増し、設計や実装、テストの難度が上がります。さらに、ソフトウェアが大規模になるほど、相互依存関係や非線形性が増し、複雑性が一層高まります。

3. **曖昧さ（Ambiguity）:** ソフトウェアの要求や仕様はしばしば曖昧で不明確なままです。ユーザーの要求が不十分であったり、異なるステークホルダー間での意見の食い違いがある場合、開発者は曖昧さを解消するために追加の努力を必要とします。曖昧な要求や仕様は、設計や実装の段階で問題を引き起こす可能性があります。

4. **急速な変化（Uncertainty）:** ソフトウェア開発は常に変化し続けています。新しい技術やツールが登場し、既存のベストプラクティスやアプローチが陳腐化することがあります。開発者は新しい技術を学び、迅速に変化に対応する必要があります。この急速な変化によって、開発プロセスの不確実性が高まります。


これらの要素に対処するためには、柔軟性、アジリティ、学習能力、チームワーク、効果的なコミュニケーションなどが重要となります。本質的な困難に直面していたソフトウェア開発者たちは、アジャイル開発宣言 [^agilemanifesto] を提唱することによって、困難に対処できる可能性を模索しているのではないでしょうか。

[^agilemanifesto]: https://agilemanifesto.org/iso/ja/manifesto.html

本質的困難を埋め込んだアジャイル開発宣言です

> ソフトウェアエンジニアリングが持つ**本質的な困難**を攻略するため、*よりよい開発方法を見つけだそうとしている。*
>
> - **不可視性：** 重なり合っている複数の一般的な有向グラフで構成された概念構造体は、空間に埋め込めず見ることはできないため、*プロセスやツールよりも個人と対話に価値を置く。*
> - **同調性：** インターフェースを人間の慣習や社会制度との順応（顧客から見た品質）を調べるため、*包括的なドキュメントよりも動くソフトウェアに価値を置く。*
> - **複雑性：** 本質的に複雑なソフトウェアに対して、相互のコミュニケーションを通じて攻略するため、*契約交渉よりも顧客との協調に価値を置く。*
> - **可変性：** 慣習や媒体といった変化する文化的マトリックスに はめ込められているため、*計画に従うことよりも変化への対応に価値を置く。*
>
> [銀の弾とアジャイルについてのメモ (Agile is a Silver Bullet) - ari's world https://motohasi.hatenablog.com/entry/2018/11/02/210615](https://motohasi.hatenablog.com/entry/2018/11/02/210615)


本質的な困難とアジャイル開発宣言の親和性は高いです。本質的な困難への問題意識が、アジャイル開発宣言の要因のひとつになったとの考えは受け入れられます。アジャイル開発は、ソフトウェア開発の困難に対処するための柔軟で迅速なアプローチとして、現代のソフトウェア開発プロセスにおいて重要な位置を占めています。アジャイル開発宣言は、ソフトウェアエンジニアリングにおける提案とは言え、それ以外の領域に対しても有効であることが経験的にわかってきました。

しかしながら、アジャイル開発の「次」は何か、ITに限らず一般的な社会制度や経済、哲学や文化など強く関係している事柄についての探究は十分になされていません。


<div class="page"/>

## 1.3. 知働研のチャレンジと影響要因

**次世代のエンジニアリングやサービス、組織やビジネス、文化や哲学に至るまで幅広く深い問題意識を持って議論する必要があります。**

研究誌や缶詰会、イベントを通じて、以下のような事柄について幅広く研究してきました。

1. **哲学や思想の研究:** 知働化研究室では、哲学や思想に関する研究を行ってきました。これにより、人間の知識や意識のあり方、人間の目的や価値観について深く考察し、知識労働者としてのエンジニアの役割や存在意義を探求してきました。

2. **デザインやイノベーションに関する研究:** 知働化研究室は、デザイン思考やイノベーションに関する研究も行ってきました。これにより、新たなアイデアや解決策の創出方法、創造性の促進、ユーザーエクスペリエンスの向上などに焦点を当てました。

3. **システムや科学に関する探究:** 知働化研究室では、システム思考や科学的なアプローチによる研究も行ってきました。システムの相互作用や複雑性を理解し、継続的な学習や改善を促進する方法を探求してきました。

4. **組織や人に関する研究:** 知働化研究室は、組織や人に関する研究も行ってきました。組織の文化や風土、チームの動態、リーダーシップの役割などを分析し、知識労働者の働き方や生産性の向上につながるような環境を模索してきました。

5. **社会や文化に関する研究:** 知働化研究室では、社会や文化に関する研究も行ってきました。社会の変化やトレンド、文化の影響などを考慮し、知識労働者としてのエンジニアの役割が社会や文化にどのように関連しているかを探求してきました。

6. **問題解決法の整理や探究:** 知働化研究室では、問題解決法に関する研究も行ってきました。既存の問題解決手法やアプローチの整理や比較、新たな手法やアイデアの発見などを行い、問題解決法がそのものが持つ問題についても議論してきました。 [^YURU_AsianPLoP2014]

7. **政治や経済に関する研究:** 知働化研究室では、政治や経済に関する研究も行ってきました。政治的な制度や経済的な仕組み、規制環境などについて分析し、独裁性や民主主義、経済と、エンジニアを含む組織について研究と実践してきました。

[^YURU_AsianPLoP2014]: Masanari MOTOHASI, 2014, ゆる思考 問題の問題に対する挑戦, AsianPLoP 2014, https://hillside.net/asianplop/proceedings/AsianPLoP2014/papers/20.pdf

以上の要因について、知働化研究室ではそれぞれの研究を通じて、エンジニアリングやサービス、組織やビジネス、文化や哲学などの幅広い領域における課題に向き合っています。これにより、より持続可能な社会や経営を築くための知識と洞察を提供することを目指しています。

どのような要因も「知が働く」ことが共通となってきます。そこで著者・本橋は、自転車に乗っているときに思いつき「知働化」を名付け、皆様に受け入れていただきました [^exekt-lab]。

[^exekt-lab]: http://www.exekt-lab.org

研究会では、幅広い領域について深く議論していきます。参加者も、それぞれの想いを持ち独立して議論しています。しかし「知働化」そのものについての共通認識は十分ではありません。







<div class="page"/>

## 1.4. 知働化アプローチ

**知働化研究会において幅広く議論がなされてきました。しかし、より社会に受け入れられていくために、この「知働化」そのものについて語りたいです。**

現時点で著者が考える知働化の定義を紹介します。

|  知働化 |       定義       | 内容         | 適応分野                   |
| ------: | :--------------: | :----------- | -------------------------- |
| 知働化1 | **実行可能知識** | *ゆるコード* | IT、法、パターンランゲージ |
| 知働化2 |     **表現**     | *ゆる思考*   | モデル、情報転送           |
| 知働化3 |     **創造**     | *ゆる制約*   | 設計、アート、デザイン     |
| 知働化4 |     **学習**     | *ゆる反応*   | モデル化、システム         |
| 知働化5 |     **対話**     | *ゆる状況*   | 教育、現場、ワークショップ |
| 知働化6 |     **自律**     | *ゆる支配*   | 政治、チーム、民主化       |
| 知働化7 |    **気付き**    | *ゆる日常*   | 人生、生き方               |


<div class="page"/>

### 1.4.1. 知働化1＝実行可能知識@IT

コロナ禍で休校になり毎日のように家族でお昼を食べている時期がありました。
最初は楽しみだったものの毎日続くと、その選択に悩むようになりました。

子どもたちとのランチを元に 子どもと書いたPythonのプログラムです。

``` python
import random
our_lunches = [
	'そば・うどんを茹でる、お餅を焼く',
	'インスタントラーメンを食べる',
	'シリアルやグラノーラを食べる',
	'残りものを食べる、残り物がなかったら、もう一度、実行する',
	'コンビニやスーパーへ買いに行く',
	'マクドナルドへ買いに行く',
	'何を食べるか話し合って決める'
]
print('今日は'+random.choice(our_lunches))
```

このプログラムを実行すると

> 今日はインスタントラーメンを食べる

とその日の料理を教えてくれます。
知識が実行された、とも解釈できます。

知識の記述やメモだけでは、その知識が実際の行動に影響を与えることはできません。知識を実され、それが働くことが重要です。このプログラムの例では、食事の選択肢をリストとして定義し、ランダムに選択することで実際の行動を決定しています。

このような知識を具体化するプログラムや行動の中で、知識行為が行われます。知識行為は、知識や情報を活用し、問題解決や意思決定などの課題に取り組む活動です。具体的な行動を通じて知識が活用されることで、知識行為が実現されます。

「知働化」とは、知識を具体的な行動や労働に結び付けるプロセスやアプローチを指します。具体的なプログラムの例は、知識が実行可能な形に変換され、行動に反映されることが「知働化」の一つの側面です。


<div class="page"/>

### 1.4.2. 知働化1＝実行可能知識

コンピュータ・マシンが解釈できるコードである実行可能知識をさらに一般化してみましょう。

実行可能知識は、コンピュータが解釈できるコードだけでなく、法律や曼荼羅、パターンランゲージなど、さまざまな形式の知識を含みます。これらは単なる記述や図像ではなく、実際のシステムや人々の行動の中で活用され、影響を与えます。

> （安全運転の義務）
> 第七十条　車両等の運転者は、当該車両等のハンドル、ブレーキその他の装置を確実に操作し、かつ、道路、交通及び当該車両等の状況に応じ、他人に危害を及ぼさないような速度と方法で運転しなければならない。  
> 道路交通法

法律の例を見てみましょう。道路交通法の第七十条は、運転者が車両を確実に操作し、他人に危害を及ぼさないような速度と方法で運転しなければならないことを定めています。この法律は単なる文字の列ですが、実際の道路や標識、警察、運転者などのシステムの中で運用され、安全な交通環境を実現するための実行可能な知識として機能しています。

![胎蔵界 via https://en.wikipedia.org/wiki/Mandala](../_resources/Taizokai-8.jpg)

同様に、曼荼羅も単なる色の濃淡の模様ですが、そのテクスチャーを読み取り、知識が働き、心に影響を与えます。曼荼羅は宗教的な象徴や思想を表現する手法であり、観る人の心を静めたり、瞑想を促したりする役割を果たします。これは単なる図像だけではなく、知識として働き、人々の内面に深い影響を与える実行可能な知識です。

このような法律や曼荼羅などの知識は、単なる記述や図像の域を超えており、実際のシステムや人々の行動の中で働きます。実行可能知識として活用されることで、社会や文化、個人の行動や認識に影響を与え、知識労働の一環として働いています。知識の持つ力と影響力を理解し、実践することが知働化の範疇に含まれます。

<div class="page"/>

### 1.4.3. 知働化2＝表現

知働化における実行可能知識は、記述と実行の双方の要素を含んでいます。記述は、法律やプログラムなどのコードとすること、実行はその環境への作用です。「知働化」の「化」は、変化を意味しています。

知識や思いを表現し、実際の行動や具体的な記述に変えていくプロセスも、知働化と呼ぶことができます。例えば、デザインやアート、小説や論文の執筆など、継続的に表現を行う活動は「知働化」の一環です。これらの活動では、アイデアや感情、情報などが言葉や絵画、音楽、デザイン、表現の形式を通じて具現化されます。それによって、知識や思考が他の人と共有されたり、影響を与えたりすることが可能となります。

表現を通じた知働化は、個人や社会に対して多くの価値をもたらします。表現活動は新たなアイデアや視点を生み出し、問題解決やイノベーションの源となることがあります。また、文化や芸術の領域での表現は、感情や思考の共有、社会的なつながりの形成、個人や集団のアイデンティティの形成に寄与します。

知識や思考を表現することは、個人の内面の世界を外部に示すだけでなく、相互作用や共有の場を創り出すことでもあります。表現活動は、言葉や記号、メディアを通じてアイデアや知識を形にし、他の人々との対話やコミュニケーションを促進します。これにより、知識や思考が進化し、さらなる創造性や洞察を生み出すことができるのです。

知働化の一環としての表現活動は、人々が持つ知識や思考を形にし、共有し、より豊かな人間のつながりと成長を促進します。表現を通じて、個人の内面や共有された知識が社会的な影響を持つことができるのです。


<div class="page"/>

### 1.4.4. 知働化3＝創造

知働化には、さまざまな表現の形態が存在します。例えば、文章を写経するように既存の表現を再現する場合や、仕様書に基づいてプログラムを作成する場合など、既存の知識を実行することも知働化の一形態です。しかし、このような場合には知識の働き方が記述の範囲に収まり、限定的になることがあります。

そこで、知働化の一環として、特に創造的な行為も強調されます。創造的な活動では、設計やアート、デザイン、執筆など、与えられた状況を読み取り、言語や制約の中で新しいものを創造していくことを指します。これは、周囲の状況や文脈を観察し、既存の知識や素材を組み合わせ、新たなアイデアや表現を生み出すプロセスです。

創造的な知働化によって、特定の状況や目的に適した妥当な表現が継続的に生まれます。創造行為には、状況や制約を理解し、自由な発想やアイデアを組み合わせる能力が求められます。これによって、新しい視点や解決策が発見され、既存の知識やアイデアの進化や拡張が可能となります。

創造的な知働化は、個人や組織の成長やイノベーションに重要な役割を果たします。創造行為は新たな表現やアート作品、デザイン、コンテンツの創造につながるだけでなく、問題解決や新たな価値の創出にも寄与します。創造的な知働化によって、新たなアイデアや表現が持続的に生み出され、知識の範疇が広がっていくのです。


<div class="page"/>

### 1.4.5. 知働化5＝学習

前のセクションで説明したように、実行可能知識の創造的表現や実行によって知の働きが生じます。知の働きそのものの変化は、学習と呼ばれます。

学習には、ベイトソンによる学習定義のレベル0から4までの定義が存在します。これらの定義は、知働化の概念と密接に関連しており、それぞれが知の働きの変化を表現しています。

> - ゼロ学習の特徴は、反応が一つに定まっている点にある。その特定された反応は、正しかろうと間違っていようと、動かすことのできないものである。
> - 学習Ⅰとは、反応が一つに定まる定まり方の変化、すなわちはじめの反応に代わる反応が、所定の選択肢群から選びとられる変化である。
> - 学習Ⅱとは、学習Iの進行過程上の変化である。選択肢群そのものが修正される変化や、経験の連続体が区切られる、その区切り方の変化がこれにあたる。
> - 学習Ⅲとは、学習IIの進行過程上の変化である。代替可能な選択肢群がなすシステムそのものが修正されるたぐいの変化である。
> - 学習Ⅳとは、学習Ⅲに生じる変化、ということになろうが、地球上に生きる（成体の）有機体が、このレベルの変化に行きつくことはないと思われる。ただ、進化の過程は、個体発生のなかでⅢのレベルに到達するような有機体を生み出しているわけであるから、そのような個体発生上の変化を変化させる系統発生上の変化は、事実Ⅳのレベルに踏み込んでいると言える。
>
> エンゲストローム, 山住勝広ほか訳『拡張による学習』, pp163-164

学習における効果的な進め方や方法については、出版されている多くの専門書に譲りここでは詳しく触れません。環境からの影響を受けて人やマシンが学習し、そして人やマシンが環境に影響を与えるという相補的な関係が存在しています。学習は、知識や経験の蓄積、新たな情報の取り入れ、適応や成長のプロセスとして、個人や社会の発展に重要な要素です。


<div class="page"/>

### 1.4.6. 知働化5＝対話

実行可能知識を記述し、表現し、創造し、学習するためには、多くの情報や状況を理解することが重要です。この情報の入力と出力のための一つの形式として、対話が存在します。

対話は、相互のコミュニケーションや意思疎通を通じて情報を交換し、意見や知識を共有するプロセスと一般的に定義されています。知働化における対話は、個人同士や集団の間で行われ、相互作用と相互影響が生じます。対話には言語やコミュニケーションの手段が利用され、情報や意味が共有されます。

非対話的な場合、個人が独自の知識や経験に頼って問題に取り組むことがあります。この場合、他の人々の視点や情報を取り入れることが制限され、新たなアイデアや洞察を得る機会が制約される可能性があります。また、個人の認識や解釈によるバイアスや限定的な視野が生じることもあります。

知働化における対話によるアウトカムです：

1. **共同の理解:** 対話によって異なる視点や情報が共有されることで、参加者間での共同の理解が生まれます。個人の知識や経験の幅が広がり、より包括的な視野が得られます。

2. **新たなアイデアや洞察:** 対話によって意見や知識が交換されることで、新たなアイデアや洞察が生まれることがあります。異なる視点や経験からの情報が組み合わさり、創造的な解決策やアプローチが生まれる可能性があります。

3. **協力と協働:** 対話によってコミュニケーションが促進されるため、参加者間での協力や協働が進みます。問題解決や目標達成に向けての共同作業が推進され、個人やチームの成果向上に寄与します。

4. **レフレクションと学習:** 対話を通じて自身の考えや意見を他者と共有し、議論やフィードバックを受けることで、自己の思考や知識の再評価、反省が促されます。このプロセスによって、個人や組織の学習と成長が促進されます。

対話は、知識の共有と創造的な思考の促進を通じて、知働化の重要な要素となります。対話によって複数の視点や経験が結びつき、より豊かな知のネットワークが形成されることで、個人や組織の能力やパフォーマンスを向上させることができます。

知働化研究会の缶詰会やイベントによって、このような対話を促進してきました。また、このポジションペーパーも対話を導くために書いています。

<div class="page"/>

### 1.4.7. 知働化6＝自律

実行可能知識と知働化は、支配的な関係においても機能することがありますが、より自由度が高く、多様な状況に適応するためには「自律性」が重要です。この自律性は、政治や組織、コミュニティなどの民主化とも深く関わっています。

自律性は、個体やシステムが自らの意思や価値観に基づいて行動し、自己統制や自己決定を行う能力を指します。自律的な個体やシステムは、外部からの指示や制約に依存せずに目標を達成し、自己成長や独自の取り組みを進めることができます。

自律性が重要な理由は次の通りです：

1. **柔軟な適応力:** 自律的な個体やシステムは、変化や複雑な状況に対して柔軟に対応する能力を持っています。外部からの指示や制約に頼らずに自身の判断や行動を調整できるため、新たな課題や環境への適応が容易になります。

2. **高い意欲とエンゲージメント:** 自律的な個体やシステムは、自身の目標や意義に基づいて行動するため、高い意欲とエンゲージメントを持つことができます。自己の関心やパッションに従って取り組むことで、創造性や成果の向上につながります。

3. **責任と信頼:** 自律的な個体やシステムは、自らの行動に責任を持ち、信頼を築くことができます。自己統制や自己管理を行うことで、他者との協働やチームワークにおいても貢献することができます。

自律性の実現によって、以下のようなアウトカムが生まれます：

1. **創造性とイノベーション:** 自律的な個体やシステムは、自身の考えやアイデアを追求し、独自の視点や解決策を生み出すことができます。自己の関心やパッションに基づいて探求することで、新たなアイデアやイノベーションが生まれます。

2. **主体性と成長:** 自律的な個体やシステムは、自らの目標や成長に向けて自己の意思で取り組みます。自己の学習やスキルの向上に主体性を持ち、自己実現や発展を達成することができます。

3. **チームワークと協働:** 自律的な個体やシステムが集まる場合、相互に信頼を築き合い、個々の能力と自己責任を活かしながら、共同の目標に向けて協力し協働します。自律性が高まることで、個人の主体性とチームのパフォーマンスが向上します。

自律性は、個人やチーム、組織、社会において重要な概念です。自律的な行動や意思決定は、効果的なリーダーシップや組織文化の構築に貢献します。また、政治やチームなどの集合体においても、自律性を持った個体やシステムの相互作用によって、より持続可能な成果や共同の目標の達成が可能となります。

<div class="page"/>

### 1.4.8. 知働化7＝気付き

知働化は、知識から知恵への変換を指します。知恵とは物事や道理を識知・判断・推理する精神作用であり、智慧や悟りを含むことがあります。知とは物事の道理を判断し処理していく心の働きであり、物事の筋道を立て、計画し、正しく処理していく能力を指します。知の働きによって、我々は新たな気付きを得ることができます。

気付きとは、ある事柄や状況に対して新たな理解や洞察を得ることを意味します。知働化においては、気付きが重要な役割を果たします。気付きによって、我々は問題の本質を見極めたり、新たなアイデアを発展させたり、より深い洞察を得たりすることができます。

知働化は、仕事やエンジニアリングに限らず、日常生活のさまざまな行為や行動にも関連しています。知識や経験を活かし、自身の意思や能力を発揮することによって、我々は知の働きを通じて気付きを得ることができます。

なぜ知働化が必要なのでしょうか？知働化によって得られる気付きは、以下のような重要な理由から必要とされます：

1. **問題解決と改善:** 知働化による気付きは、問題解決や改善のための基盤となります。新たな情報や視点に気付くことで、問題の本質を把握し、適切な解決策や改善策を見出すことができます。

2. **創造性とイノベーション:** 気付きは創造性とイノベーションの源泉となります。新たなアイデアやアプローチを発展させるためには、既存の枠組みや常識にとらわれず、新たな気付きを得る必要があります。

3. **学びと成長:** 気付きは学びと成長のプロセスを促進します。新たな知識や経験に気付くことで、自己の能力や視野を広げ、個人や組織の成長を促すことができます。

4. **意思決定と判断:** 気付きは意思決定や判断の根拠となります。より深い洞察や理解を得ることで、より正確な判断や効果的な意思決定が可能となります。

知働化における気付きの重要性を理解し、日常的に気付きを得ることで、個人や組織のパフォーマンス向上や持続的な成果を実現することができます。気付きを得るためには、常に学び続ける姿勢や探究心を持ち、自身の知識や経験を積極的に活用することが重要です。


<!--
- 知とは
	- > 事物や道理を識知・判断・推理する精神作用。 また、真理を観ずるところの智慧や、悟りの意にも用いる。
	- 〔知性〕intellect; 〔知恵〕wisdom; 〔智巧〕cleverness, shrewdness
	- 智慧 wisdom 物事の道理を判断し処理していく心の働き。物事の筋道を立て、計画し、正しく処理していく能力。「—を借りる」「生活の—」
	- [https://ja.wikipedia.org/wiki/般若](https://ja.wikipedia.org/wiki/般若)
	- > アジタ（人名）よ、命ある者における煩悩の流れをせき止めるものは、気づき（sati）である。
		> それが煩悩の流れを堰き止める、とわたしは説く。般若によって、それら（煩悩の流れ）は塞がれる。— スッタニパータ1035 -->






<div class="page"/>


## 1.5. 知働化を飛躍させる ゆる

知働化アプローチをまとめてみましょう。

1. 知働化1 **実行可能知識** 記述された知識をゆるめ、環境と状況と共同する取り組みです。*ゆるコード*
2. 知働化2 **表現** さまざまな知識や思考の境界をゆるめ、理解しやすく伝わる状態にしてくことです。*ゆる経験*
3. 知働化3 **創造** その時の制約や問題をゆるめ、新たな枠組みを作り出すことです。*ゆる制約*
4. 知働化4 **学習** 刺激に対する画一的な反応をゆるめ、経験の区切りや選択群のシステムを修正することです。 *ゆる反応*
5. 知働化5 **対話** それぞれの異なった状況や情報をゆるめ、意見や知識を共有するプロセスのことです。*ゆる状況*
6. 知働化6 **自律** 観察と思考を停止させる支配をゆるめ、自らの意思や価値観で行動することです。*ゆる支配*
7. 知働化7 **気付き** 変わり映えしない日常的な経験をゆるめ、新たな理解や洞察を得ることです。*ゆる日常*

このように知働化は、知をゆるめる行為と表現できます。ここでの「ゆる」とは、構造を変化させ、ある対象に対する関係を弱くすることを示し、[YURUism: Embracing the Art of Relaxation for Limitless Possibilities](TBD) で整理しています。ゆるイズムは、それぞれの状況にあった それぞれ個別の思考や行為を作り出すことも目的としており、このポジションペーパーはその結果です。



<div class="page"/>

![YURUism: Embracing the Art of Relaxation for Limitless Possibilities](../_resources/YURUism-TitlePage.drawio-8.png)



<div class="page"/>

## 1.6. 知働化による新しい世界

長野市や近所において、公園の利用に関する共存のジレンマが生じました。公園は子どもたちが遊び、人々がリラックスする場所でありながら、近隣住民の中には騒音や騒ぎが気になるという声がありました。

長野市は1軒の住民からの騒音への訴えを受け、公園の閉鎖を決定しました。この決定は一部の住民の要望に基づいており、子どもたちの遊び場を奪うこととなりました。一方で、子どもたちや公園の活用者からは批判の声が上がり、共存の問題が浮き彫りになりました。

公園の利用に関する問題は、単純な解決策ではなく、異なるステークホルダーの利益や価値観が衝突していることが明らかです。

知働化のアプローチを適用することで、この共存のジレンマを解決に近づける道が見えてきます。ゆるめる（YURUism）アプローチを通じて、以下のようなアプローチを取ります。

1. **ゆるコード**：公園利用のルールや制約をゆるめ、状況に応じた柔軟な運用を実現します。公園の利用者や近隣住民の意見を尊重し、共有のルールを作り出します。

2. **ゆる経験**：異なるステークホルダー間での理解を深めるために、対話や体験を通じてコミュニケーションを図ります。お互いの立場やニーズを理解し、共感を生み出します。

3. **ゆる制約**：公園の利用に関する制約を柔軟に見直し、異なるニーズをバランスさせるための新たな枠組みを作り出します。子どもの遊び場や静寂な場所の確保など、共存の要素を考慮に入れます。

4. **ゆる反応**：市や住民の反応や意見を受け入れつつ、適切な修正や改善を行います。状況や経験に基づいたフィードバックを取り入れ、適切な調整を行います。

5. **ゆる状況**：異なるステークホルダーの参加と協力を促すために、対話や意見交換の場を提供します。共有の目標や価値観を共有し、協力して問題解決に取り組みます。

6. **ゆる支配**：市や関係者のリーダーシップをゆるめ、自律性や共同決定を促します。個々の意思や価値観を尊重し、共存のための適切なルールや枠組みを創り出します。

7. **ゆる日常**：問題解決の取り組みを日常に組み込み、持続可能な共存の実現を目指します。日常の中で柔軟な発想と創造性を駆使し、共存の可能性を追求します。

「共存のジレンマ：知働化による問題解決の迷走」は、知働化のアプローチを通じて、異なるステークホルダーが共存を実現するための道を模索するエピソードです。ゆるめるアプローチを適用することで、問題解決の迷走から持続可能な共存の解決策を見出すことができるでしょう。

知働化の探究は、まだ始まったばかりです。
皆さんとのお話しできることを楽しみにしています。
知働化とは何か、知働化がなぜ必要なのか、幅広く深くそして楽しく議論していきましょう。





