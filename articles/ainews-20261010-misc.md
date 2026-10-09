---
title: "生成AIニュース 2026/10/10 その他まとめ：ChatGPT音声ファイル対応、Claude Dashboards、損保ジャパン"
emoji: "🗞️"
type: "idea"
topics: ["ai", "生成ai", "llm", "news"]
published: false
---

## ニュース一覧

### ChatGPT、音声ファイルのアップロードに対応 — 文字起こし・要約が可能に

ITmedia AI+ や Impress Watch が10月9日に報じたところによると、**OpenAI** の ChatGPT で **音声ファイルを添付して文字起こし・要約・内容への質問** ができるようになりました。対象は有料ユーザーで、WAV、MP3、FLAC、M4A などに対応し、1ファイルの上限は **512MB** です。長時間の録音は分割処理されたりタイムアウトしたりする場合があり、文字起こしや話者の識別に誤りが含まれる可能性があると説明されています。

**このニュースの影響**：有料ユーザーは、会議や講義の録音を別のツールで文字起こしせずに ChatGPT へ直接渡して要約できるようになります。

**なぜ重要か**：チャット AI が扱える入力の種類が広がり、音声の議事録作成などの用途で専用ツールと競合する場面が増えると考えられます。

**キーワード**：`ChatGPT` `OpenAI` `文字起こし` `音声認識` `マルチモーダル`

出典：[ITmedia AI+：ChatGPT、ついに音声ファイルに対応](https://www.itmedia.co.jp/aiplus/article/2610/09/2000002182/)、[Impress Watch：ChatGPT、音声アップロードに対応](https://www.watch.impress.co.jp/docs/news/2147136.html)

### Anthropic、データに連動する「Claude Dashboards」と解説動画を作る「Claude Motion」をベータ公開

**Anthropic** は10月8日（米国時間）、BigQuery や Snowflake、Salesforce などに接続して最新の状態を保つダッシュボードを作る **「Claude Dashboards」**（有料プラン）と、プロンプトから短い解説アニメーションを作り MP4 で書き出せる **「Claude Motion」**（Team/Enterprise）をベータ版で公開しました。Motion は動画生成モデルを使わず、動きをコードとして生成する仕組みです。あわせて Claude の Docs、Slides、Design がベータを終え、Free を含む全プランで使えるようになりました。

**このニュースの影響**：企業のデータ担当者は、自然言語の質問から更新され続けるダッシュボードを作れるようになります。Enterprise の管理者は、Dashboards と Motion が既定で無効（組織設定の Artifacts で有効化）である点に注意が必要です。

**なぜ重要か**：チャット AI が文章の生成にとどまらず、BI ツールや資料作成ツールの領域に広がっていることを示す発表です。

**キーワード**：`Claude` `Anthropic` `ダッシュボード` `BI` `データ可視化`

出典：[Claude（公式）：Dashboards and Motion](https://claude.com/ja/resources/articles/dashboards-and-motion)、[Impress Watch：Claudeに新機能「ダッシュボード」　プレゼン動画「Motion」も](https://www.watch.impress.co.jp/docs/news/2147180.html)

### 損保ジャパン、約2万人の「Gemini Enterprise」利用をどう管理しているか

ITmedia（キーマンズネット）は、**損害保険ジャパン** が2026年1月に約 **2万人** を対象に導入した「Gemini Enterprise」の運用を紹介しました。AI リテラシーテストの合格者だけを利用者として登録し、人事名簿と研修合格者名簿を毎日自動で突き合わせて権限を更新しているほか、「Model Armor」でプロンプトと回答を検査しています。2026年6月時点で、平日の DAU（日次利用者の割合）は **50%超**、WAU（週次）は約80%だということです。

**このニュースの影響**：生成 AI を全社導入する企業にとって、利用者の認定や監視、社員によるエージェント作成の統制など、ガバナンスの具体例として参考になります。

**なぜ重要か**：国内の大手企業が、数万人規模で生成 AI を安全に運用するための仕組みを公開している事例です。

**キーワード**：`損保ジャパン` `Gemini Enterprise` `AIガバナンス` `市民開発` `Google Cloud`

出典：[キーマンズネット（ITmedia）：損保ジャパン、2万人の「Gemini活用」どう管理？](https://kn.itmedia.co.jp/kn/article/2610/09/2000002145/)

### Magnific（旧 Freepik）、ブランド規定に沿って画像を作る「Magnific One」を公開

画像生成サービスの **Magnific**（旧 Freepik）は、プロンプトや参照画像を解釈してから生成する画像生成機能 **「Magnific One」** を公開しました。ブランドのガイドラインから「Brand Kit」を作り、生成時にルールを適用して出力のずれも確認できます。VentureBeat によると、同社は基盤に **OpenAI の GPT Image 2** を使っているとブリーフィングで説明したと報じられています。

**このニュースの影響**：マーケティングやデザインのチームは、ブランドの色やルールに沿った画像をまとめて試作しやすくなる可能性があります。

**なぜ重要か**：画像生成 AI の競争が、画質だけでなく企業のブランド管理への対応にも広がっています。

**キーワード**：`画像生成` `Magnific` `GPT Image 2` `ブランドキット` `Freepik`

出典：[VentureBeat：Magnific One launches to give teams an image generator that avoids the 'AI look'](https://venturebeat.com/orchestration/magnific-one-launches-to-give-teams-an-image-generator-that-avoids-the-ai-look-and-automatically-upholds-their-brand-kit)

### トランプ大統領、「Artificial Intelligence」を使う者は「敵」と投稿 — AI.gov のロゴは「SI GOV」に

ITmedia NEWS によると、**トランプ米大統領** は10月8日（米国時間）、SNS「Truth Social」で「Artificial Intelligence」ではなく「Super Intelligence」を使うべきだとし、前者を使う者を **「敵」** と見なすと投稿しました。具体的な措置は示されていません。連邦政府の AI 政策サイト「AI.gov」は、10月9日時点でロゴが **「SI GOV」** に変わっています。

**このニュースの影響**：9月29日の大統領令で連邦行政機関に「SI」表記が命じられているため、今後の米政府の資料では用語の違いに注意が必要になる可能性があります。

**なぜ重要か**：9月の大統領令に続き、米政府が AI を指す呼称の変更を強く打ち出していることを示しています。

**キーワード**：`Super Intelligence` `AI.gov` `米国政府` `AI政策` `トランプ政権`

出典：[ITmedia NEWS：トランプ米大統領、「AI」という言葉を使う者は「敵」](https://www.itmedia.co.jp/news/article/2610/09/2000002157/)

### AI キャラクターとの会話に没頭した人は1年後も依存が強い傾向 — スタンフォード大などが追跡調査

ITmedia NEWS によると、米 **スタンフォード大学** や **カーネギーメロン大学** などの研究者が、AI キャラクターとチャットできる「Character.AI」の利用者を約1年追跡した研究を arXiv で公開しました。初回調査は **1,182人**、約12か月後の追跡調査は **439人** です。初期に強く関わっていた人ほど1年後も依存が強く、持続的な深い関わりは1年後の幸福度の低下を予測し、その一因として対面での交流の減少が示唆されたとしています。

**このニュースの影響**：AI コンパニオンを提供する企業や利用者にとって、長期利用が人間関係や幸福度に与える影響を考える材料になります。

**なぜ重要か**：AI との長期的な関係が人に与える影響を、同じ利用者を追跡して調べた研究です。

**キーワード**：`AIコンパニオン` `Character.AI` `スタンフォード大学` `追跡調査` `arXiv`

出典：[ITmedia NEWS：“AIキャラチャット”に没頭した人の予後、スタンフォード大などが1年の追跡調査](https://www.itmedia.co.jp/news/article/2610/09/2000002121/)

---

*この記事は Claude により公開情報をもとに自動生成されています。詳細・正確な情報は各出典をご確認ください。*
