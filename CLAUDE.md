# 生成AIデイリーニュース（Zenn自動投稿）

このリポジトリは Zenn と GitHub 連携している。`articles/` に Markdown を置いて `main` に push すると Zenn に公開される。
毎日のルーティン実行では、以下の「日次手順」に厳密に従うこと。

## 日次手順

1. **日付を確定する**：日本時間（JST）の今日の日付を `YYYY-MM-DD` で求める（例: `TZ=Asia/Tokyo date +%F`）。
   対象期間は「JST前日 06:00 〜 当日 06:00」の約24時間。
2. **重複チェック**：`articles/ai-news-YYYY-MM-DD.md` が既に存在すれば、何もせず終了する。
   また直近7日分の記事を読み、既に取り上げたニュースは再掲しない（大きな続報がある場合のみ「続報」として扱う）。
3. **収集**：WebSearch / WebFetch で対象期間のニュースを集める。下記「情報源」を優先する。
   - 各ニュースは **必ず一次情報（公式発表・論文・公式ブログ）か信頼できる報道の記事ページを実際に開いて** 内容を確認する。
   - 開いて確認できなかったニュースは載せない。日付が対象期間外のものも載せない。
4. **選別**：重要度順に 8〜12 件を選ぶ。優先度の目安：
   主要モデル/製品のリリース > 大型の資金調達・買収・提携 > 規制・政策 > 注目研究 > 開発ツール/OSS > その他。
   日本国内の動き（国内企業・政府・日本語モデル）は最低1件入れる（該当がなければ省略可）。
5. **執筆**：下記テンプレートで `articles/ai-news-YYYY-MM-DD.md` を作成する。
6. **検証**：front matter の形式、全ニュースに出典URLがあること、日付の整合を確認する。
7. **公開**：`git add articles/ && git commit -m "ai-news: YYYY-MM-DD" && git push origin main`

## 執筆ルール

- **front matter は必ず `published: false`（下書き）にする。** 公開への切り替えは人間が内容を確認してから手動で行う。
  Zenn の規約は「機械により自動生成された文章の投稿」をスパムとして禁止しているため、ルーティンが `true` にすることは絶対にしない。既存記事の `published` も変更しない。

- 要約は **自分の言葉で** 書く。元記事の文章を丸写ししない。引用は必要な場合のみ1文以内・引用符付き。
- 推測や未確認情報は書かない。噂・リークは「〜と報じられている」と明示し、出典を付ける。
- 各ニュースに「なぜ重要か」を1〜2文で添える（読者が要点だけ掴めるように）。
- 数値（価格・パラメータ数・ベンチマーク等）は出典に書かれているものだけを使う。
- 文体はです・ます調。専門用語は初出で簡単に補足する。

## 記事テンプレート

ファイル名: `articles/ai-news-YYYY-MM-DD.md`

```markdown
---
title: "生成AIニュース YYYY/MM/DD：<最重要トピックを短く>"
emoji: "📰"
type: "idea"
topics: ["ai", "生成ai", "llm", "news"]
published: false
---

## 今日のハイライト

- <最重要ニュースを1行で>
- <2番目>
- <3番目>

## ニュース一覧

### 1. <見出し>

<要約 2〜4文>

**なぜ重要か**：<1〜2文>

出典：[<媒体名>](<URL>)

### 2. ...

## まとめ

<今日の動向を2〜3文で総括>

---

*この記事は Claude により公開情報をもとに自動生成されています。詳細・正確な情報は各出典をご確認ください。*
```

## 情報源（優先）

- 公式：Anthropic News、OpenAI News、Google DeepMind / Google AI Blog、Meta AI Blog、Microsoft AI Blog、Hugging Face Blog、Mistral AI News、xAI
- 海外報道：TechCrunch (AI)、The Verge (AI)、VentureBeat (AI)、Reuters (Technology)、Ars Technica
- 国内報道：ITmedia AI+、Impress Watch、日経クロステック
- 研究：arXiv（cs.CL / cs.LG の注目論文）、Hugging Face Papers
