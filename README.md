# filters
インターネット上には、嫌な気分や悲しい気持ちになるような情報が溢れています。腐海フィルタは、そんな不快（腐海）な要素を非表示にできる、uBlock Origin用のフィルタです。
Yuki2718さんのYuki's uBlock Japanese filters - Annoyances Plus（公開終了）に触発されました。一部ルールを引用しています。

## 腐海フィルタ（3lun's Filters - Annoyances）
<a href="https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/3lun/filters/main/annoyances.txt&title=3lun's filters - Annoyances">フィルタを購読する</a>
[中身を見る](https://raw.githubusercontent.com/3lun/filters/main/annoyances.txt)

### 対象とするサイトの言語
- 日本語、中国語

### このフィルタが向いている人
- 悲しいニュース・ショッキングな記事の氾濫に心を痛めている人
- 政治・社会系の対立煽り・誹謗中傷記事の乱立にうんざりしている人
- 自分で目的の情報を探し出せて、それ以外の興味のない情報を見たくない人

### 非表示にするもの
- マスコミ・ニュースサイトの記事の本文に関係のない関連ニュース・ランキングなど
  - 大手マスコミを含めほとんどの場合で不快あるいは悲しいニュースが見受けられますので、全て非表示にします
- ニュースサイト以外の関連記事のうち、特に扇情的、あるいは政治色や社会性の強いもの
- 自社宣伝・広告等で特に目立つもの
  - Amazonのおすすめ商品など、既存フィルタの基準にぎりぎり引っかからない広告を非表示にします
- その他既存フィルタでは非表示対象外になる不快要素

### 非表示にしないもの
- 一般的な広告（AdGuard Japanese、EasyList等をご利用下さい）
- AdGuardやuBlock Originのフィルタで対応できるもの（クッキー通知など）
  - ただし、AdGuardで対応できないものについては、ここで反映させています
- ニュース一覧のページ
  - ここまで非表示にすると、目的の記事を探すことも困難になるのでやむを得ません。しかし、ランキングなどはやはり不快なので非表示にします
 
### 推奨環境
- ブラウザ：FirefoxまたはBrave
  - Firefoxの場合は強化型トラッキング防止機能を「厳格」に設定することを推奨します 
  - 現在はChromeでも動きますが、MV3に完全移行する2023年1月までに上記ブラウザのどちらかに乗り換えることを強く推奨します
- ブロッカー：uBlock OriginまたはBrave Shields
  - AdGuard Annoyances、AdGuard Social Media、uBlock filters – Annoyancesを購読していることを前提とします

