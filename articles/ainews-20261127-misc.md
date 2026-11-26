---
title: "生成AIニュース 2026/11/27 その他まとめ：GPT-6.2の使用量計算を修正、S&PがNvidia格下げ検討"
emoji: "🗞️"
type: "idea"
topics: ["ai", "生成ai", "llm", "news"]
published: false
---

## ニュース一覧

### OpenAI、GPT-6.2 の使用量が少なく計算されていた問題を修正 — Astra は上限到達が約40%早まる見込み

OpenAI のプロダクト責任者ティボー・ソティオ氏が、11月17日に公開した **「GPT-6.2 Astra」と「GPT-6.2 Sol」の使用量が実際より少なく計算されていた** と X で明らかにしたと、ITmedia AI＋ が伝えました。問題はすでに修正され、修正前に比べて **Astra は約40%、Sol は約25% 早く利用上限に達する** 見込みです。おわびとして、有料プランの利用者に利用枠のリセット権が1回分付与されます。

**このニュースの影響**：Astra や Sol を多用している有料プランの利用者は、これまでと同じ使い方でも上限に早く達するため、使うモデルの使い分けやリセット権の使いどころを考える必要があります。

**なぜ重要か**：定額プランでは、使用量の計測方法の誤りやその修正が、利用者が使える量の体感に直結することを示しています。

**キーワード**：`GPT-6.2` `OpenAI` `ChatGPT` `利用制限` `GPT-6.2 Astra`

出典：[ITmedia AI＋](https://www.itmedia.co.jp/aiplus/article/2611/26/2000003495/)

### S&P、Nvidia の格下げを検討 — CEO 解任と復帰による「キーマンリスク」を懸念

格付け会社の **S&P Global Ratings が、Nvidia の信用格付けの引き下げを検討している** と TechCrunch が伝えました。理由は業績ではなく、Jensen Huang CEO の解任と復帰をめぐる経営監督の弱さや後継者計画の欠如、同氏への依存度の高さ（キーマンリスク）です。S&P は **90日以内** に審査を終える見込みで、格付けは **AA から AA-** に下がる可能性があります。

**このニュースの影響**：記事によると、Nvidia は自社で十分な信用力を持たないネオクラウド（GPU クラウド専業の事業者）などの借り入れを支えているため、格下げされれば、こうした AI インフラ企業の資金調達コストが上がる可能性があります。

**なぜ重要か**：AI インフラへの巨額融資が Nvidia の信用に支えられている構図の中で、同社の企業統治の問題が資金調達面にも波及しうることを示しています。

**キーワード**：`Nvidia` `S&P Global Ratings` `信用格付け` `ネオクラウド` `AIインフラ`

出典：[TechCrunch](https://techcrunch.com/2026/11/25/sp-considers-nvidia-credit-downgrade-over-governance-and-key-man-risks/)

### DeepL、遅延を半減した音声翻訳モデル「Aure v2」を東京のイベントで発表

DeepL は東京で開いたイベント「Unmute Tokyo 26」で、音声 AI モデル **「Aure v2」** を発表し、DeepL Voice の利用者向けに提供を始めました。前モデルに比べ、翻訳が始まるまでの遅延（中央値）を **50%削減** しています。文字起こし・翻訳・音声生成を1つにまとめた、音声から音声へ直接翻訳する方式（エンドツーエンド型）を採用し、話者の声の特徴や感情、抑揚も翻訳音声に反映するとしています。対応言語は日本語・英語・ドイツ語・フランス語・スペイン語・韓国語の6言語です。

**このニュースの影響**：DeepL Voice for Online Meetings、In-Person Conversations、DeepL API for Voice で、対応言語なら追加設定なしで自動的に適用されるため、オンライン会議や対面での通訳利用者、音声翻訳を組み込む開発者がそのまま恩恵を受けられます。

**なぜ重要か**：同社の社内ベンチマークでは英日翻訳で Google の Gemini 3.5 Live Translate より翻訳エラーが32%少ないとしており、リアルタイム音声翻訳をめぐる競争が日本語でも進んでいます。

**キーワード**：`DeepL` `Aure v2` `音声翻訳` `エンドツーエンド` `DeepL Voice`

出典：[Impress Watch](https://www.watch.impress.co.jp/docs/news/2159451.html)

### Obsidian、AI エージェント向けの公式スキル集とコネクタを公開

マークダウンエディタ **Obsidian** の開発チームが、AI エージェントから Vault（ノートの保管庫）を扱えるようにする **「コネクタ」と、オープンソースのスキル集** を公開しました。スキル集には、Obsidian 独自のマークダウン記法や Bases・Canvas ファイルの書き方、Obsidian CLI を使ったノートの検索・管理などが含まれます。公式ドキュメントでは Claude、ChatGPT（Codex を含む）、Cursor、GitHub Copilot などが対応エージェントとして挙げられています。

**このニュースの影響**：Obsidian でメモを管理している利用者や開発者は、普段使っている AI エージェントにノートの作成や検索を任せやすくなります。CLI を使うスキルはデスクトップアプリで Obsidian CLI を有効にする必要があり、ITmedia AI＋ によると対象はローカルの Vault です。

**なぜ重要か**：アプリ側が「エージェントにどう操作してほしいか」をスキルとして公式に配布する動きで、AI エージェント前提のアプリ設計が広がっていることを示しています。

**キーワード**：`Obsidian` `エージェントスキル` `コネクタ` `Obsidian CLI` `マークダウン`

出典：[ITmedia AI＋](https://www.itmedia.co.jp/aiplus/article/2611/26/2000003470/)、[Obsidian Help：Connectors](https://obsidian.md/help/connectors)

### NVIDIA、文書解析モデル「Nemotron 3.5 Parse」の学習データと微調整手順を公開

NVIDIA は Hugging Face のブログで、ページ画像を構造化データに変換する小型モデル **「Nemotron 3.5 Parse」** 向けに、グラフ・表・多言語 OCR の **合成データセット3種** と、微調整（ファインチューニング）の手順を公開しました。データセットはグラフ約998万件、表100万件、多言語 OCR 用ページ790万件です。H200 1基で、投機的デコーディング（小さなモデルで先の出力を予測して高速化する手法）の「DFlash2」を使うと、同時実行数1で処理量が **7.62倍** になったとしています。

**このニュースの影響**：RAG（検索拡張生成）やエージェントで PDF や帳票を読み込ませたい開発者は、公開データと手順を使って、自社の文書形式に合わせたモデルを作りやすくなります。

**なぜ重要か**：文書をAIに読ませる前処理は RAG の精度を左右する部分で、その学習データまで公開されることでオープンな改良が進めやすくなります。

**キーワード**：`Nemotron 3.5 Parse` `NVIDIA` `OCR` `RAG` `投機的デコーディング`

出典：[Hugging Face Blog](https://huggingface.co/blog/nvidia/building-on-nemotron-35-parse-open-data-fine-tunin)

### llama.cpp、AMD の Ryzen・Radeon での性能を追うベンチマークダッシュボードを公開

ローカル LLM 実行ツール **llama.cpp** を開発する ggml-org が、**AMD の Ryzen・Radeon 環境での推論性能を毎週計測して公開するダッシュボード** を Hugging Face で公開しました。Radeon 8060S と Radeon AI Pro R9700S を対象に、512トークンの入力処理と128トークンの生成の速度を、ビルド・モデル・量子化形式ごとに比較できます。計測対象のモデルには Inkling 2 Mini、Qwen、Gemma、gpt-oss などが含まれ、結果データも公開されています。

**このニュースの影響**：AMD 製の PC や GPU でローカル LLM を動かしたい開発者は、モデルや量子化形式を選ぶ際の判断材料として使えます。

**なぜ重要か**：ローカル推論の性能比較は NVIDIA 製 GPU が中心になりがちで、AMD 環境の継続的な計測データが公開される意義があります。

**キーワード**：`llama.cpp` `AMD` `Radeon` `ローカルLLM` `量子化`

出典：[Hugging Face Blog](https://huggingface.co/blog/ggml-org/llamacpp-amd-bench)

---

*この記事は Claude により公開情報をもとに自動生成されています。詳細・正確な情報は各出典をご確認ください。*
