# Gyliardson Keitison | ソフトウェア開発・業務自動化

<div align="center">
  <img src="profile-banner.jpg" alt="Gyliardson Keitison | Software Developer & Process Automation" width="100%">
</div>

<div align="center">
  <a href="README.md">English</a> · <a href="README.pt-BR.md">Português</a> · <a href="README.es.md">Español</a> · <strong>日本語</strong>
</div>

> この翻訳版は、海外の方にもプロフィールを読みやすくするために用意しています。各言語版が存在することは、その言語を業務レベルで話せることを意味しません。

## 自己紹介

私は、**業務プロセスの自動化、Full Stack アプリケーション、応用AIを中心に取り組むソフトウェア開発者**です。主に **Python、JavaScript/TypeScript、React/Next.js、FastAPI、Node.js、PostgreSQL、Docker** を使い、設計から運用まで一貫したソリューションを開発しています。

業務では、ソフトウェアエンジニアリングと業務効率化の接点にある課題を扱うことが多く、社内システム、企業向けAPI連携、文書処理、RPA、ダッシュボード、AI支援ワークフロー、ローカル／プライベート環境でのLLM活用などに取り組んでいます。

現在の業務では、アーキテクチャ設計、実装、デプロイ、監視、保守、インフラまで開発サイクル全体を担当しており、大規模な文書取り込み、OCR振り分け、RAGパイプライン、SharePoint同期、財務業務の自動化、Docker環境、CI/CDなどを扱っています。

<div align="center">
  <h3>コード以外も見てみませんか？</h3>
  <p>プロジェクトやライブデモを通して、私がどのようにソフトウェアを開発しているかご覧いただけます。</p>
  <a href="https://gyliardson.github.io/gyliardson/">
    <img src="https://img.shields.io/badge/View_Portfolio-238636?style=for-the-badge&logo=github&logoColor=white" alt="ポートフォリオを見る">
  </a>
</div>

## 主な技術スタック

`Python` · `TypeScript` · `JavaScript` · `React` · `Next.js` · `Node.js` · `FastAPI` · `PostgreSQL` · `Supabase` · `Docker` · `GitHub Actions` · `Linux`

**応用AI:** RAG · OCR · LLM連携 · Gemini · Ollama · LangChain · ローカルAIワークフロー

## GitHubでの活動

<div align="center">
  <img src="assets/stats/stats-ja.svg" width="420" alt="GyliardsonのGitHubでの活動">
  <img src="assets/stats/languages-ja.svg" width="420" alt="Gyliardsonのリポジトリでよく使われる言語">
</div>

<p align="center"><sub>公開されているGitHub上の活動と、リポジトリ内の言語構成を表示しています。言語の使用量は習熟度を示すものではありません。</sub></p>

## 主なプロジェクト

### MangaSensei
**ローカルファーストの日本語マンガ学習ワークスペース**

元のマンガ画像を保持したまま、OCRと決定論的な言語解析をローカルで実行する、プライバシー重視の読書・学習アプリです。React製リーダー、FastAPI、PostgreSQLキュー、ワーカー処理、Sudachi/JMdict、任意のGemini連携、Docker Compose、Full Stackテスト、CI、セキュリティ／プライバシー境界を備えています。

`React` · `FastAPI` · `PostgreSQL` · `Docker` · `OCR` · `Sudachi` · `JMdict` · `Gemini`

[**ソースコード**](https://github.com/Gyliardson/mangasensei)

---

### L'Mere Studio
**製菓店向けマルチテナントSaaS**

顧客向けの複数ステップ注文シミュレーターと、商品管理、注文Kanban、店舗ごとのブランド設定を行える管理CMSを備えたホワイトラベル型プラットフォームです。

`Next.js` · `TypeScript` · `React` · `TailwindCSS` · `Prisma`

[**デモ**](https://lmere-studio.vercel.app) · [**動画**](https://youtu.be/XpgxfHBhJoI)

---

### Little Mere News
**AIで自動化されたテクノロジーニュースポータル**

Pythonによる情報収集、LLMによる要約・翻訳、Next.jsの公開サイトとCMS、Supabase/PostgreSQL、ローカル＋クラウドのバッチ処理を組み合わせたバイリンガルニュースプラットフォームです。

`Next.js` · `Python` · `Supabase` · `Llama 3` · `Docker`

[**デモ**](https://little-mere-news.onrender.com/en) · [**ソースコード**](https://github.com/Gyliardson/little-mere-news)

---

### FinanceFlow
**財務管理・自動化・OCR**

FastAPIバックエンド、React Nativeアプリ、Supabase/PostgreSQL、領収書OCR、AIによるインサイト、通知、オフライン対応、自動デプロイを備えた財務管理システムです。

`Python` · `FastAPI` · `React Native` · `Supabase` · `Gemini` · `Docker`

[**ソースコード**](https://github.com/Gyliardson/FinanceFlow)

---

### StudyFlash AI
**AIを使ったアクティブラーニングプラットフォーム**

学習コンテンツをLLMで構造化されたフラッシュカードへ変換するFull Stackアプリです。認証、リレーショナルデータ保存、分離されたフロントエンド／バックエンド構成を採用しています。

`Next.js` · `FastAPI` · `Clerk` · `Supabase`

[**デモ**](https://studyflash-ai.vercel.app/)

---

### Smart Feedback API
**AIによるサポートチケット分類API**

サポートチケットの感情分析、カテゴリ分類、優先度判定、構造化JSON出力、ローカルLLM実行を行うRESTマイクロサービスです。

`Python` · `FastAPI` · `Docker` · `Ollama` · `Pydantic`

[**ソースコード**](https://github.com/Gyliardson/smart-feedback-api)

---

### Local RAG Assistant
**オフライン文書アシスタント**

PDFをローカル環境で安全に分析するアプリです。チャンク分割、Embedding、ベクトル検索、参照元付き回答、ローカルLLM推論を実装しています。

`Python` · `LangChain` · `Streamlit` · `ChromaDB` · `Ollama`

[**ソースコード**](https://github.com/Gyliardson/local-rag-assistant)

## 得意・関心のある領域

- 業務プロセス自動化・RPA
- 社内システム・B2Bダッシュボード
- REST API・企業向けシステム連携
- 文書取り込み、OCR、セマンティック検索、RAG
- ローカルファースト／プライベートAI
- Docker、CI/CD、実用重視のインフラ構成

## 連絡先

<div align="center">
  <a href="https://linkedin.com/in/gyliardson-keitison">LinkedIn</a> ·
  <a href="https://gyliardson.github.io/gyliardson/">Portfolio</a> ·
  <a href="mailto:gyliardson@outlook.com">Email</a>
</div>
