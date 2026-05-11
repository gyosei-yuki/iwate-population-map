# 🏙️ 岩手県・地域別人口 3D可視化マップ

<img width="1920" height="1080" alt="{B9272F4A-3798-42A3-A1F4-672C2D9ACF34}" src="https://github.com/user-attachments/assets/f2a14211-292e-43e6-8991-1b4c647e41dd" />

岩手県内の地域別人口データを、Kepler.glを用いて3Dの棒グラフとして直感的に可視化したシビックテック（オープンデータ利活用）プロジェクトです。
各地域の人口密度や密集度合いを、ブラウザ上で立体的に把握することができます。

## 🌐 デモサイト (Live Demo)
以下のリンクから、インストール不要でブラウザ上で操作・閲覧が可能です。

* **盛岡市版マップ**
  👉 https://gyosei-yuki.github.io/iwate-population-map/morioka.html
* **北上市版マップ**
  👉 https://gyosei-yuki.github.io/iwate-population-map/kitakami.html

## 📊 データ出典・ライセンス
本プロジェクトは、以下のオープンデータを利用し、機械判読性向上のためのデータクレンジング（不要なスペース文字の除去、データ型の変換等）を施して作成しています。

**1. 岩手県オープンデータポータル「DataEYE」**
本データは「CC BY（表示）」に基づき、一部加工して利用しています。
出典：岩手県及び市町村共同オープンデータポータルサイト「DataEYE」（https://dataeye.iwate.jp/）

**2. 北上市オープンデータサイト**
出典：北上市オープンデータサイト
（https://www.city.kitakami.iwate.jp/life/soshikikarasagasu/toshipromotionka/jouhouseisakusuishinshitsu/1_1/opendata/index.html）

**3. 政府統計の総合窓口（e-Stat）**
出典：「政府統計の総合窓口（e-Stat）」（https://www.e-stat.go.jp/）
※本データは加工して利用しています。

---
# 🛠️ 使用ツール・地図データ
- **Mapbox**: © Mapbox © OpenStreetMap
- **kepler.gl**: © Uber Technologies, Inc. （本プロジェクトは MIT License に基づき kepler.gl を利用しています）
- **データ処理**: Python (Pandas, GeoPandas)

---

## ⚠️ 免責事項
当マップにおけるデータの正確性、有用性、安全性等について、いかなる保証も行うものではありません。当サイトに掲載された内容によって生じた損害等の一切の責任を負いかねますのでご了承ください。
