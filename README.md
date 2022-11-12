# filters
- インターネット上には、嫌な気分や悲しい気持ちになるような情報が溢れています。腐海フィルタや王蟲フィルタは、そんな不快（腐海）な要素を非表示にできる、uBlock Origin用のフィルタです。
  - 腐海フィルタは、ニュースサイトを始めとして様々なサイトにおいて、記事とは関係のない不快なサイドバーや関連記事等を非表示にします
  - 王蟲フィルタは、ニュースサイトのヘッドラインから、特定の不快文字列を含むニュースリンクを非表示にします。腐海フィルタとの併用が前提です。
- Yuki2718さんのYuki's uBlock Japanese filters - Annoyances および Annoyances Plusの公開終了に触発されました（愛用していたルールを一部引用しています）
  - 非表示とする範囲はYuki2718さんのものよりももっと広く、ニュースサイト等の関連記事一覧などを思い切ってごっそりと非表示にしています（これまで公開されてきたフィルタでこれらを非表示にしているものはないと思います）。まだ作りかけですが、これから少しずつ充実させていく予定です
- 本来、個人・仲間用に作成していたものですが、せっかくなので一般公開しました。心安らかなネットサーフィンを！

### 推奨環境
- ブラウザ：FirefoxまたはBrave
  - Firefoxの場合は強化型トラッキング防止機能を「厳格」に設定することを推奨します 
  - 現在はChromeでも動きますが、MV3に完全移行する2023年1月までに上記ブラウザのどちらかに乗り換えることを強く推奨します
- ブロッカー：uBlock Origin
  - AdGuard Annoyances、AdGuard Social Media、uBlock filters – Annoyancesを購読することを推奨します（ここで対応されていないものを消すため）

## 腐海フィルタ（3lun's Annoyances Filters）
<a href="https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/3lun/filters/main/annoyances.txt&title=3lun's Annoyances filter">フィルタを購読する</a>
[中身を見る](https://raw.githubusercontent.com/3lun/filters/main/annoyances.txt)

### このフィルタの特徴
- ニュースサイトを中心に、記事本文とは関係のない不快なサイドバー、ランキング、関連記事、おすすめ情報、速報を非表示にします。

### 対象とするサイトの言語
- 日本語、中国語

### このフィルタが向いている人
- 悲しいニュース・ショッキングな記事の氾濫に心を痛めている人
- 政治・社会系の対立煽り・誹謗中傷記事の乱立にうんざりしている人
- 自分で目的の情報を探し出せて、それ以外の興味のない情報を見たくない人
- 自分の世界に介入されたくない人

### 非表示にするもの
- マスコミ・ニュースサイトの記事の本文に関係のない関連ニュース・ランキングなど
  - 大手マスコミを含めほとんどの場合で不快あるいは悲しいニュースが見受けられますので、全て非表示にします
- ニュースサイト以外の関連記事のうち、特に扇情的、あるいは政治色や社会性の強いもの
- 自社宣伝・広告等で特に目立つもの
  - Amazonの「あなたへのおすすめ」など、既存フィルタの基準にぎりぎり引っかからない広告を非表示にします
- その他既存フィルタでは非表示対象外になる不快要素

### 非表示にしないもの
- 一般的な広告（AdGuard Japanese、EasyList等をご利用下さい）
- 既存のフィルタ（AdGuard、uBlock Origin、Fanboy'sのAnnoyancesフィルタで対応できるもの（クッキー通知など）
- ニュース一覧のページ
  - ここまで非表示にすると、目的の記事を探すことも困難になるのでやむを得ません。しかし、ランキングなどはやはり不快なので非表示にします

## 王蟲フィルタ（3lun's News filter）
<a href="https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/3lun/filters/main/news.txt&title=3lun's News filter">購読する</a>
[中身を見る](https://raw.githubusercontent.com/3lun/filters/main/news.txt)

### このフィルタの特徴
- ニュースサイトのヘッドラインで、不快な文字列を含む記事のリンクを一括非表示にします
- 主に事件・被害系、政治・活動家系、スキャンダル・炎上系の不快語を狙い撃ち！
  - [対象語一覧](https://raw.githubusercontent.com/3lun/filters/main/words.txt)（閲覧注意）
- 腐海フィルタを購読していることが前提です

### このフィルタが向いている人
- ニュースサイトはよく見るものの、不快なニュースは絶対に目にしたくない人

### 対応サイト
- 新聞等：読売、日経、産経、朝日、毎日、時事通信
- テレビ：NHK、FNN、ANN、TBS、MBS
- その他ネットニュース：Yahoo!ニュース、ニコニコニュース（この二つは特に不快な割に有益な情報が少ないので元々あまり見ません。そのため、漏れが多いと思います）
