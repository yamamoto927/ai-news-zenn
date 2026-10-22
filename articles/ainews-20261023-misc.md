---
title: "生成AIニュース 2026/10/23 その他まとめ：Microsoft診断AI、Agent Skills移管、Canva画像AI"
emoji: "🗞️"
type: "idea"
topics: ["ai", "生成ai", "llm", "news"]
published: false
---

## ニュース一覧

### Microsoft の診断 AI「MAI-DxO」、論文が Science に掲載 — 難しい症例で正答率83%

Microsoft AI は2026年10月22日、複数の AI エージェントが医師団のように問診・検査の指示・議論を行って診断する **「MAI-DxO」** の研究が学術誌 **Science** に掲載されたと発表しました。同社によると、NEJM の複雑な症例では正答率 **83%** で、教科書やインターネットを使える医師の36%を上回り、検査を減らして費用も約2分の1〜3分の1に抑えたとしています。TechCrunch は、比較対象がプライマリケア医や総合内科医で、専門医やチームは含まれていない点や、改善の多くは基盤モデルの性能によるとみられる点を指摘しています。

**このニュースの影響**：医療機関にとっては、臨床判断を支援する AI の実用化に向けた検証が進む動きです。Microsoft は Mayo Clinic と医療向け基盤モデルを開発し、Beth Israel Deaconess Medical Center で患者が実際にシステムとやり取りする前向き研究も行うとしています。

**なぜ重要か**：Google や OpenAI も医師に匹敵・上回る性能を主張する中、Microsoft は Science 掲載の論文で同様の結果を示しました。

**キーワード**：`MAI-DxO` `医療AI` `マルチエージェント` `Microsoft AI` `Science`

出典：[Microsoft AI](https://microsoft.ai/news/building-medical-superintelligence/)、[TechCrunch](https://techcrunch.com/2026/10/22/microsofts-mustafa-suleyman-says-its-ai-outperforms-doctors-on-hard-cases-as-he-chases-medical-superintelligence/)

### Anthropic、「Agent Skills」の標準を Linux Foundation 傘下の団体に寄贈

Anthropic は2026年10月22日、AI エージェントに専門知識や手順を与える仕組み **「Agent Skills」** の標準を、Linux Foundation 傘下の **Agentic AI Foundation（AAIF）** に寄贈すると発表しました。スキルは SKILL.md というファイルと必要なスクリプトなどをまとめたフォルダで、ChatGPT、Cursor、GitHub Copilot、VS Code など **70以上** のプラットフォームが採用し、公開されたスキルは100万件、インストールは約2億8,000万件に達したとしています。

**このニュースの影響**：開発者にとっては、特定企業に依存しない形で標準が管理されるため、作ったスキルを複数のエージェントで使い回しやすくなることが考えられます。バージョン付きリリースや、スキルの作成・導入時のセキュリティ指針などを含むロードマップが提案されています。

**なぜ重要か**：MCP（Model Context Protocol）に続き、エージェント向けの標準が中立的な団体のもとで運営されることになります。

**キーワード**：`Agent Skills` `AAIF` `Linux Foundation` `オープン標準` `MCP`

出典：[Anthropic](https://www.anthropic.com/news/donating-agent-skills-to-the-agentic-ai-foundation)

### Google Cloud、OpenAI の「GPT-6 Astra」などを Model Garden で提供開始

Google Cloud は2026年10月21日（米国時間）、モデルカタログ「Model Garden」に OpenAI の **GPT-6 Astra、GPT-6.1 Sol、GPT-6 Luna** の3モデルを追加すると発表しました。まず一部の企業顧客向けのプライベートプレビューとして提供されます。同社は、主要3社のクローズドなモデルをすべて使える唯一のハイパースケーラー（大規模クラウド事業者）になったとしています。

**このニュースの影響**：企業は OpenAI のモデルの利用料を Google Cloud の請求に一本化でき、既存のクラウド利用契約の消化にも充てられます。入力や出力は顧客の指定範囲内に保持され、モデルの学習には使われないとしています。

**なぜ重要か**：主要なクラウド事業者が、競合するモデル企業のモデルも取りそろえる流れが進んでいます。

**キーワード**：`Google Cloud` `Model Garden` `GPT-6 Astra` `OpenAI` `マルチモデル`

出典：[Google Cloud Blog](https://cloud.google.com/blog/products/ai-machine-learning/google-cloud-brings-openai-models-to-customers?hl=en)、[ITmedia AI＋](https://www.itmedia.co.jp/aiplus/article/2610/22/2000002487/)

### Canva、初の自社製画像生成モデル「Canva Craft」を公開

デザインツールの **Canva** は、初の画像生成モデル **「Canva Craft」** を公開しました。写真ではなく、ポスターやプレゼン資料など Canva のテンプレートで学習しており、まず配置や大きさ、文字情報を計画してから、最大 **2K 解像度・30種類の縦横比** で画像を生成します。すべての利用者が「Dream Lab」タブから使え、API でも提供される予定です。

**このニュースの影響**：利用者は、読みやすい文字を含むデザイン画像を作り、レイヤー付きのデザインに変換して部分的に修正できます。Canva にとっては、外部の画像モデルへの支払いを減らせる可能性があります。

**なぜ重要か**：デザインデータを持つ企業が、自社のデータで特化型の生成モデルを作る例です。

**キーワード**：`画像生成` `Canva Craft` `Canva` `Leonardo.ai` `デザイン`

出典：[TechCrunch](https://techcrunch.com/2026/10/22/canva-releases-its-first-image-generation-model/)

### 1Password、パスワードを見せずに AI エージェントにログインさせる「1Password for Agents」

パスワード管理の **1Password** は2026年10月22日、AI エージェントが利用者の代わりにサイトへログインできる **「1Password for Agents」** を公開しました。エージェントが固有の鍵で身元を示し、利用者が通知を見て承認すると、1Password がログイン情報を入力するため、エージェント自身はパスワードを見ません。Claude Duet、OpenAI の Dots と ChatGPT Work、Meta の Muse などに対応するとしています。

**このニュースの影響**：利用者は、エージェントにパスワードを直接渡さずに作業を任せられるようになります。料金や提供地域は記事では示されていません。

**なぜ重要か**：エージェントに買い物や手続きを任せる場面が増える中で、認証情報の安全な受け渡しが課題になっています。

**キーワード**：`1Password` `AIエージェント` `認証` `パスワード管理` `セキュリティ`

出典：[TechCrunch](https://techcrunch.com/2026/10/22/1password-launches-a-way-for-ai-agents-to-log-in-on-your-behalf-without-seeing-your-password/)

### Uber、全社員約3万人に OpenAI の「ChatGPT Work」を導入

Uber と OpenAI は2026年10月22日に提携の拡大を発表し、Uber は世界の **約3万人** の全社員が OpenAI の業務向けエージェント **「ChatGPT Work」** を使えるようにしたと TechCrunch に明らかにしました。今年行った1,000人規模の試験導入では、早期利用者の約80%がエンジニア以外だったとしています。

**このニュースの影響**：大企業での全社展開の事例として、エンジニア以外の部門での業務 AI 活用の参考になります。導入費用は公表されていません。

**なぜ重要か**：TechCrunch は、OpenAI が Anthropic と競いながら企業向け事業を急速に拡大していると伝えています。

**キーワード**：`ChatGPT Work` `Uber` `OpenAI` `企業導入` `AIエージェント`

出典：[TechCrunch](https://techcrunch.com/2026/10/22/uber-puts-all-30000-employees-on-chatgpt-work/)

### チームみらい、AI を悪用したサイバー攻撃への緊急提言をデジタル庁に提出へ

チームみらい党首の **安野貴博氏** は2026年10月22日の定例会見で、相次ぐ情報漏えいや PHP の脆弱性などに触れ、今後は **電力・水道・医療** などの停止を伴う被害を想定すべきだと述べました。同党は「AIにはAIで、守りを固める」と題した緊急提言をまとめ、10月23日にデジタル大臣に提出する予定です。11月4日には専門家を招いた超党派の勉強会も開くとしています。

**このニュースの影響**：AI を使った攻撃への対策が国内の政策課題として議論される動きで、企業や自治体のセキュリティ対策にも関係する可能性があります。

**なぜ重要か**：AI による脆弱性発見や攻撃の増加を受け、国内でも政治の場で対応が求められ始めています。

**キーワード**：`サイバーセキュリティ` `チームみらい` `デジタル庁` `AI悪用` `政策提言`

出典：[ITmedia AI＋](https://www.itmedia.co.jp/aiplus/article/2610/22/2000002518/)

---

*この記事は Claude により公開情報をもとに自動生成されています。詳細・正確な情報は各出典をご確認ください。*
