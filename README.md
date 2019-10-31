# このレポジトリについて

- AillisのAI開発チームでは、各メンバーが気になった論文を紹介し合う論文輪読会を定期的に開催しています。
- その論文輪読会で各自が紹介した論文の要約をこのレポジトリの[Issue](https://github.com/AillisInc/paper_survey/issues)として、まとめていきます。
- ここに書かれている論文紹介の内容は、あくまで個人の解釈に基づくものであり、雑なメモ程度であるため、時折、解釈が正しくない場合もあるかも知れませんが、多少の間違いはご容赦いただければ幸いです。

# アイリス株式会社(Aillis Inc)について

- [アイリス株式会社](https://aillis.jp/) はディープラーニング技術を用いた、精度・早期診断対応のインフルエンザ検査デバイスの開発を行っています。
- 具体的には、インフルエンザに感染すると喉の後壁に濾胞（ろほう）と呼ばれる腫れ物ができるのですが、この腫れ物を含む喉の画像をCNNなどで画像解析したり、濾胞を物体検出することによって、インフルエンザかどうかを判定する仕組みです。
- インフルエンザ濾胞は、発症時点で既にのどに出ていることが知られているため、発症直後からの画像解析が可能で、鼻の奥に綿棒を入れて行う検査方法より、早期に判定が可能です。

## 使用技術など

- ディープラーニングのフレームワークは[Chainer](https://github.com/chainer/chainer)や[PyTorch](https://pytorch.org/)を使っており、画像解析系のニューラルネットワークを構築しています。
- ハイパーパラメータのチューニングには[optuna](https://github.com/pfnet/optuna)なども使っています。
- インフラは、産総研保有する世界最速(※ 2018年11月時点)のスパコンである、[ABCI](https://abci.ai/ja/)を使っています。

## [WIP]主要メンバー 

- こちらはまだ作成途中です

| Github ID                                                         | Role                   | Twitter                                         | ひとこと                                                                                                                                                      |
| :---------------------------------------------------------------- | :--------------------- | :---------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [fukumame](https://github.com/fukumame)                           | 取締役CTO              | [@fukumimi014](https://twitter.com/fukumimi014) | 小さいヒゲおじさん<br>[アイリスのAIチームに掛ける思い](https://note.mu/atsushi_f/n/ncef090f0d250)                                                             |
| [Tdys13](https://github.com/Tdys13)                               | AIエンジニア           | [@Tdys13](https://twitter.com/Tdys13)           | アイスと[医療×AIが大好き](https://speakerdeck.com/tdys13/aixyi-yong-hua-xiang-falsexian-zhuang-toke-neng-xing)<br>医療画像系DNNにおいて豊富な知識・実力を持つ |
| [analokmaus](https://github.com/orgs/AillisInc/people/analokmaus) | データサイエンティスト |                                                 | 国際データ解析オリンピックの[日本代表](https://jp.sputniknews.com/opinion/201904126123976-IDAO/)として出場<br />機械学習に関して豊富な知識を持つ              |
| [MasashiSode](https://github.com/MasashiSode) | データサイエンティスト | [@MasashiSode](https://twitter.com/MasashiSode) | [多目的ベイズ最適化](https://github.com/MasashiSode/MOBO)を応用した航空機設計に従事．<br />機械学習に関して豊富な知識を持つ              |


# アイリスの論文輪読会へ参加してみたい方
- 隔週水曜日の19時くらいから、弊社アイリスのオープンスペースにて、まったりと論文輪読会を行っています。
- 事前準備は最低限でOKで、各自が気になった論文を調べ、ざっと読んだ上で、こちらのレポジトリのIssueに要点などを記載します。
- 当日は、それぞれが要約を説明し、疑問点や活用できそうな点などをみんなでディスカッションします。
- テーマは特に自由ですが、画像系のニューラルネットワークや機械学習、画像処理周りの論文だと、弊社の関心領域と近いので嬉しかったりします。
- 参加希望の方は、[CTO福田のtwitter](https://twitter.com/fukumimi014)のDMなどで、ご連絡ください。 
- 参加資格などは特にありませんが、一応、節度ある場にはしたいので、あまりにも弊社の雰囲気と合わない方は審査の上お断りさせていただく可能性もあります。 その点、ご了承いただければと思います。

# We are hiring !
- それから、アイリス株式会社では、私達とともに、インフルエンザ検査デバイスのAIエンジンを開発していただけるメンバーを募集しています。
- 話を聞いてみたい方は、[Wantedly](https://www.wantedly.com/projects/294793)から「話を聞いてみたい」をしていただくか、[CTO福田のtwitter](https://twitter.com/fukumimi014)へDMにて、気軽にご連絡ください。
