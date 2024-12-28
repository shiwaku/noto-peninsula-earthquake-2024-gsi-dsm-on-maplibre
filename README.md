# 令和6年能登半島地震後 被災状況3Dマップ
## Public Website
https://shiwaku.github.io/noto-peninsula-earthquake-2024-gsi-dsm-on-maplibre/

https://github.com/shi-works/noto-hanto-earthquake-2024-gsi-dsm-map-on-maplibre-gl-js/assets/71203808/7491b0a3-e7f6-4cc7-932b-589415df5f37

## Data Source
### 国土地理院
- 被災後の数値表層モデル（DSM）
    - 出典：[令和6年(2024年)能登半島地震 3Dモデル閲覧サイト](https://maps.gsi.go.jp/noto/#11/37.343686/137.009125/&base=std&ls=std%7C20240102noto_wazimanaka_0111do%7C20240102_noto_nanao_0105do%7C20240102noto_anamizu_0117do%7C20240102noto_wazimanishi_0111do%7C20240102noto_wazimahigashi_0102do%7C20240102noto_wazimahigashi_0114do%7C20240102noto_suzu_0102do%7C20240102noto_suzu_0114do&blend=00000000&disp=111111111&lcd=20240102noto_suzu_0114do&vs=c1g1j0h0k0l0u0t0z0r0s0m0f0)
    - 標高タイルURL：https://maps.gsi.go.jp/xyz/20240102noto_1mDSM/{z}/{x}/{y}.png
    - 概要：以下の撮影日に国土地理院が撮影した空中写真を使用し、SfM手法を用いて作成した数値表層モデル（DSM）です。
        - 珠洲地区：１月２日及び１月１４日撮影
        - 輪島東地区：１月２日及び１月１４日撮影
        - 輪島中地区：１月１１日撮影
        - 輪島西地区：１月１１日及び１月１７日撮影
        - 穴水地区：１月１７日撮影
        - 七尾地区：１月５日及び１月１７日撮影
    - 留意事項：本サイトから得られる高さ情報は測量成果ではなく、精度検証は実施していません。
    - 免責事項：本サイトから得られる情報の利用により生じた一切の損害について、国土地理院はいかなる責任も負わないものとします。

- 被災後の空中写真（正射画像）
    - 出典：https://www.gsi.go.jp/BOUSAI/20240101_noto_earthquake.html#3-1
        - 珠洲地区：１月２日及び１月１４日撮影
        - 輪島東地区：１月２日及び１月１４日撮影
        - 輪島中地区：１月１１日撮影
        - 輪島西地区：１月１１日及び１月１７日撮影
        - 穴水地区：１月１７日撮影
        - 七尾地区：１月５日及び１月１７日撮影

- 斜面崩壊・堆積分布データ（2024年1月22日更新）
    - 出典：https://www.gsi.go.jp/BOUSAI/20240101_noto_earthquake.html#2
    - 概要：国土地理院が1月2日、5日、11日、14日及び17日に撮影した空中写真（正射画像）・（珠洲地区、輪島東地区、輪島中地区、輪島西地区、穴水地区、七尾地区）から、令和6年能登半島地震によって生じたと考えられる斜面崩壊地及び土砂堆積箇所の範囲について判読（一部は再度判読）したものです。
    - ※1 道路や河川上の土砂は、一部撤去されている可能性があります。
    - ※2 珠洲地区は、1月2日及び5日に撮影した空中写真（正射画像）を用いて、輪島東地区は、1月2日に撮影した空中写真（正射画像）を用いて判読しています。
    - ※3 輪島西地区は、1月11日に撮影した空中写真（正射画像）を用いて判読しています。
    - ※4 輪島中地区は、1月2日、5日及び11日に撮影した空中写真（正射画像）を用いて判読しています。
    - ※5 穴水地区は、1月5日、14日及び17日に撮影した空中写真（正射画像）を用いて判読しています。
    - ※6 七尾地区は、1月5日及び17日に撮影した空中写真（正射画像）を用いて判読しています。

- 空中写真判読による津波浸水域（推定）データ（2024年1月19日更新）
    - 出典：https://www.gsi.go.jp/BOUSAI/20240101_noto_earthquake.html#7
    - 概要：国土地理院が1月2日、5日、11日、14日及び17日に撮影した空中写真（珠洲地区、輪島東地区、輪島西地区、穴水地区、七尾地区）から、令和6年能登半島地震によって生じたと考えられる津波到達範囲（堤外地を含む）を判読（一部を再判読）して作成したものです。
    - ※海岸線は空中写真（正射画像）に合わせて取得しており、地形図と整合していない箇所があります。

- 空中写真等の画像判読による輪島市中心の火災焼失範囲（推定）（2024年1月12日更新）
    - 出典：https://www.gsi.go.jp/BOUSAI/20240101_noto_earthquake.html#17
    - 概要：国土地理院が令和6年1月2日に撮影した空中写真等を画像判読して輪島市中心の火災による焼失範囲を推定したものです。

- 空中写真で確認した、陸化したと思われる港等（1月18日更新）
    - 出典：https://www.gsi.go.jp/BOUSAI/20240101_noto_earthquake.html#17
    - 概要：下記HPより港の名称を取得して、空中写真で確認した「隆起の影響で著しく水がなくなっている港データ」を作成。
    - 第九管区海上保安本部海洋情報部HP：「[航空機から見た石川県の港湾と海岸線](https://www1.kaiho.mlit.go.jp/KAN9/tori-naru/ishikawa-sakuin.htm#ishikawa-plan)」

- 亀裂分布データ（2月14日公表）
    - 出典：https://www.gsi.go.jp/BOUSAI/20240101_noto_earthquake.html#4
    - 概要：地震によって生じたと考えられる地表の亀裂箇所について空中写真を判読して作成。

- 上記の公開データのライセンス：[国土地理院コンテンツ利用規約](https://www.gsi.go.jp/kikakuchousei/kikakuchousei40182.html)に従い、出典明示により、転載も含め使用可

### 日本地理学会災害対応委員会
- 海岸地形変化の検討結果（1月15日公開）
    - 出典：https://ajg-disaster.blogspot.com/
    - 概要：http://disaster.ajg.or.jp/files/202401_Noto008.pdf

- 上記の公開データのライセンス：令和6年能登半島地震変動地形調査グループ（日本地理学会）、[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.ja)

### 背景地図及び地形データ
- 国土地理院 最適化ベクトルタイル
    - 出典：https://github.com/gsi-cyberjapan/optimal_bvmap
    - ライセンス：[国土地理院コンテンツ利用規約](https://www.gsi.go.jp/kikakuchousei/kikakuchousei40182.html)に従い、出典明示により、転載も含め使用可
- 国土地理院 地理院タイル（陰影起伏図）
    - 出典：https://maps.gsi.go.jp/development/ichiran.html#hillshademap
    - ライセンス：[国土地理院コンテンツ利用規約](https://www.gsi.go.jp/kikakuchousei/kikakuchousei40182.html)に従い、出典明示により、転載も含め使用可
