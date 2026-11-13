---
title: "生成AIニュース 2026/11/14 その他まとめ：M365障害でAIコネクタ停止、llama.cpp v1.0"
emoji: "🗞️"
type: "idea"
topics: ["ai", "生成ai", "llm", "news"]
published: false
---

## ニュース一覧

### Microsoft 365 で大規模障害 — Copilot や ChatGPT・Claude の M365 コネクタにも影響

Microsoft の Outlook や Teams で始まった障害が世界に広がり、**Microsoft 365 Copilot** などの AI ツールも使いにくい状態になりました。ITmedia AI＋によると、日本時間11月13日午前の時点で、OpenAI と Anthropic も **ChatGPT・Claude の Microsoft 365 コネクタが正常に動作していない** と報告していました。TechCrunch によると、Microsoft は原因を明らかにしていないものの、多数のサーバーが予期せず利用できなくなったと説明し、サイバー攻撃や AI エージェントとは関係ないとしています。

**このニュースの影響**：Microsoft 365 のデータを ChatGPT や Claude から使う業務は、M365 側の障害で止まることがあります。利用企業は、AI ツールが外部サービスに依存している部分を把握しておく必要があると考えられます。

**なぜ重要か**：AI アシスタントが業務システムとつながるほど、接続先のクラウド障害の影響を受ける範囲が広がることを示しました。

**キーワード**：`Microsoft 365` `Microsoft 365 Copilot` `コネクタ` `クラウド障害` `Claude for Outlook`

出典：[ITmedia AI＋](https://www.itmedia.co.jp/aiplus/article/2611/13/2000003164/)、[TechCrunch](https://techcrunch.com/2026/11/13/microsoft-latest-email-outage-turned-into-a-full-blown-global-cloud-crisis/)

### ローカル推論の llama.cpp が v1.0.0 に — API 互換性のルールを明確化

ローカル環境で LLM を動かすための C/C++ ライブラリ **llama.cpp（libllama）** と、テンソル計算ライブラリ **ggml（libggml）** が、そろって **v1.0.0** になりました。今後は公開 C API に互換性のない変更があるときにメジャーバージョンを上げる、セマンティックバージョニング（変更の種類で版番号の上げ方を決める方式）に従います。プロジェクトは約3年半で、**150以上のモデルアーキテクチャ** に対応しているとしています。

**このニュースの影響**：llama.cpp を組み込んだアプリを開発するエンジニアは、版番号を見て破壊的な変更の有無を判断しやすくなります。

**なぜ重要か**：ローカル AI の基盤となるライブラリが、安定した API を前提に使える段階に入ったことを示しています。

**キーワード**：`llama.cpp` `ggml` `ローカルLLM` `セマンティックバージョニング` `Hugging Face`

出典：[Hugging Face Blog](https://huggingface.co/blog/ggml-org/llama-cpp-v1)

### Meta の AI エージェント「Muse」、米国の店舗や企業へ電話をかける機能を有料会員に提供

Meta は、AI エージェント **Muse** が利用者の代わりに **米国の企業へ電話をかける機能** を、有料会員向けに提供し始めました。9月から一部の利用者で試験していた機能です。Muse の料金は **月20ドル（週5億トークン）** から、利用量の多い人向けに月100ドルのプランもあります。

**このニュースの影響**：米国の有料会員は、保険会社やオンライン予約のないレストランへの問い合わせなどを Muse に任せられるようになります。

**なぜ重要か**：AI エージェントが Web 上の操作だけでなく、電話という現実の窓口にも対応範囲を広げています。

**キーワード**：`Meta` `Muse` `AIエージェント` `音声通話` `有料プラン`

出典：[TechCrunch](https://techcrunch.com/2026/11/12/muse-can-now-place-calls-to-u-s-businesses-if-you-pay/)

### Nebius、2027年の設備投資を400億ドル規模に — Microsoft 向け設備は遅れ

AI 向けクラウドの Nebius は第3四半期決算で、**2027年に400億〜450億ドル** の設備投資を行う計画を示しました。四半期売上は **9億8,100万ドル（前年同期比571%増）** でしたが、外部の運営会社が手がける拠点の遅れを理由に、2026年の売上見通しを2億ドル下げて30億ドルとしました。TechCrunch によると、株価は17%下落して取引を終えました。

**このニュースの影響**：GPU クラウドの供給が、データセンターの建設や電力の確保に左右されることを示す事例で、AI 計算資源の調達を考える企業には参考になります。

**なぜ重要か**：AI インフラへの巨額投資が続く一方で、建設の遅れが事業者の業績見通しに直接響く局面に入っています。

**キーワード**：`Nebius` `ネオクラウド` `データセンター` `設備投資` `Microsoft`

出典：[TechCrunch](https://techcrunch.com/2026/11/12/nebius-tests-the-neocloud-playbook-with-40-billion-in-planned-spending/)

### 中国の主要オープンモデルに Nvidia Blackwell で学習した痕跡があると分析

元 OpenAI の研究者 Will DePue 氏が、中国企業が公開したモデルの重みを分析し、Moonshot AI の **Kimi K3** と DeepSeek の **V4** に、**中国への輸出が禁止されている Nvidia の Blackwell GPU** で学習した特徴が見られると指摘しました。TechCrunch は、これだけでは全体を Nvidia 製チップで学習したことや、輸出規制に違反したことの証明にはならない（国外のデータセンターを使った可能性もある）としています。

**このニュースの影響**：米国の半導体輸出規制の実効性をめぐる議論に、新たな材料を加える可能性があります。

**なぜ重要か**：公開されたモデルの重みから、学習に使われたハードウェアを推定しようとする試みとして注目されます。

**キーワード**：`Nvidia Blackwell` `輸出規制` `DeepSeek` `Kimi` `オープンウェイト`

出典：[TechCrunch](https://techcrunch.com/2026/11/13/export-banned-nvidia-chips-are-behind-chinas-most-powerful-ai-models-uh-oh-jensen/)

### ElevenLabs、会議メモと音声入力をまとめたチーム向けアプリ「ElevenAI」を試験提供

音声 AI の ElevenLabs は、**会議の記録と音声入力（ディクテーション）を1つにまとめた試験的なアプリ「ElevenAI」** を発表しました。過去の会議をまたいで内容を検索でき、音声入力は **90以上の言語** に対応します。現在はプレビュー段階で、早期アクセスへの登録が必要です。

**このニュースの影響**：企業は、会議の文字起こしツールと音声入力ツールを別々に契約せずに済む可能性があります。

**なぜ重要か**：音声 AI の専業企業が、業務アプリの領域に直接乗り出す動きです。

**キーワード**：`ElevenLabs` `ElevenAI` `音声認識` `議事録` `ディクテーション`

出典：[TechCrunch](https://techcrunch.com/2026/11/13/elevenlabs-new-app-combines-meeting-note-taking-and-dictation-for-teams/)

### C-RISE、AI が書いた kintone のコードを本番導入前に調べる無料診断を提供開始

サイボウズのパートナー企業 **C-RISE** は、kintone 向けの JavaScript を本番導入前に確認できる **無料のコード診断サービス** を始めました。社内で書いたコードのほか、**AI が生成したコード** や外部プラグインも対象で、結果は「要対応」「要確認」などに分けて示されます。キーマンズネットによると、1組織あたり月10回まで診断でき、アップロードしたファイルは最大7日後に自動削除され、AI の学習には使われません。

**このニュースの影響**：AI でアプリのカスタマイズを作る国内の kintone 利用企業は、導入前の安全確認を手軽に行えるようになります。

**なぜ重要か**：AI によるコード生成が業務部門に広がるなか、生成されたコードの検証が新しいニーズになっています。

**キーワード**：`kintone` `C-RISE` `AI生成コード` `コード診断` `サイボウズ`

出典：[キーマンズネット（ITmedia）](https://kn.itmedia.co.jp/kn/article/2611/13/2000003159/)

---

*この記事は Claude により公開情報をもとに自動生成されています。詳細・正確な情報は各出典をご確認ください。*
