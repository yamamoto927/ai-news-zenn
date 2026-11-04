---
title: "生成AIニュース 2026/11/05 その他まとめ：GoogleがAnthropic向けDCを信用補完、Kimi重み公開"
emoji: "🗞️"
type: "idea"
topics: ["ai", "生成ai", "llm", "news"]
published: false
---

## ニュース一覧

### Google、Anthropic が借りるケンタッキー州のデータセンターの賃料債務を一部保証

データセンター事業者の TeraWulf は11月4日、Google と **信用補完（クレジット・サポート）契約** を結んだと発表しました。対象は、ケンタッキー州ホーズビルの「Justified Data Campus」で Anthropic と結んだ **約190億ドル** の賃貸契約に関連する借入で、Anthropic の一部の支払い義務を Google が裏付ける形です。あわせて、建設大手 Fluor と3棟分の設計・調達・建設（EPC）契約も結び、2027年末ごろから2028年4〜6月期にかけて段階的に稼働を始める見込みとしています。

**このニュースの影響**：格付けの高い Google が支払いを裏付けることで、TeraWulf は資金調達の条件を有利にしやすくなると考えられます。Unite.AI によると、契約には施設で Google が承認した TPU を使う条件も含まれており、Anthropic の計算資源の確保に Google が深く関わっていることがわかります。

**なぜ重要か**：AI 向けデータセンターの建設資金を、大手クラウド企業の信用で支える仕組みが広がっていることを示す事例です。

**キーワード**：`TeraWulf` `Google` `Anthropic` `データセンター` `TPU`

出典：[TeraWulf プレスリリース（SEC 提出）](https://www.sec.gov/Archives/edgar/data/0001083301/000162828026069810/wulfhawesvillecsaandepcmpr.htm)／[Unite.AI](https://www.unite.ai/terawulf-lines-up-google-backstop-for-anthropics-kentucky-ai-campus/)

### Moonshot AI、「Kimi K3.1 Pro」の重みを Hugging Face で公開と報道

中国の Moonshot AI が、10月に発表した **「Kimi K3.1 Pro」の重み** を Hugging Face で公開したと報じられています。総パラメータ **2.8兆**・1トークンあたり 1040億パラメータが動く MoE（Mixture of Experts：複数の専門家ネットワークを使い分ける構造）で、約100万トークンの文脈長、テキストと画像の入力に対応します。重みは MXFP4 形式で配布され、ライセンスは独自の「Kimi K3.1 Pro License」です。

**このニュースの影響**：開発者は大規模なオープンウェイトモデルを自前の環境で動かしたり、調整したりできるようになります。ただし規模が非常に大きく、動かすには相応の GPU 資源が必要になると考えられます。

**なぜ重要か**：兆単位のパラメータを持つ高性能モデルの重み公開が続き、クローズドモデルとの選択肢の差が縮まりつつあります。

**キーワード**：`Moonshot AI` `Kimi K3.1 Pro` `オープンウェイト` `MoE` `Hugging Face`

出典：[Hugging Face：moonshotai/Kimi-K3.1-Pro](https://huggingface.co/moonshotai/Kimi-K3.1-Pro)／[Phemex News](https://phemex.com/news/article/moonshot-ai-opensources-kimi-k31-pro-weights-on-hugging-face-102388)／[The Next Web](https://thenextweb.com/news/moonshot-kimi-k3-1-pro-open-weight-cyber)

### AMD による AI チップ企業 Taalas の買収額は約29億ドル — 提出書類で判明

AMD が8月に発表していたカナダ・トロントの AI チップスタートアップ **Taalas** の買収について、11月4日の証券提出書類で **買収額が約29億ドル**（現金と株式）と明らかになりました。このうち14億ドルは条件付きの支払いで、買収は規制当局の承認などを経て完了する予定です。

**このニュースの影響**：AMD は Taalas の技術を将来の推論向けチップに組み込むとしており、AI 推論用ハードウェアの選択肢が広がる可能性があります。

**なぜ重要か**：NVIDIA が強い AI チップ市場で、AMD が買収を通じて推論分野の強化を急いでいることを示しています。

**キーワード**：`AMD` `Taalas` `AIチップ` `推論` `買収`

出典：[The Globe and Mail](https://www.theglobeandmail.com/business/article-amd-to-pay-29-billion-for-ai-chip-firm-taalas/)

### Uber、AI エージェント経由の配車予約は繁忙週にわずか4件

Uber は11月4日の決算説明会で、10月で最も忙しかったハロウィンの週に、AI エージェント経由の配車予約が **わずか4件**、Uber Eats の注文が **500件** だったと明かしました。同じ週の配車・注文の合計は約3億2000万件です。CEO の Dara Khosrowshahi 氏は「ごく初期で限定的」と述べつつ、今後の成長に期待を示しました。

**このニュースの影響**：AI エージェントによる買い物・予約は話題が先行しており、実際の利用はまだ小さいことがわかります。エージェント向けの機能を検討する企業にとって、現状を見極める材料になります。

**なぜ重要か**：先週の DoorDash に続き、大手サービスが AI エージェント経由の利用の少なさを具体的な数字で示しました。

**キーワード**：`Uber` `AIエージェント` `Uber Eats` `決算`

出典：[TechCrunch](https://techcrunch.com/2026/11/04/almost-no-one-uses-ai-agents-to-book-their-uber-company-says/)

### 米オハイオ州の住民投票、少なくとも14自治体でデータセンターの禁止・制限が可決

11月3日の米国の選挙で、オハイオ州では18自治体で21件のデータセンター関連の住民投票が行われ、**少なくとも14自治体** で禁止や制限が可決されたと Fortune が報じました。多くは25メガワット以上の大規模施設を対象としています。

**このニュースの影響**：AI 向けデータセンターの建設を計画する企業は、地域の反対による立地リスクをより重く見る必要が出てきます。

**なぜ重要か**：AI インフラの拡大が、電力や環境をめぐる地域の政治課題になっていることを示しています。

**キーワード**：`データセンター` `住民投票` `オハイオ州` `AIインフラ`

出典：[Fortune](https://fortune.com/2026/11/04/ohio-data-center-ballot-measures-midterm-elections/)

### OpenAI の政策責任者、2028年米大統領選を「AI 選挙」と位置づける論考を公開

OpenAI のグローバル渉外責任者 Chris Lehane 氏が、2028年の米大統領選を AI にとって決定的な場になりうるとする論考を同社の Substack で公開しました。労働者保護、教育、AI の安全性、データセンター開発などにわたる **5つの政策優先事項** を挙げています。TechCrunch は、拘束力のある施策が乏しいとする専門家の批判もあわせて伝えています。

**このニュースの影響**：AI 企業が次の大統領選を見据えて政策議論に積極的に関わる姿勢を示しており、今後の AI 規制の議論に影響する可能性があります。

**なぜ重要か**：中間選挙の直後に、主要 AI 企業が早くも次の選挙に向けた政策の主張を打ち出しました。

**キーワード**：`OpenAI` `AI政策` `米大統領選` `AI安全性`

出典：[TechCrunch](https://techcrunch.com/2026/11/04/openai-is-already-trying-to-shape-the-2028-election/)

### 国産 AI 開発の Noetra、Zenn でテックブログを開設

国内の大手企業が出資する AI 開発企業 **Noetra** が、11月4日に技術者向けプラットフォーム Zenn でテックブログを開設しました。AI 開発の取り組みや成果、開発現場での試行錯誤を開発者の視点で発信するとしており、最初の記事では画像エンコーダーを一から作った事例を紹介しています。

**このニュースの影響**：国産 AI の開発ノウハウが公開されることで、国内のエンジニアが具体的な手法を学べる機会が増えます。

**なぜ重要か**：国産 AI 開発の現場の情報発信が進むことは、国内の開発者コミュニティにとって参考になります。

**キーワード**：`Noetra` `国産AI` `Zenn` `画像エンコーダー`

出典：[ITmedia AI+](https://www.itmedia.co.jp/aiplus/article/2611/04/2000002886/)

---

*この記事は Claude により公開情報をもとに自動生成されています。詳細・正確な情報は各出典をご確認ください。*
