# NoteLyn AI

<p dir="ltr"><a href="README.md">English</a> · <a href="README.de.md">Deutsch</a> · <a href="README.fr.md">Français</a> · <a href="README.zh-TW.md">繁體中文</a> · <a href="README.ko.md">한국어</a> · <a href="README.pt.md">Português</a> · <strong>日本語</strong> · <a href="README.es.md">Español</a> · <a href="README.it.md">Italiano</a> · <a href="README.ar.md">العربية</a> · <a href="README.pl.md">Polski</a> · <a href="README.he.md">עברית</a></p>

**講義や学習資料を、実際に役立つノートに変えましょう。**

NoteLynは、録音、PDF、ドキュメント、写真、リンクを構造化されたノートに変換するAIノートツールです。重要なアイデアを確認したり、フラッシュカードやクイズで練習したり、マインドマップを見たり、同じノートについて質問したりできます。

復習したい講義、理解したい資料、フォローアップが必要なミーティングなどを持ってきてください。

**[無料で最初のノートを作成する →](https://app.notelyn.com/)** · [講義のサンプルノートを見る](https://www.notelyn.com/ja/samples/lecture)

**Web · iOS · Android** | **新規アカウントは無料のAIノートが2件 · クレジットカード不要**

[ウェブサイト](https://www.notelyn.com/ja) · [App Store](https://apps.apple.com/app/id6747017579) · [Google Play](https://play.google.com/store/apps/details?id=com.studyai.ainotetaker)

![サンプルノート、フラッシュカード、クイズを表示しているNoteLyn AIの製品概要](images/product-overview.png)

*画像は製品およびウェブサイトのデザイン例であり、説明用です。サンプルのコンテンツ、スコア、残高はデモ用のものです。実際のアプリでは、レイアウトや上限が異なる場合があります。*

このリポジトリには、NoteLynの利用開始ガイド、実践的なワークフロー、プロンプト、テンプレートがまとめられています。

<a id="is-notelyn-right-for-you"></a>

## NoteLynはあなたに向いていますか?

次のような場合はNoteLynをお試しください。

- **手元の資料を、そのまま学習セッションにしたい。** 録音、資料、ノートの写真、字幕付きのYouTube講義から始められます。
- **覚える必要があることを練習したい。** 要約から、同じ資料に基づくフラッシュカードやクイズ問題へと進めます。
- **一つのトピックをさまざまな方法で学びたい。** ノートを読み、マインドマップを見て、同じワークスペースで質問できます。

初めて試すときは、短い録音や、よく知っているPDFを選んでみてください。要約が主要なアイデアを捉えているか、練習問題が復習に役立つか、行き詰まったときに回答が有用かを確認しましょう。

<a id="create-your-first-note-in-three-steps"></a>

## 3つのステップで最初のノートを作成する

1. **資料を1つ用意する。** [ウェブアプリ](https://app.notelyn.com/)またはモバイルアプリを開いてサインインし、資料に応じて録音、アップロード、リンクインポートを選びます。
2. **ノートを確認する。** 要約と重要な概念を読みましょう。重要な名前、用語、数値、結論は元の資料と照らし合わせて確認してください。
3. **次のステップを選ぶ。** フラッシュカードを生成したり、クイズを受けたり、マインドマップを確認したり、ノートについて質問したりできます。次回のためにノートブックに保存しておきましょう。

**[自分の資料で試す →](https://app.notelyn.com/)**

まずは閲覧したい場合は、[講義のサンプルノートを開いてください](https://www.notelyn.com/ja/samples/lecture)。サンプルの閲覧にアカウントは必要ありません。

<a id="in-this-guide"></a>

## このガイドの内容

- [NoteLynはあなたに向いていますか?](#is-notelyn-right-for-you)
- [3つのステップで最初のノートを作成する](#create-your-first-note-in-three-steps)
- [保存した講義から復習セッションまで](#from-a-saved-lecture-to-a-review-session)
- [用途に合ったシーンを探す](#find-your-use-case)
- [各ノートでできること](#what-you-can-do-with-each-note)
- [手元の資料から始める](#start-with-the-material-you-already-have)
- [ワークスペースを探る](#explore-the-workspace)
- [ワークフローに合うツールを比較する](#compare-tools-for-your-workflow)
- [試してみたいプロンプトとテンプレート](#prompts-and-templates-to-try)
- [よくある質問](#frequently-asked-questions)
- [フィードバックとサポート](#feedback-and-support)

<a id="from-a-saved-lecture-to-a-review-session"></a>

## 保存した講義から復習セッションまで

試験前に講義の録音を聞き直す場面を想像してください。主要なアイデアを把握し、覚えているかどうかを確認でき、分かりにくい部分の手助けも欲しいところです。

NoteLynのノートを中心に、次のような復習の流れを組み立てられます。

1. **全体を把握する。** 要約と重要な概念を読み、その後、重要な詳細を録音またはコース資料と照らし合わせて確認します。
2. **記憶から答えてみる。** フラッシュカードと選択式クイズを生成します。まず自分で答えてから、解説を読みましょう。
3. **分からない部分を埋める。** 分かりにくい概念をAIに質問し、マインドマップでその概念が全体の話題とどう関係しているかを確認します。

同じ資料を、読み、質問し、練習できるものに変えられます。形式を確認するには[サンプルノートを見てみてください](https://www.notelyn.com/ja/samples/lecture)。このサンプルは使い勝手のイメージを示すもので、結果はお使いの資料によって異なります。

<a id="find-your-use-case"></a>

## 用途に合ったシーンを探す

| 取り組んでいること | NoteLynでできること |
| --- | --- |
| **講義や試験の範囲** | 録音やスライドをノートにして、フラッシュカードやクイズで練習する |
| **PDF、資料、研究論文** | 要点を確認し、難しい箇所について質問し、概念を図にまとめる |
| **YouTubeの授業** | 字幕付きの動画をノートにして、復習し質問できるようにする |
| **ミーティングや面接** | 録音の文字起こしと要約を確認し、フォローアップを整理して、ノートを共有する |

<a id="what-you-can-do-with-each-note"></a>

## 各ノートでできること

| 機能 | 役立つこと |
| --- | --- |
| **構造化されたノートと要約** | 主要なアイデアと重要な概念の整理された概要から始められる |
| **音声の文字起こし** | 対応している録音の内容を、ノートと並べて見返せる |
| **フラッシュカード** | 答えを表示する前に、思い出す練習ができる |
| **解説付きクイズ** | 選択式問題で理解度を確認し、答えが正しい理由を振り返れる |
| **マインドマップ** | 話題がばらばらに感じるとき、概念同士の関係を把握できる |
| **ノートについてのAIチャット** | より平易な説明を求めたり、アイデアを比較したり、特定の箇所を一緒に考えたりできる |
| **インフォグラフィック** | ノートの重要なアイデアを、ダウンロードできる1ページのビジュアル要約にできる |
| **ポッドキャスト** | ノートについて2人のホストが話すエピソードを聴ける。Proの機能で、クレジットを使用する |
| **ノートブック** | 同じ講義、科目、プロジェクトの資料をまとめて保管できる |
| **閲覧専用の共有** | アカウントがなくても、ブラウザで開けるノートのリンクを送れる |

NoteLynはウェブ、iOS、Androidで利用でき、資料を取り込む場所や復習する場所に合わせて使えます。

<a id="start-with-the-material-you-already-have"></a>

## 手元の資料から始める

| 資料 | 用意するもの |
| --- | --- |
| **ライブ録音** | 録音する許可を得ている講義、ミーティング、面接 |
| **音声ファイル** | 文字起こしをしてノートにしたい既存の録音 |
| **PDFまたはWordドキュメント** | コースの読み物、スライド、その他のドキュメント |
| **画像** | ノートやスライドの写真 |
| **テキスト** | 整理して復習したい文章 |
| **ウェブまたはYouTubeのリンク** | 公開されているウェブページや、字幕付きのYouTube動画 |

各ノートは1つの資料から始まります。講義の録音とそのスライドを扱う場合は、それぞれ別々のノートを作成し、同じノートブックに保存してください。対応している形式やファイルの上限はアプリに表示されます。

<a id="explore-the-workspace"></a>

## ワークスペースを探る

録音から復習セッションまでの流れをたどってみましょう。画像を選択すると、原寸で開きます。

| **資料を取り込む** | **整理されたノートを得る** |
| --- | --- |
| 既存の録音をアップロードし、ノートブックを選択します。 | 見出し、要点、まとめを確認します。 |
| <a href="images/capture-upload-audio.webp"><img src="images/capture-upload-audio.webp" alt="ノートブックの選択画面を含む音声アップロードダイアログのNoteLyn Webデザイン例" width="360"></a> | <a href="images/ai-note-view.webp"><img src="images/ai-note-view.webp" alt="見出しと重要なまとめを含む構造化ノートのNoteLyn Webデザイン例" width="360"></a> |

| **フラッシュカードで練習する** | **理解度を確認する** |
| --- | --- |
| 答えを思い出してから、カードをめくって確認します。 | クイズに答え、その解答の解説を読みます。 |
| <a href="images/flashcards-deck.webp"><img src="images/flashcards-deck.webp" alt="質問と「カードをめくる」ボタンを含むフラッシュカードのNoteLyn Webデザイン例" width="360"></a> | <a href="images/quiz.webp"><img src="images/quiz.webp" alt="正解と不正解、解説を含むクイズのNoteLyn Webデザイン例" width="360"></a> |

| **アイデア同士をつなげる** | **分かりにくい点を質問する** |
| --- | --- |
| 主要な概念をマインドマップで確認します。 | 開いているノートの概念について、AIに質問します。 |
| <a href="images/mind-map-view.webp"><img src="images/mind-map-view.webp" alt="つながった概念とズームコントロールを含むマインドマップのNoteLyn Webデザイン例" width="360"></a> | <a href="images/ai-chat-panel.webp"><img src="images/ai-chat-panel.webp" alt="現在のノートの横で質問に答えるAIチャットのNoteLyn Webデザイン例" width="360"></a> |

| **資料を聴く** | **ビジュアルで見直す** |
| --- | --- |
| 2人のホストによるポッドキャストのエピソードを生成します。Proプランとポッドキャスト用のクレジットが必要です。 | 見直したりダウンロードしたりできる1ページのインフォグラフィックを生成します。 |
| <a href="images/podcast-episode.webp"><img src="images/podcast-episode.webp" alt="再生コントロールを含むポッドキャストエピソードプレーヤーのNoteLyn Webデザイン例" width="360"></a> | <a href="images/infographic-poster.webp"><img src="images/infographic-poster.webp" alt="共有とダウンロードのコントロールを含むビジュアル要約ポスターのNoteLyn Webデザイン例" width="360"></a> |

現在の形式やプランの詳細は、[NoteLynの機能ガイド](https://www.notelyn.com/ja/features)をご覧ください。

<a id="compare-tools-for-your-workflow"></a>

## ワークフローに合うツールを比較する

ツールを比較していますか?まずは、資料をどのように取り込み、どのように復習したいかから考えてみてください。以下のグループは、2026年10月17日に確認した公式の製品説明をまとめたものです。出力品質のランキングではありません。

<a id="study-recall-and-source-based-research"></a>

### 学習、暗記、資料に基づく調査

| ツール | 公式に説明されているワークフロー | NoteLynと比較する点 |
| --- | --- | --- |
| **[NoteLyn](https://www.notelyn.com/ja/features)** | 録音、ドキュメント、画像、テキスト、対応しているリンクをノートにして、フラッシュカード、クイズ、マインドマップ、インフォグラフィック、ポッドキャスト、チャットを使えます。 | 自分の資料で、取り込みから復習までの流れを試してみてください。各ノートは1つの資料から始まります。ポッドキャストはProとクレジットが必要です。 |
| **[Gemini Notebook / NotebookLM](https://support.google.com/gemininotebook/answer/16179559?hl=en)** | ノートブックの資料を選んで質問し、出典付きの回答を得られます。[学習ツール](https://support.google.com/gemininotebook/answer/16958963?hl=en)にはフラッシュカードやクイズが含まれます。 | 資料の選択、複数の資料をまたいだ作業、回答を引用元までたどれるかどうか。 |
| **[Quizlet](https://help.quizlet.com/hc/en-us/articles/360030841732-Studying-on-Quizlet)** | フラッシュカードや練習アクティビティで学習したり、アップロードしたノートを学習ガイドや練習テストに変換したりできます。 | 練習の形式、既存の学習セット、生成された問題が学びたい内容にどれだけ合うか。 |
| **[Coconote](https://coconote.app/)** | 録音やアップロードをノート、文字起こし、チャット、フラッシュカード、クイズ、学習ゲーム、ポッドキャストに変換します。 | 同じ資料を使って、学習の体験、取り込みのオプション、現在のプランの制限を比較する。 |

<a id="digital-notebooks-and-workspaces"></a>

### デジタルノートとワークスペース

| ツール | 公式に説明されているワークフロー | NoteLynと比較する点 |
| --- | --- | --- |
| **[Notion AI](https://www.notion.com/help/ai-meeting-notes)** | ワークスペースのページで作業を管理し、AI Meeting Notesで文字起こし、要点、アクションアイテムを作成します。 | ノートの周りに、より広いワークスペースがどの程度必要か。ミーティングの取り込みオプションとプランの対象かどうかを確認してください。 |
| **[Goodnotes](https://www.goodnotes.com/ai)** | 手書きや文書で作業し、AI検索、要約、手書きからテキストへの変換ツール、生成されたクイズを使えます。 | 学習の中で手書きや書き込みのある資料がどの程度を占めるか、また、プランにどのAIツールが含まれるか。 |
| **[Notability](https://notability.com/)** | 手書きまたは入力したノートを、音声の文字起こし、AIの要約、クイズ、フラッシュカードと組み合わせられます。 | ノートの書き方と録音のやり方、そしてそのノートを復習教材にどれだけ自然に変えられるか。 |

<a id="meeting-assistants"></a>

### ミーティングアシスタント

| ツール | 公式に説明されているワークフロー | NoteLynと比較する点 |
| --- | --- | --- |
| **[Otter](https://help.otter.ai/hc/en-us/articles/4425393298327-Otter-Notetaker-Overview)** | カレンダーを連携させ、Notetakerに Zoom、Google Meet、Teamsのミーティングに参加させて、録音、文字起こし、要約を行います。 | カレンダー連携と、ミーティングの自動取り込み。NoteLynでは、ご自身が開始する録音またはアップロードから始まります。 |

フラッシュカード、クイズ、AIチャット、ミーティングの要約は、複数のツールで利用できます。**資料を取り込み、書かれたノート、ビジュアル要約、質問、練習の間を、同じノートのワークスペースで行き来したい場合はNoteLynをお試しください。** 機能はプラン、プラットフォーム、アカウントによって異なります。選ぶ前に、現在の提供状況を確認してください。

<a id="prompts-and-templates-to-try"></a>

## 試してみたいプロンプトとテンプレート

これらのプロンプトは、現在のノートのAIチャットで使う提案です。テンプレートは、ご自身の学習記録やミーティング記録にコピーして使えるプレーンテキストです。

<a id="understand-a-difficult-concept"></a>

### 分かりにくい概念を理解する

> このノートの[概念]を、分かりやすい日本語で説明してください。簡単な例を挙げてから、理解を確認するための質問を1つ私にしてください。

<a id="prepare-for-a-review-session"></a>

### 復習セッションの準備をする

> このノートを学習した後に、答えられるようになっておくべき質問を5つ提案してください。主要な概念に焦点を当て、関連するセクションも示してください。

<a id="clarify-meeting-follow-ups"></a>

### ミーティングのフォローアップを明確にする

> このノートに明示的に書かれている決定事項とフォローアップのタスクを一覧にしてください。担当者と期限は、書かれている場合のみ含めてください。記載がないものは「未指定」と表示してください。

結果を利用したり共有したりする前に、元の資料と照らし合わせて確認してください。

<details>
<summary><strong>授業後の復習テンプレートをコピーする</strong></summary>

```text
コース / トピック:
日付:
NoteLynノートのリンク:

説明できるようになるべき3つの概念:
1.
2.
3.

自分の言葉での説明:

まだ理解できていないこと:

元の資料で確認する場所:

フラッシュカードやクイズで間違えた問題:

次回の復習で見直すこと:
```

</details>

<details>
<summary><strong>ミーティングのフォローアップテンプレートをコピーする</strong></summary>

```text
ミーティング:
日付:
NoteLynノートのリンク:

確定した決定事項:

フォローアップのタスク:
- タスク:
- 担当者（または「未指定」）:
- 期限（または「未指定」）:

未解決の質問:

録音と照らし合わせて確認した詳細:
```

</details>

<a id="frequently-asked-questions"></a>

## よくある質問

<details>
<summary><strong>NoteLynはNotebookLMとどう違いますか?</strong></summary>

NoteLynは、対応している録音、ドキュメント、画像、テキスト、リンクを、要約、フラッシュカード、クイズ、マインドマップを備えた個別のノートに変換します。[GoogleのGemini Notebook / NotebookLM](https://support.google.com/gemininotebook/answer/16179559?hl=en)では、ノートブックの資料を選んで質問し、出典付きの回答を得られます。また、[学習ツール](https://support.google.com/gemininotebook/answer/16958963?hl=en)も利用できます。資料の整理方法、回答を資料と照らし合わせる方法、ご自身が好む復習の進め方を比較してください。

</details>

<details>
<summary><strong>NoteLynはQuizletとどう違いますか?</strong></summary>

NoteLynは、録音と対応しているインポートを、構造化されたノート、フラッシュカード、クイズ、マインドマップ、現在のノートに関する質問と組み合わせます。[Quizlet](https://help.quizlet.com/hc/en-us/articles/360030841732-Studying-on-Quizlet)は、フラッシュカードのセット、学習アクティビティ、コース資料から生成された学習ガイドや練習テストを提供します。どちらも練習に対応しています。資料の取り込み方、整理の仕方、学習セッションでの使い方を比較してください。

</details>

<details>
<summary><strong>NoteLynは無料で試せますか?</strong></summary>

はい。[NoteLynでは現在](https://www.notelyn.com/ja/features)、新規アカウントに無料のAIノート2件を提供しており、クレジットカードは不要です。ノートの作成にはアカウントが必要です。最新の利用枠、有料プラン、料金はアプリでご確認ください。ポッドキャストはProの機能で、クレジットを使用します。

</details>

<details>
<summary><strong>字幕のないYouTube動画をインポートできますか?</strong></summary>

YouTubeリンクのインポートは動画の字幕を使うため、字幕のない動画はこの方法では処理できません。利用可能な音声ファイルがある場合は、代わりに音声アップロードを選んでください。

</details>

<details>
<summary><strong>録音とスライドを1つのノートにまとめられますか?</strong></summary>

各ノートは1つの資料から始まります。録音とスライドはそれぞれ別のノートを作成し、同じノートブックにまとめてください。

</details>

<details>
<summary><strong>AIチャットは何についての質問に答えますか?</strong></summary>

AIチャットは、開いているノートを基に回答します。概念の説明、アイデアの比較、分かりにくい箇所の説明、復習問題の提案などを依頼できます。特定の用語やセクションを指定すると、焦点を絞った回答が得られます。

</details>

<details>
<summary><strong>共有したノートを開くのに、相手がアカウントを必要としますか?</strong></summary>

いいえ。閲覧専用のリンクは、サインインせずにブラウザで開けます。受信者は元のノートを編集できません。リンクを共有する前に、内容を確認してください。

</details>

<details>
<summary><strong>ノートをファイルとして書き出せますか?</strong></summary>

現在、ノートのファイル書き出しは利用できません。閲覧専用のリンクを使ってノートを共有できます。個々のコンテンツ形式のダウンロードオプションは、アプリに表示されます。

</details>

<details>
<summary><strong>AIが生成した内容は確認すべきですか?</strong></summary>

はい。名前、用語、数値、日付、重要な結論は、元の資料と照らし合わせて確認してください。授業の課題に使う場合は、コースの資料で答えを確認してください。

</details>

<details>
<summary><strong>このリポジトリにはアプリのソースコードが含まれていますか?</strong></summary>

このリポジトリには、ガイド、プロンプト、テンプレートのみが含まれています。NoteLynのアプリとウェブサイトのソースコードは含まれていません。

</details>

<a id="feedback-and-support"></a>

## フィードバックとサポート

このガイドに誤りを見つけた場合や、ワークフローの提案がある場合は、このリポジトリでIssueを作成し、背景と改善してほしい内容をお知らせください。

アカウント、サブスクリプション、個別のサポートについては、[support@notelyn.com](mailto:support@notelyn.com)までメールでお問い合わせください。パスワード、支払い情報、非公開のノートの内容は、公開のIssueに書き込まないでください。

**講義、ドキュメント、録音の準備はできていますか?[NoteLynのノートを作成して、復習セッションを試す →](https://app.notelyn.com/)**

[ブログのその他のガイド](https://www.notelyn.com/ja/blog) · [プライバシーポリシー](https://www.notelyn.com/ja/privacy-policy) · [利用規約](https://www.notelyn.com/ja/terms-of-service)
