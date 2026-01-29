# 画像生成練習記録

AI画像生成のプロンプトと結果を記録するリポジトリ。

## 📚 記録一覧

### 記録 #1: 岩手県盛岡市

**日時:** 2026-01-29

**お題:** 岩手県盛岡市

**プロンプト:**
```
Beautiful landscape of Morioka city, Iwate Prefecture, Japan. Historic Morioka Castle ruins in Iwate Park with cherry blossoms in full bloom, traditional Japanese architecture, majestic Mt. Iwate in the background, clear blue sky, peaceful atmosphere, high quality, detailed, photorealistic
```

**生成された画像:**
![岩手県盛岡市](https://v3b.fal.media/files/b/0a8c428d/GfqE47WvXez1RLUjS_RbN_8Xd3M2R6.png)

**パラメータ:**
- 解像度: 1K
- アスペクト比: 16:9
- 生成時間: 17.8秒
- モデル: Nano Banana Pro (Gemini 2.5 Flash)

**結果:**
盛岡城跡（岩手公園）をイメージした風景画像が生成されました。桜が満開で、背景には岩手山が見える美しい構図です。

---

### 記録 #2: 盛岡市観光地紹介ポスター

**日時:** 2026-01-29

**お題:** 観光地紹介（文字入りの説明用ポスター）

**事前調査:**
Web検索で盛岡市の主要観光スポットを調査：
- 盛岡城跡公園：花崗岩の見事な石垣、桜の名所
- もりおか啄木・賢治青春館：明治建築、啄木と賢治の資料展示
- 岩手銀行赤レンガ館：明治44年建設、辰野金吾設計、重要文化財
- 盛岡八幡宮：歴史ある神社
- 石割桜：岩を割って成長した桜

**プロンプト:**
```
Professional tourism infographic poster for Morioka City, Iwate Prefecture, Japan. Vertical poster design with Japanese text.

Title at top: "盛岡市観光ガイド" (Morioka City Tourism Guide)

Layout with 4 main sections, each with image and text:

1. Top Left: Image of Morioka Castle ruins with stone walls and cherry blossoms. Text: "盛岡城跡公園 - 見事な石垣と桜の名所"

2. Top Right: Image of red brick bank building with green dome. Text: "岩手銀行赤レンガ館 - 明治44年、辰野金吾設計の名建築"

3. Bottom Left: Image of classical Japanese building. Text: "もりおか啄木・賢治青春館 - 二人の偉人を知る文化館"

4. Bottom Right: Image of cherry tree growing through granite rock. Text: "石割桜 - 岩を割る生命力の桜"

Bottom text: "歴史と文化が息づく城下町 Morioka"

Design: Clean modern travel poster, white background, elegant typography, high quality, Japanese travel magazine style, 4K resolution
```

**生成された画像:**
![盛岡市観光ガイド](https://v3b.fal.media/files/b/0a8c42b6/fTZw2YuNnX6Nr4WQ5cUDh_HOBR05rd.png)

**パラメータ:**
- 解像度: 1K
- アスペクト比: 9:16（縦長ポスター）
- 生成時間: 23.4秒
- モデル: Nano Banana Pro (Gemini 2.5 Flash)

**結果:**
観光地紹介の縦長ポスターが生成されました。盛岡市の主要観光地4箇所を紹介するインフォグラフィックスタイルのデザインで、日本語のキャプションが含まれています。

**学び:**
- 事前にWeb検索で観光地情報を収集することで、具体的で正確なプロンプトを作成できた
- 縦長（9:16）のアスペクト比でポスター形式の画像を生成
- 日本語のテキストを画像内に配置させることで、説明用のコンテンツを作成可能

---

## 🛠️ 使い方

### Webインターフェース
`index.html` をブラウザで開くと、プロンプトと生成画像を記録・管理できるインターフェースが使えます。

### 主な機能
- プロンプトと生成画像の記録
- プロンプトでの検索・フィルタリング
- プロンプトのクリップボードコピー
- データのエクスポート/インポート（JSON形式）
- 画像のダウンロード
- ローカルストレージでのデータ保存

## 📝 ライセンス

CC0 1.0 Universal
