<img src="./images/baboo_cover.png" />

<div align="center">
  <div>
    <img src="https://img.shields.io/badge/Next.js-000?style=for-the-badge&logo=nextdotjs&logoColor=fff" alt="Next.js" />
    <img src="https://img.shields.io/badge/React-61dafb?style=for-the-badge&logoColor=000&logo=react" alt="React" />
    <img src="https://img.shields.io/badge/Vercel-000?style=for-the-badge&logo=vercel&logoColor=fff" alt="Vercel" />
    <img src="https://img.shields.io/badge/TypeScript-3178c6?style=for-the-badge&logo=typescript&logoColor=fff" alt="TypeScript" />
    <img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=fff" alt="Tailwind CSS" />
    <img src="https://img.shields.io/badge/shadcn%2Fui-000?style=for-the-badge&logo=shadcnui&logoColor=fff" alt="shadcn/ui" />
    <img src="https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=fff" alt="ESLint" />
    <img src="https://img.shields.io/badge/Prettier-F7B93E?style=for-the-badge&logo=prettier&logoColor=000" alt="Prettier" />
    <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=fff" alt="PostgreSQL" />
    <img src="https://img.shields.io/badge/CockroachDB-6933FF?style=for-the-badge&logo=cockroachlabs&logoColor=fff" alt="CockroachDB" />
    <img src="https://img.shields.io/badge/Clerk-6C47FF?style=for-the-badge&logo=clerk&logoColor=fff" alt="Clerk" />
    <img src="https://img.shields.io/badge/Inngest-000?style=for-the-badge&logo=dependabot&logoColor=fff" alt="Inngest" />
    <img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=fff" alt="Google Gemini" />
    <img src="https://img.shields.io/badge/Brave%20Search%20API-FB542B?style=for-the-badge&logo=brave&logoColor=fff" alt="Hugging Face" />
  </div>

  <h3 align="center">CONVERSATIONAL AI SEARCH APP</h3>

  <div align="center">
    リアルタイム AI 検索回答アプリ
  </div>
</div>

## 📋 <a name="table">もくじ</a>

1. 🤖 [はじめに](#intro)
2. 🔗 [URL](#url)
3. 😮‍💨 [Baboo の概要](#description)
4. 🔋 [AI 検索回答アプリの機能](#feature)
5. 🚀 [アプリの利用サンプル](#example)
6. 💻 [画面サンプル](#screen_sample)
7. 🤸 [終わりに](#outro)

## <a name="intro">🤖 はじめに</a>

AI との自然な会話を通じて、あなたの知りたい情報をすばやく見つけることができる会話型 AI 検索アプリ、**Baboo** をご紹介します。

## <a name="url">🔗 URL</a>

Baboo | CONVERSATIONAL AI SEARCH APP    
https://baboo-nu.vercel.app

---

## <a name="description">😮‍💨 Baboo の概要</a>

**Baboo（バブー）** は、AI を活用した対話型の検索エンジンアプリです。従来の検索エンジンとは異なり、自然言語での質問に対して AI が理解し、リアルタイムで最適な回答を提供します。
おもな特徴や機能は以下の通りです。

### おもな特徴

#### 🥳 対話型 AI 検索

ユーザーが自然な言葉で質問すると、AI が文脈を理解して最適な回答を生成します。
従来のキーワード検索ではなく、会話するような感覚で情報を取得できます。

#### 👯 最新の検索技術との連携

Brave Search API を利用することで、ウェブ上の最新かつ関連性の高い情報を取得し、AI がそれを要約・整理して提示します。これにより、情報の網羅性と正確性を両立しています。

#### 💾 過去の検索履歴を保存

あなたの検索履歴を保存し、いつでも見返すことができます。これにより、以前調べた内容を簡単に確認したり、会話を再開したりすることが可能です。

#### 🤹‍♀️ 想定される利用シーン

- 特定のトピックについて深く掘り下げて知りたいとき
- 複雑な情報をわかりやすく要約してほしいとき
- アイデア出しやブレインストーミングのパートナーとして
- 日々の疑問をすぐに解決したいとき

#### 🔨 技術的背景

Google Gemini を利用した高度なテキスト生成能力と、Brave Search API によるリアルタイムのウェブ検索機能を組み合わせています。これにより、AI が最新の情報を取得し、ユーザーの質問に対して質の高い回答を生成します。

フロントエンドと API は、Next.js を使った Web アプリ構成です。
タスク実行のクラウドジョブ管理には Inngest を使用しています。

- フロントエンド/バックエンド: Next.js, React, TypeScript
- UI: Tailwind CSS, shadcn/ui
- 認証: Clerk
- データベース: PostgreSQL, CockroachDB
- AI (LLM): Google Gemini
- 検索API: Brave Search API
- ジョブ管理: Inngest
- コード品質: ESLint, Prettier

#### まとめ

**Baboo（バブー）** は、AI との会話を通じて情報を検索できる、次世代の検索体験を提供する無料の Web サービスです。自然な言葉で質問するだけで、AI が最新のウェブ情報を基に的確な回答を生成し、あなたの疑問を素早く解決します。

---

## <a name="feature">🔋 会話型 AI 検索アプリの機能</a>

### 🏠 検索への入口

- ランディングページ

### ユーザ認証機能

- 🗝️ ログイン
- 🔐 ログアウト

### 📡 リアルタイム検索処理

- 検索ワードまたは疑問を自由入力
- Brave Search API を用いたソース収集
- 引用ソース付きの回答表示
- 関連情報の提示

### 🤖 AI 要約生成

- Gemini による要約と補足説明
- 非同期処理による応答最適化

### ライブラリ管理

- ユーザーごとの検索履歴保存
- AI とのやりとりをスレッド形式で管理

### 🌐 ニュース探索機能

- 最新のニュース記事やブログを取得
- トピック（IT / サイエンス / 教育など）の選択 UI

---

## <a name="example">🚀 アプリの利用サンプル</a>

##### 検索デモ
<!-- ./images/baboo_demo.mp4 -->
<video src="https://github.com/user-attachments/assets/4117b3bd-8628-4857-93fa-62c17fab7810" controls="true"></video>

---

## <a name="screen_sample">💻 画面サンプル</a>

### 検索への入口

#### ランディングページ 

<img src="./images/landing.png" width="360px" />

### ユーザ認証機能

#### ログイン

<img src="./images/login.png" width="360px" />

#### ログアウト

<img src="./images/logout.webp" width="360px" />

### 対話型検索機能
#### 🚶 メイン検索画面
<img src="./images/baboo_main_search.webp" width="360px" style="border: 1px solid #777;" />

#### 🔍 質問入力
<img src="./images/baboo_question_input.webp" width="360px" />

#### 🌐 検索結果表示
<img src="./images/baboo_search_results.png" width="360px" />

#### 🪶 AI 回答生成
<img src="./images/baboo_ai_response.png" width="360px" />

#### 🎨 参考情報表示
<img src="./images/baboo_reference_info.png" width="360px" />

#### 🧑‍🎨 会話履歴
<img src="./images/baboo_conversation_history.png" width="360px" />

### 履歴画面
#### 🧑 ログイン認証
<img src="./images/baboo_history_auth.png" width="360px" />

#### 🧑‍🎨 会話履歴一覧表示
<img src="./images/baboo_history_list.png" width="360px" />

#### 🚋 過去の会話への移動
<img src="./images/baboo_move_to_old_conversation.webp" width="360px" />

---

## <a name="outro">🤸 おわりに</a>

今回は、Google Gemini と Brave Search API を組み合わせることで、ユーザーがより自然に、そして効率的に情報にアクセスできる会話型 AI 検索アプリ Baboo を作成しました。

信頼性の高い情報を簡潔に得たいユーザー、トピックを深堀りしたい学習者や研究者、そして情報収集効率を高めたいすべての人におすすめのアプリです。

将来的には、マルチエージェント機能や音声検索など、よりインタラクティブな機能拡張も検討中です。
