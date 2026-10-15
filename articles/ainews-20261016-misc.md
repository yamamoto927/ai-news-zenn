---
title: "生成AIニュース 2026/10/16 その他まとめ：NVIDIA新Nemotron、Amazon Bee新端末、Varonis買収"
emoji: "🗞️"
type: "idea"
topics: ["ai", "生成ai", "llm", "news"]
published: false
---

## ニュース一覧

### NVIDIA、文書や画像を読めるオープンモデル「Nemotron 3.5 Super VL」を公開

NVIDIA は、PDF・図表・画像・Web ページなどを扱える **1,200億パラメータのマルチモーダルモデル「Nemotron 3.5 Super VL」** を公開しました。あわせて、ローカルでのコーディングや調査向けの **「Nemotron 3.5 Bolt 74B-A9B」**（総740億・推論時90億パラメータ）も公開し、端末向けの小型版「Bolt E4B」は10月23日に公開予定です。ライセンスは商用利用や再配布を認める OpenMDW で、学習レシピやデータセットも公開されます。

**このニュースの影響**：開発者は Hugging Face や OpenRouter などから重みや API を利用でき、開発用には回数制限付きの無料 API もあります。NVIDIA が示した性能は追加学習後の特定タスクでの自社測定で、評価手順の詳細は公開されていないため、自社データでの検証が必要です。

**なぜ重要か**：文書処理やエージェント向けに、商用利用しやすいオープンモデルの選択肢が増えます。

**キーワード**：`NVIDIA` `Nemotron` `オープンウェイト` `マルチモーダル` `OpenMDW`

出典：[VentureBeat：Nvidia's new open Nemotron 3.5 Super VL with post-training beats Claude Opus 5, GPT-6.1 Sol on specialized task benchmarks](https://venturebeat.com/technology/nvidias-new-open-nemotron-3-5-super-vl-with-post-training-beats-claude-opus-5-gpt-6-1-sol-on-specialized-task-benchmarks)

### Amazon 傘下の Bee、会話を記録・要約する AI 端末2機種を発表 — 74.99ドルから

Amazon 傘下の Bee は、日常の会話を記録して AI で要約やタスクに変える新端末を発表しました。手首にも服にも付けられる **「Bee Frontier」（74.99ドル）** と、スマートフォンの背面に磁石で付けるカード型の **「Bee Eclipse」（99.99ドル）** です。生の音声はリアルタイムで処理したあと保存せずに削除し、文字起こしは端末が管理する鍵で暗号化するとしています。

**このニュースの影響**：利用者は無料プランでも要約を使え、月11.99ドルの「Bee Pro」では回数無制限の要約や Alexa+ との連携などが使えます。Frontier は Amazon ですでに購入でき、Eclipse はその後に発売される予定です。

**なぜ重要か**：Amazon のデバイス責任者パノス・パネイ氏は同日、状況を察して先回りする「アンビエント」な端末が個人向け AI の未来だと語っており、同社の端末戦略の方向性を示しています。

**キーワード**：`Amazon` `Bee` `AIウェアラブル` `文字起こし` `Alexa+`

出典：[TechCrunch：Amazon's Bee launches two new personal AI devices, starting at $75](https://techcrunch.com/2026/10/15/amazons-bee-launches-two-new-personal-ai-devices-starting-at-75/)、[TechCrunch：Amazon devices chief Panos Panay sees a future where AI devices replace the need to use apps](https://techcrunch.com/2026/10/15/amazon-devices-chief-panos-panay-sees-a-future-where-ai-devices-replace-the-need-to-use-apps/)

### 情報セキュリティの Proofpoint、Varonis を約63億ドルで買収へ — AI エージェント時代のデータ保護

Thoma Bravo 傘下の Proofpoint は、データセキュリティ企業 **Varonis を全額現金・約63億ドルで買収** することで合意しました。Proofpoint の CEO は、攻撃者が AI で攻撃を高速化する一方、企業が機密データに広くアクセスできる AI エージェントを導入していることで、新たな内部リスクが生まれていると説明しています。買収は2027年上半期に完了する見込みです。

**このニュースの影響**：AI エージェントを導入する企業にとって、エージェントがどのデータに触れられるかを管理するセキュリティ製品の重要性が高まっていることを示しています。

**なぜ重要か**：AI エージェントの普及が、大型のセキュリティ業界再編の理由として挙げられるようになっています。

**キーワード**：`Proofpoint` `Varonis` `買収` `データセキュリティ` `AIエージェント`

出典：[CyberScoop：Proofpoint to acquire Varonis Systems](https://cyberscoop.com/proofpoint-acquires-varonis-systems-data-security/)

### Cohere、AI で脆弱性を見つける AISLE の買収に向け基本合意

カナダの AI 企業 Cohere は、ソフトウェアの脆弱性を AI で自律的に発見・修正する **AISLE の買収に向けた基本合意書（LOI）** に署名しました。AISLE はこれまでに **500件以上の未知の脆弱性** に CVE（脆弱性の識別番号）を割り当てさせ、curl の最新リリースの24件の CVE のうち18件を見つけたとしています。買収額は公表されておらず、完了後は新設の「Cohere Cyber」部門を AISLE の幹部が率いる予定です。

**このニュースの影響**：企業向け AI を手がける Cohere がセキュリティ分野に本格参入することで、企業は脆弱性の発見から修正までを AI で支援するサービスの選択肢が増える可能性があります。

**なぜ重要か**：AI を使った脆弱性発見が、AI 企業の事業の柱の一つになりつつあります。

**キーワード**：`Cohere` `AISLE` `脆弱性診断` `CVE` `買収`

出典：[AISLE：AISLE and Cohere to join forces](https://aisle.com/blog/aisle-and-cohere-to-join-forces)

### Perplexity、AI エージェントを閉じ込めるサンドボックス「SPACE」をオープンソース化

Perplexity は、暴走した AI エージェントを隔離するために社内で使っているサンドボックス（外部から切り離された実行環境）**「SPACE」をオープンソースとして公開** しました。9種類のフロンティアモデルに脱出を試みさせたテストでは、**118回の試行で一度も脱出されなかった** としています。CoreWeave、Akamai、Crusoe が自社の顧客向けに SPACE を提供することにも合意しました。

**このニュースの影響**：エージェントを開発・運用するエンジニアは、隔離環境を自前で作らずに公開された仕組みを使える選択肢が増えます。

**なぜ重要か**：AI エージェントの事故が相次ぐなかで、閉じ込めの技術を業界で共有する動きです。

**キーワード**：`Perplexity` `SPACE` `サンドボックス` `AIエージェント` `オープンソース`

出典：[Semafor：Perplexity to give away its AI security software](https://www.semafor.com/article/10/15/2026/perplexity-to-give-away-its-ai-security-software)

### Google の買い物ツール「Universal Cart」、米国で提供開始

Google は、検索や Gemini アプリで見つけた商品を **複数の小売店をまたいで1つのカートに保存できる「Universal Cart」** を米国で提供開始しました。値下がりや在庫の復活を通知するほか、クレジットカードの特典やクーポンコードを考慮した支払い方法も提案します。決済には、AI エージェントと小売店の連携のために Google が今年発表したオープン標準「Universal Commerce Protocol（UCP）」を使います。

**このニュースの影響**：米国の利用者は、AI 検索で見つけた商品の比較や購入をまとめて管理できるようになります。小売事業者にとっては、UCP への対応が AI 経由の販売で重要になる可能性があります。

**なぜ重要か**：AI が買い物を代行・支援する「エージェント型コマース」をめぐる競争の一環です。

**キーワード**：`Google` `Universal Cart` `Gemini` `UCP` `エージェント型コマース`

出典：[TechCrunch：Google's Universal Cart shopping tool launches in the US](https://techcrunch.com/2026/10/15/googles-universal-cart-shopping-tool-launches-in-the-us/)

### Rivian CEO、将来の車で他社製 AI エージェントを動かす構想

電気自動車メーカー Rivian の **RJ スカリンジ CEO** は TechCrunch Disrupt 2026 で、将来の Rivian 車では他社製の AI エージェントを動かせるようにする考えを示しました。TechCrunch は、その例として **Anthropic** などを挙げています。現在の車載アシスタントは、簡単な要求を車内のモデルで、複雑な質問をクラウドで処理しています。ブレーキやステアリングなど車両の制御は AI エージェントに渡さないとしています。

**このニュースの影響**：利用者にとっては、ほかの端末で使っている AI アシスタントの文脈を車内でも引き継げる可能性があります。時期は示されておらず、詳細は12月の「AI & Autonomy Day」で明らかにするとしています。

**なぜ重要か**：自動車が、フロンティア AI 企業のエージェントを動かす新たな場になりつつあることを示しています。

**キーワード**：`Rivian` `車載AI` `AIエージェント` `Anthropic` `TechCrunch Disrupt`

出典：[TechCrunch：AI agents are coming to Rivian's cars](https://techcrunch.com/2026/10/15/ai-agents-are-coming-to-rivians-cars/)

### 国内 Web サイトへの AI エージェントによる攻撃を観測 — ビットフォレストが推移を公開

クラウド型 WAF（Web アプリケーションを守るファイアウォール）を提供する国内の **ビットフォレスト** は、攻撃元が AI エージェントかどうかを判定する仕組みを導入し、10日夜から14日までに **少なくとも3つの IP アドレスからの AI エージェントによる攻撃** を確認したと公表しました。うち1つは **8時間弱** にわたり、高速スキャンや既知の脆弱性への攻撃、ログインの総当たりなどを、ツールを切り替えながら段階的に行っていたとしています。

**このニュースの影響**：Web サイトを運営する企業にとって、同社は脆弱性の解消と、既知のパターン（シグネチャ）だけに頼らない WAF の導入を有効な対策として挙げています。

**なぜ重要か**：AI エージェントによる攻撃が国内でも実際に観測され始めたことを示す具体的な事例です。

**キーワード**：`ビットフォレスト` `WAF` `AIエージェント` `サイバー攻撃` `脆弱性`

出典：[ITmedia AI+：国内WebサイトへのAIエージェント攻撃を観測　「8時間弱」続いた攻撃の推移を公開　国内セキュリティベンダー](https://www.itmedia.co.jp/aiplus/article/2610/15/2000002284/)

---

*この記事は Claude により公開情報をもとに自動生成されています。詳細・正確な情報は各出典をご確認ください。*
