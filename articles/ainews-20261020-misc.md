---
title: "生成AIニュース 2026/10/20 その他まとめ：AWSがTorchNeuron、OpenCodeで不正利用"
emoji: "🗞️"
type: "idea"
topics: ["ai", "生成ai", "llm", "news"]
published: false
---

## ニュース一覧

### AWS、PyTorch のコードをほぼそのまま Trainium で動かせる「TorchNeuron」を発表

Amazon は、自社の AI チップ **Trainium** 向けの PyTorch（AI 開発で広く使われるオープンソースのフレームワーク）バックエンド **「TorchNeuron」** を発表しました。設定を1か所変えるだけで、既存の PyTorch コードを書き直さずに Trainium2・Trainium3 で動かせるとしています。10月20日の PyTorch Conference North America で **Apache 2.0 ライセンスのオープンソース** として公開予定で、PyTorch 本体から特定チップへの依存を減らす変更も提供するとしています。

**このニュースの影響**：開発者は、NVIDIA の GPU 向けに書いた PyTorch のコードを AWS のチップへ移しやすくなる可能性があります。Hugging Face も同日、自社ツールで Trainium をネイティブに使えるようにしたと紹介しています。

**なぜ重要か**：TechCrunch は、NVIDIA の強みであるソフトウェア面の囲い込みに AWS が正面から挑む動きだと伝えています。

**キーワード**：`AWS` `Trainium` `PyTorch` `TorchNeuron` `オープンソース`

出典：[Amazon](https://www.aboutamazon.com/news/innovation-at-amazon/torchneuron-pytorch-aws-trainium-chips-ai)、[TechCrunch](https://techcrunch.com/2026/10/19/amazon-is-taking-its-biggest-shot-at-nvidia-yet-with-new-torchneuron-dev-tool/)、[Hugging Face](https://huggingface.co/blog/hf-torchneuron)

### AI コーディングツール OpenCode に不正侵入 — 利用者の API キーで高額請求も

オープンソースの AI コーディングエージェント **OpenCode** は、オンライン版「OpenCode Console」の旧システムに侵入され、**Console 利用者の1.4%** が影響を受けたと明らかにしました。Console には利用者が AI サービスの API キーを保存できる仕組みがあり、TechCrunch によると、一晩で数百ドル、合計で **1,000ドルを超える不正請求** を受けた開発者もいたと報告されています。オープンソースのアプリとコマンドラインツールは影響を受けていないとしています。

**このニュースの影響**：OpenCode から通知メールを受け取った利用者は、各 AI サービスで API キーを無効化して再発行し、利用額を確認する必要があります。Anthropic と Google は漏えいしたとみられるキーを無効化し、OpenAI は攻撃で消費されたクレジットを返金したと報じられています。

**なぜ重要か**：AI サービスの API キーを外部ツールに預けることのリスクが、実際の金銭被害として表れた事例です。

**キーワード**：`OpenCode` `APIキー` `不正アクセス` `AIコーディングエージェント` `セキュリティ`

出典：[TechCrunch](https://techcrunch.com/2026/10/19/hackers-hit-ai-coding-tool-opencode-running-up-charges-on-users-ai-accounts/)

### ChatGPT にスライド作成機能「ChatGPT Slides」

Impress Watch によると、OpenAI は ChatGPT でプレゼン資料を作れる **「ChatGPT Slides」** の提供を始めました。対象は **Pro・Business・Enterprise** プランです。チャットやファイル、アウトラインからスライドを生成し、テキストや図形、グラフを直接編集したり、チームでリアルタイムに共同編集したりできます。PowerPoint、PDF、Google スライド形式で書き出せます。

**このニュースの影響**：対象プランの利用者は、資料の下書きから共同編集、書き出しまでを ChatGPT 上で進められるようになります。

**なぜ重要か**：チャット AI が、文書作成だけでなくプレゼン資料という業務の定番成果物まで直接扱う流れを示しています。

**キーワード**：`ChatGPT` `ChatGPT Slides` `OpenAI` `プレゼン資料` `共同編集`

出典：[Impress Watch](https://www.watch.impress.co.jp/docs/news/2149226.html)

### AI コンパニオンアプリの Tolan、3,000万ドルを調達

キャラクターとの会話を通じて日々の用事や人間関係、気持ちの整理を手助けする AI コンパニオンアプリ **Tolan** が、**3,000万ドル** を調達しました。Union Square Ventures、Khosla Ventures、Homebrew が出資しています。アクティブユーザーは **25万人超**、過去1年の会話数は7,000万件を超えるとしています。

**このニュースの影響**：有料会員制の AI コンパニオンが一定の収益を上げていることを示し、同分野への投資判断の材料になります。

**なぜ重要か**：Character.AI の破産申請があった一方で、別の形の AI コンパニオンには資金が集まっていることを示しています。

**キーワード**：`Tolan` `AIコンパニオン` `資金調達` `消費者向けAI`

出典：[TechCrunch](https://techcrunch.com/2026/10/19/tolan-snags-30m-for-its-ai-companion-that-helps-users-navigate-life/)

### ロボットや自動運転車をシミュレーションで「攻撃テスト」する Laplace Intelligence

米ミシガン大学発のスタートアップ **Laplace Intelligence** は、ロボットや自動運転車、スマートシティのシステムを、実環境に出す前にシミュレーション上で自動的に **レッドチーミング**（攻撃者の視点で弱点を探すテスト）するプラットフォームを提供しています。NVIDIA の世界モデル「Cosmos」を追加学習したシミュレーションを使い、AI エージェントがニュースや警察の報告書などから、めったに起きない難しい状況を作り出します。顧客には米国の自動運転トラック企業や **日本の大手自動車メーカー** が含まれるとしています。

**このニュースの影響**：自動運転やロボットの開発企業にとって、実環境では再現しにくい危険な状況を事前に検証する手段の一つになります。

**なぜ重要か**：生成 AI やシミュレーションを、物理世界で動く AI（フィジカル AI）の安全性検証に使う動きの一例です。

**キーワード**：`Laplace Intelligence` `レッドチーミング` `自動運転` `NVIDIA Cosmos` `フィジカルAI`

出典：[TechCrunch](https://techcrunch.com/2026/10/19/laplace-intelligence-red-teams-robots-and-self-driving-cars-before-they-hit-the-real-world/)

---

*この記事は Claude により公開情報をもとに自動生成されています。詳細・正確な情報は各出典をご確認ください。*
