Listening Test
============

このREADMEはオープン以後も更新される可能性があります。

会場には現在v1.0.0のリビジョンを展示の概要文・導入文として会場にも置いてあります。


## 導入と概要

この展示及び作品は大雑把に言って、会場に設置されたモノフォニックシンセサイザーとしての機能を持った２台のコンピューターが自発的・対話的に、あるいは周囲の音に反応して勝手に発音・演奏を行うインスタレーションです。

各々のコンピューターにはスピーカーとマイクがそれぞれ接続されてあり、「声のような音」として認識されたものを中心に適宜集音・解析しデータを蓄積していくことで、自身の音響合成とコンポジションを変化させていきます。

（＊注：現状では実際にオーディオファイルとして録音・保存しているわけではなく、特徴量をある程度リアルタイムに解析することで簡易的なエフェクトを与えつつ、ログデータとして記録しています、会場内で喋った内容が残るということは現時点ではありません。）

２台のコンピューターは、機械学習で用いられるような統計的・確率的なネットワーク構造やデータモデルを一部に流用していますが、展示開始時の状態では、スピーチシンセサイザーのような人の声を模すことを目的としたようなものは特に意識せず、作家がある程度恣意的にベースとなるモデルを選択して音をセットアップしてあります。

外部の人の声やその他の環境音・ノイズの特徴を蓄積し、チューニングされていく先でどのような音の生成が行われるようになるのか・なるべきなのか、作者もあまり深く考えていません。

あくまで音響的な興味を前提としながら、言語やコミュニケーションの成り立ちについても考察しつつ発展させていければと思います。


## 雑多なリンクとメモ

- WaveNet: A Generative Model for Raw Audio

  喃語

  - https://deepmind.com/blog/wavenet-generative-model-raw-audio/
  - https://soundcloud.com/paperkettle/wavenet-babble-test-trained-a-neural-network-to-speak-with-my-voice


- 人工言語、隠語 / スラング、特定の者にだけ理解できる言語
  - グーグルの人工知能、自ら情報の「暗号化」を学ぶ

    そういえばソフトウェアがある通信プロトコルに対応していることを「○○が話せる」と喩えたりする

    - https://arxiv.org/pdf/1610.06918v1.pdf
    - http://wired.jp/2016/11/02/google-ai-encryption/

  - スラング、投稿型辞書
    - [urban dictionary](http://www.urbandictionary.com/)


- AIによる翻訳・中間言語
  - http://jp.techcrunch.com/2016/11/23/20161122googles-ai-translation-tool-seems-to-have-invented-its-own-secret-internal-language/
  - https://arxiv.org/pdf/1611.04558v1.pdf
  - [ウィキペディア日本版・『中間言語』の項目](https://ja.wikipedia.org/wiki/%E4%B8%AD%E9%96%93%E8%A8%80%E8%AA%9E)


- 機械学習・解析系の技術が最終的にもたらす結果よりもフローや中間状態に自分が惹かれるなと思ったものn選（まだあった気がする）
  - http://playground.tensorflow.org
  - https://vimeo.com/12774628


- 音声学、音による言語の分類・研究
  - [国際音声記号（IPA）](https://ja.wikipedia.org/wiki/%E5%9B%BD%E9%9A%9B%E9%9F%B3%E5%A3%B0%E8%A8%98%E5%8F%B7)
  - [各記号に対する音声データ](http://coelang.tufs.ac.jp/ipa/index.php)


- 聞くこと、コンポジション

  「楽器を選ぶこと、配置を決めること、録音ボタンを押すこと、その全てが作曲行為なのです。」

  - [外の音: フィールド・レコーディングの流儀](https://www.ableton.com/ja/blog/art-of-field-recording/)


- シンセサイザーの比喩

  ざっくりとだけど一応全部見た

  - [ccc-tv / Machine Dreams, 29:00あたりくらいから](https://media.ccc.de/v/33c3-8369-machine_dreams)


- （割と直接的に）刺激を受けた作品とか

    - Rashad Becker / Traditional Music of Notional Species Vol. I / II
      - [ele-king review（Traditional Music of Notional Species Vol. II）](http://www.ele-king.net/review/album/005497/)
