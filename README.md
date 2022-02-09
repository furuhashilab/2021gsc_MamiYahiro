# 2021gsc_MamiYahiro
2021年度古橋ゼミ論用リポジトリ　八尋舞美

## 2021年度　八尋舞美ゼミ論用リポジトリ

青山学院大学　地球社会共生学部　地球社会共生学科

八尋舞美/Mami Yahiro

学籍番号 1A118170

指導教員　古橋　大地　教授

© Furuhashi Laboratory/Mami Yahiro, CC BY 4.0

## 最終発表


# 【2021年度ゼミ論】タイトル：江の島の絶景スポットを海外の方向けにまとめたサイト作成

## Introduction
今回のゼミ論では、江の島の絶景スポットを海外の方向けにまとめたサイト作成を行う。昨年の江ノ島でのセーリングオリンピックで、各国の選手関係者と話す機会があった。その時に眺めの良い場所を知りたがっており、そういった場所をもっと海外の方にも発信していきたいと感じた。また去年のゼミ論で江ノ島を歩いた時にガイドブックには載ってないような絶景をいくつか見つけたが、海外の方向けの観光サイトではこれらの穴場の絶景スポットはあまり見られなかった。現在コロナの影響で海外からの観光客はほとんどいないが、いずれ江の島に外国人観光客が戻った際にはこれらの絶景スポットにも訪れて欲しいと考え今回のテーマに至った。

#### 藤沢市観光公式ホームページ・藤沢のLocalWikiにおける江ノ島関連ページの現状

藤沢市観光公式ホームページでは、英語版のページはあるが載っている観光スポットは有名なところのみで、絶景スポットをメインに紹介したページはない。またそれぞれの観光スポットの場所をまとめた地図はPDFのみでWEB地図での掲載はなかった。藤沢市のLocalWikiには、江ノ電や小田急江ノ島線、駅前の魚屋などのページはあるが、江ノ島内の観光に関するページは見当たらない。
その他江ノ島を紹介した英語のサイトも文章だけであったり、有名なスポットを紹介しているものが多い。

#### 基本方針
以上の点を踏まえ今回のサイト作成では以下のことを意識して作成していく。

* テーマを絶景に絞る。
> 絶景とは、他にたとえようもない、素晴らしい景色のことをいいます。これは、神秘的風景や幻想的風景、驚愕風景、異次元風景など、自然が作り出した信じられない景色で、人生観が変わるほどの感動や興奮を及ぼすことがあります。 （x-Memory トラベル用語より）　

今回は島である江ノ島の特性も活かして、海が見える且つ自然が作り出した他では見られない景色に定義付けてまとめていく。

* 英語でまとめる。対象は江ノ島に訪れた海外の方、実際には来れないけど江ノ島の絶景を見たい海外の方とする。

* 各スポットの場所、写真が一目で見える地図を載せる。江ノ島に訪れた海外の方が自力で各スポットに行けるように、PDFの地図ではなく正確な距離や現在地が把握しやすいWEB地図で作成する。

* 江ノ島に来たことがない人にもどんな眺めなのか伝わるように写真を多く載せていく

#### 具体的にどのようなサイトにしていくのか
各スポットを一つの地図に表示させ、一目でどこに何があるのかが把握しやすいようにする。各スポットをクリックすると名前と写真が表示されるようにして、そこがどんな場所なのかすぐに分かるようにする。そこから詳細のページに飛べるようにする。詳細のページでは各スポットの説明文（どのような場所なのか、行き方の簡単な説明、何が見えるのか）、ルート、写真（360度画像含む）を載せていく。





## Methods
作業は大きく分けて4つ

#### （１）絶景スポットを決める
実際に江の島に行き、絶景が見える箇所を去年のゼミ論も参考に探す。
![IMG_9207](https://user-images.githubusercontent.com/62396682/152580912-4a301db7-5845-402a-b9f4-45944e88a7be.jpg)


今回10ヶ所の絶景スポットをピックアップ

1)湘南港北緑地広場

2)湘南港臨港道路附属駐車場の防波堤

3)西浦漁港

4)御岩屋道通りの階段から見える「山二つ」

5)亀ヶ岡広場のウッドデッキ

6)中津宮広場のウッドデッキ

7)稚児ヶ淵

8)江ノ島の頂上に通じる避難経路の階段

9)高台にある住宅地の細道

10)江ノ島アイランドスパ前の階段

#### (2)各スポットの情報をCSVファイルにまとめる

[Enoshima.csv](https://github.com/furuhashilab/2021gsc_MamiYahiro/files/8005076/Enoshima.csv)
<img width="1063" alt="スクリーンショット 2022-02-05 2 01 42" src="https://user-images.githubusercontent.com/62396682/152580574-085a2162-dafa-4558-b8fe-dd672a21b3f9.png">

#### (3)CSVファイルをumapにインポートする
<img width="" alt="スクリーンショット 2022-02-05 2 04 38" src="https://user-images.githubusercontent.com/62396682/152580637-d0e79972-6942-4627-aab3-d9f8d72e086a.png">


#### (4)LocalWikiにまとめる
地図の埋め込み方法→参照https://ja.localwiki.org/mr/%E8%A8%98%E4%BA%8B%E3%81%AB%E5%9C%B0%E5%9B%B3%28umap%29%E3%82%92%E5%9F%8B%E3%82%81%E8%BE%BC%E3%82%80
<img width="８００" alt="スクリーンショット 2022-02-05 3 13 13" src="https://user-images.githubusercontent.com/62396682/152582734-0c2362ad-b7db-48b6-ac3a-a0b53b79401e.png">
緑のパズルのメディアを埋め込みの部分にコードを埋め込む

## Result

LocalWiki
https://ja.localwiki.org/fujisawa/The%20beautiful%20scenery%20of%20Enoshima

メインのページには各スポットをまとめたumapを載せ、クリックすると名称、写真、詳細ページURL、ルートのURLが表示される。

<img width="1000" alt="スクリーンショット 2022-02-05 1 32 14" src="https://user-images.githubusercontent.com/62396682/152582073-a05b4ee2-f660-47c4-8d7c-5a5effe379c2.png">
また地図の下に、名称と写真をまとめ、名称のリンクからも詳細ページに飛べるようにした。
<img width="1000" alt="スクリーンショット 2022-02-05 1 32 57" src="https://user-images.githubusercontent.com/62396682/152581980-b4c4766e-38ab-43b9-a2cc-5dcfc12b272f.png">

各スポットの詳細ページには、概要説明、写真、ルートのURLを掲載
それぞれの場所がどんな場所かイメージつきやすくするため、スマートフォンの他に360度カメラでの撮影も行った。
<img width="1000" alt="スクリーンショット 2022-02-05 1 33 51" src="https://user-images.githubusercontent.com/62396682/152581808-ee36cf52-2fb8-4e65-b080-c60fcd653892.png">


## Discussion
今回の作成結果として、各スポットをデジタル地図に写真と共にまとめたことで、PDFのイラストマップと比較して、より正確な位置やその場の様子を把握しやすくなったと考える。しかし今回の課題として挙げられるのは、天気や時間帯によってそこから見える景色は大きく変わってしまうという不確定な部分である。必ずしも写真のような景色が見えるとは限らない。違う時間帯ごとにどんな景色が見えるのか調査し、写真のような景色が見える時間帯を特定すれば、より分かりやすくなったのではないかと考える。またもう一つの課題として、360度画像のそのページでの表示がうまくできなかったことだ。サイト埋め込み用のコードは作れたが、それを載せてもうまく反映されなかった。そのため今回は、Googleフォトを使い、別ページでの掲載を行った。

## Conclusion
今回のゼミ論を通じて、同じ海の景色でも場所によって見え方が全然違うことに気がついた。また去年は立ち入り禁止だった場所が行けるようになっていたり、去年行けた場所が立ち入り禁止になっていたりしてるところが何ヶ所かあった。今後さらに海外の方に江ノ島の絶景を伝えるためにもこまめに更新し、こういった変化にも対応できるようにしていきたい。ウィキペディアなどのより大きなプラットホームに載せれる情報を移すことや、SNSによる周知などによって自分以外の人でも情報を更新していける仕組み作りが重要になると感じた。自分が卒業した後も動かし続けるために、まずはLocalWikiの情報でどれが移せる情報なのか取捨選別する必要がある。

## 参考文献
https://docs.google.com/spreadsheets/d/1MxDfNtNdVV5fGdWIDxwt9DxHjt-asm9imttNbXWchT8/edit#gid=0

## 先行事例

にいがた観光ナビ
https://niigata-kankou.or.jp/pickup/zekkei?sortType=access&listStyle=map&latitude=&longitude=&keyword=#searchResultArea


London attractions map
https://www.visitlondon.com/things-to-do/london-attractions-map


cgs部おすすめの観光スホット
https://ja.localwiki.org/ksm/cgs%E9%83%A8%E3%81%8A%E3%81%99%E3%81%99%E3%82%81%E3%81%AE%E8%A6%B3%E5%85%89%E3%82%B9%E3%83%9B%E3%83%83%E3%83%88


umapを使ってオンラインガイドマップを作ろう！
http://www.yamasita.jp/osm/seminar/150221_OpenDataDay/umap.pdf




## 発表用スライド
https://docs.google.com/presentation/d/18KpS5tUHmL3YqcUOdI_axn2PfUdQRjwD4_Fs3p41RoM/edit#slide=id.g1118c264b68_1_0


## プロジェクト管理
https://github.com/furuhashilab/2021gsc_MamiYahiro/projects/1
