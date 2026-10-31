---
title: "生成AIニュース 2026/11/01 その他まとめ：ChatGPTの脆弱性、AI悪用の情報窃取、Ollie終了へ"
emoji: "🗞️"
type: "idea"
topics: ["ai", "生成ai", "llm", "news"]
published: false
---

## ニュース一覧

### ChatGPT の共有リンクで他人のアカウントを操作できる脆弱性、修正済み

セキュリティ企業 Parameter が、**ChatGPT の共有リンクを開くだけで攻撃者のコードが実行される**脆弱性を見つけ、OpenAI のバグ報奨金制度に報告していたと The Hacker News が10月31日に報じました。数式ライブラリ MathLive の処理など3つの弱点を組み合わせたもので、被害者のログイン状態のまま非公開の会話を読み出せたとされます。OpenAI は報告から8日後の **10月26日までに修正**し、報奨金 **5,000ドル**を支払いました。

**このニュースの影響**：修正済みで、利用者側の対応は不要とされています。研究者は実際の悪用は確認していないとしています。

**なぜ重要か**：AI チャットは会話に機密情報が含まれやすく、共有機能が攻撃の入り口になりうることを示した事例です。

**キーワード**：`ChatGPT` `脆弱性` `共有リンク` `バグバウンティ` `OpenAI`

出典：[The Hacker News：A Shared ChatGPT Link Could Run Attacker Code](https://thehackernews.com/2026/10/a-shared-chatgpt-link-could-run.html)

### 情報窃取マルウェア「VOLTA」、盗んだデータを LLM で分析し被害者を「値踏み」

Cisco の脅威研究チーム Talos は10月31日、Windows 向けの情報窃取マルウェア **VOLTA** を報告しました。盗んだパスワードや暗号資産ウォレットなどの情報を **LLM に送って、被害者の資産価値やセキュリティ意識を評価させる**機能を持ちます。既定では OpenRouter 経由で Claude のモデルを使い、拒否された場合は Kimi、Gemini の順に切り替える設定だったとしています。

**このニュースの影響**：セキュリティ担当者は、攻撃者が盗んだデータの分析に AI を使い、狙う相手を効率よく選ぶ手口に備える必要があります。

**なぜ重要か**：生成 AI が攻撃の「後工程」にも組み込まれ、技術力の低い攻撃者でも使える形で販売されていると Talos はみています。

**キーワード**：`インフォスティーラー` `Cisco Talos` `マルウェア` `OpenRouter` `LLM悪用`

出典：[Cisco Talos：Appraisal by AI: Model-driven victim prioritization in the VOLTA infostealer](https://blog.talosintelligence.com/appraisal-by-ai-model-driven-victim-prioritization-in-the-volta-infostealer/)

### プライバシー重視の AI アシスタント「Ollie」、11月6日にサービス終了

家族の予定管理などを手伝う AI アシスタント **Ollie** が、**11月6日にサービスを終了**すると、共同創業者兼 CEO の Bill Lennon 氏が10月30日に X で発表したと TechCrunch が報じました。Ollie はメールやカレンダーと連携し、プライバシー監査の基準 SOC 2 を取得していたとされ、9月には Khosla Ventures 主導で **750万ドル**を調達していました。Lennon 氏は、競合が増えるなかで成長と資金調達が追いつかなかったと説明しています。

**このニュースの影響**：利用者には、データの書き出しと返金の手順が案内される予定です。

**なぜ重要か**：競合が多い AI アシスタント市場で、資金調達直後のスタートアップでも撤退を迫られることを示しています。

**キーワード**：`AIアシスタント` `プライバシー` `SOC 2` `スタートアップ` `Khosla Ventures`

出典：[TechCrunch：Ollie, a privacy-focused AI assistant, is shutting down](https://techcrunch.com/2026/10/30/ollie-a-privacy-focused-ai-assistant-is-shutting-down/)

---

*この記事は Claude により公開情報をもとに自動生成されています。詳細・正確な情報は各出典をご確認ください。*
