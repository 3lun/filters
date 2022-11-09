# filters
インターネット上（腐海）には、嫌な気分や悲しい気持ちになるような情報が溢れています。これは、そんな不快（腐海）な要素を非表示にできる、uBlock Origin用のフィルタです。
Yuki2718さんのYuki's uBlock Japanese filters - Annoyances Plus（公開終了）に触発されました。一部ルールを引用させていただきました。

## 腐海フィルタ（3lun's Filters - Annoyances）
<a href="https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/3lun/filters/main/annoyances.txt&title=3lun's filters - Annoyances">フィルタを購読する</a>
[中身を見る](https://raw.githubusercontent.com/3lun/filters/main/annoyances.txt)

### 対象とするサイトの言語
- 日本語、中国語

### 非表示対象要素
- マスコミ・ニュースサイトの関連ニュース・記事リスト・ランキング
  - 大手マスコミを含めほとんどの場合で不快あるいは悲しいニュースが見受けられますので、全てブロックします
- ニュースサイト以外の関連記事のうち、特に扇情的、あるいは政治色や社会性の強いもの
- 自社宣伝・広告等で特に目立つもの
- その他既存フィルタでは対応できない不快要素

### 非表示対象外要素
- 一般的な広告（AdGuard Japanese、EasyList等をご利用下さい）
- AdGuardやuBlock Originのフィルタで対応できるもの（クッキー通知など）
  - ただし、AdGuardで対応できないものについては、ここで反映させています
 
### 想定している環境
- ブラウザ：FirefoxまたはBrave
  - Firefoxの場合は強化型トラッキング防止機能を「厳格」に設定することを推奨します 
  - 現在はChromeでも動きますが、MV3に完全移行する2023年1月までに上記ブラウザのどちらかに乗り換えることを強く推奨します
- ブロッカー：uBlock OriginまたはBrave Shields
  - AdGuard Annoyances、AdGuard Social Media、uBlock filters – Annoyancesを購読していることを前提とします

