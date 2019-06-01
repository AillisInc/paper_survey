# このレポジトリについて

- AillisのAI開発チームでは、各メンバーが気になった論文を紹介し合う論文輪読会を定期的に開催しています。
- その論文輪読会で各自が紹介した論文の要約をこのレポジトリの[Issue](https://github.com/AillisInc/paper_survey/issues)として、まとめていきます。
- ここに書かれている論文紹介の内容は、あくまで個人の解釈に基づくものであり、雑なメモ程度であるため、時折、解釈が正しくない場合もあるかも知れませんが、もし間違いがありましたらご容赦いただければ幸いです。

# アイリス株式会社(Aillis Inc)について

- [アイリス株式会社](https://aillis.jp/) はディープラーニング技術を用いた、精度・早期診断対応のインフルエンザ検査デバイスの開発を行っています。
- 具体的には、インフルエンザに感染すると喉の後壁に濾胞（ろほう）と呼ばれる腫れ物ができるのですが、この腫れ物を含む喉の画像をディープラーニング技術で画像解析することによって、インフルエンザかどうかを判定する仕組みです。
- インフルエンザ濾胞は、発症時点で既にのどに出ていることが知られているため、発症直後からの画像解析が可能で、鼻の奥に綿棒を入れて行う検査方法より、早期に判定が可能です。

## 使用技術など

- ディープラーニングのフレームワークは[Chainer](https://github.com/chainer/chainer)や[PyTorch](https://pytorch.org/)を使っています
- ハイパーパラメータのチューニングには[optuna](https://github.com/pfnet/optuna)なども使っています。
- インフラは、産総研保有する世界最速(※ 2018年11月時点)のスパコンである、[ABCI](https://abci.ai/ja/)を使っています。

## [WIP]主要メンバー 

- こちらはまだ作成途中です

| Github ID                               | Role         | Twitter                                         | ひとこと                                                     |
| :-------------------------------------- | :----------- | :---------------------------------------------- | ------------------------------------------------------------ |
| [fukumame](https://github.com/fukumame) | 取締役CTO    | [@fukumimi014](https://twitter.com/fukumimi014) | 小さいヒゲおじさん                                           |
| [Tdys13](https://github.com/Tdys13)     | AIエンジニア | [@Tdys13](https://twitter.com/Tdys13)           | アイスと[医療×AIが大好き](https://speakerdeck.com/tdys13/aixyi-yong-hua-xiang-falsexian-zhuang-toke-neng-xing) |

# We are hiring !

- アイリス株式会社では、私達とともに、インフルエンザ検査デバイスのAIエンジンを開発していただけるメンバーを募集しています。
- 話を聞いてみたい方は、[Wantedly](https://www.wantedly.com/projects/294793)から「話を聞いてみたい」をしていただくか、[CTO福田のtwitter](https://twitter.com/fukumimi014)へDMにて、気軽にご連絡ください。
