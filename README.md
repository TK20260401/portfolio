# ポートフォリオ — KIKUCHI, Toru

> **課題解決型のプロダクトエンジニア** / 教育現場16年 → ソフトウェア開発へ

現場で「課題を見つけ、仕組みで解決する」ことを16年続けてきました。その視点を活かし、ユーザーの困りごとを **実際に動くプロダクト** として形にしています。企画・要件定義から実装・デプロイ・運用までを一人で一気通貫で進められることが強みです。

- 🎯 **志望**: 自社開発企業のエンジニア（フロントエンド〜フルスタック）
- 🧭 **得意**: 課題発見 → 要件定義 → UX設計 → 実装 → 運用までの一気通貫
- ♿ **こだわり**: アクセシビリティ・ユニバーサルデザイン・セキュリティ・ドキュメント文化

---

## 🛠 技術スタック

| 分類 | 技術 |
| :-- | :-- |
| 言語 | TypeScript / JavaScript / SQL |
| フロントエンド | React 19 / Next.js (App Router) / Tailwind CSS / shadcn/ui |
| バックエンド | Supabase (PostgreSQL / Auth / Row Level Security / Edge Functions) |
| AI | Anthropic Claude API |
| モバイル | React Native / Expo |
| インフラ / 運用 | Vercel (CI/CD) / GitHub |
| 設計ドキュメント | 要件定義書・ER図・UX監査・マイグレーション設計 |

---

## ⭐ 代表プロダクト — おてつだいバンク

子供向けの「お手伝い × マネー教育」アプリ。お手伝いをRPGのクエストに見立て、稼いだお金を **「つかう／ためる／ふやす」** の3つに分けて、楽しみながらお金の使い方を学べます。

[🔗 ライブデモ](https://otetsudai-bank-beta.vercel.app) ・ [📁 リポジトリ](https://github.com/TK20260401/otetsudai-bank)

**主な機能**
- 3役認証（管理者／保護者／子供＝PIN）・保護者ダッシュボードでのタスク管理と承認
- ウォレットの3分割（つかう／ためる／ふやす）と貯金ゴール・達成バッジ
- 株式ポートフォリオ・シミュレーター（日経225／S&P500 等の14銘柄）
- AIアドバイザー（子供向け／保護者向け／ガイドの3モード、Claude API）
- RPG要素（レベル・ペット育成・ダンジョンバトル）でモチベーション設計
- ユニバーサルデザイン（色＋アイコン併用・ふりがな・大きいタップ領域、WCAG AA水準）

**技術・設計のポイント**
- Next.js 16 (App Router) / React 19 / TypeScript / Tailwind / shadcn/ui
- Supabase 15テーブルに **Row Level Security** を全面適用、PINは **bcrypt** でハッシュ化
- 子供向けサービスゆえの **COPPA / GDPR を意識したプライバシー設計**
- 実装規模 約96コミット、v0.1→v0.22 まで反復開発。要件定義・ER図・UX監査をドキュメント化

---

## 📦 プロジェクト一覧

| プロジェクト | 概要 | 主な技術 | リンク |
| :-- | :-- | :-- | :-- |
| **otetsudai-bank** | 子供向けお手伝い×マネー教育アプリ（代表作） | Next.js / Supabase / Claude API | [Demo](https://otetsudai-bank-beta.vercel.app) ・ [Repo](https://github.com/TK20260401/otetsudai-bank) |
| **zensho-algo** | 全商情報処理検定 アルゴリズム完全攻略トレーナー。擬似言語の変数トレース・フローチャート変換 | TypeScript / Next.js | [Repo](https://github.com/TK20260401/zensho-algo) |
| **team-signage** | チーム状況をリアルタイム共有するデジタルサイネージ（在席管理・営業カレンダー・リソース可視化） | TypeScript / Next.js | [Repo](https://github.com/TK20260401/team-signage) |
| **20260401-Project-Blueprint (ISLOS構想)** | 複数の学習アプリを束ねる学習プラットフォーム「IT-Skills Learning OS」の設計・構想 | TypeScript / 設計ドキュメント | [Demo](https://20260401-one.vercel.app) ・ [Repo](https://github.com/TK20260401/20260401-Project-Blueprint) |
| **report-hub** | 日報／週報／月報を一元管理し、業務効率と知見を蓄積するハブ | TypeScript / Next.js | [Demo](https://report-hub-one.vercel.app) ・ [Repo](https://github.com/TK20260401/report-hub) |
| **asset-management-ledger** | QRコード対応の資産管理台帳。更新アラート・操作ログ・権限管理 | TypeScript / Next.js | [Repo](https://github.com/TK20260401/asset-management-ledger) |
| **roi-simulator** | 売上計画とROIを即時試算・複数プラン比較 | HTML / JS | [Demo](https://roi-simulator-delta.vercel.app) ・ [Repo](https://github.com/TK20260401/roi-simulator) |
| **ai-strategy-agent** | AIを活用した戦略立案支援エージェント | TypeScript | [Repo](https://github.com/TK20260401/ai-strategy-agent) |
| **universal-games** | 誰でも楽しめるアクセシブルなゲーム集（あそびひろば） | TypeScript / Expo | [Repo](https://github.com/TK20260401/universal-games) |
| **otetsudai-quest-mobile** | おこづかいクエストのモバイル版 | React Native / Expo | [Repo](https://github.com/TK20260401/otetsudai-quest-mobile) |
| **clock** | NHK風時計アプリ（アナログ時計＋天気＋タイマー） | HTML / CSS / JS | [Repo](https://github.com/TK20260401/clock) |
| **tetris-games** | ブラウザで遊べるテトリス | HTML / JS | [Demo](https://tetris-games-six.vercel.app) ・ [Repo](https://github.com/TK20260401/tetris-games) |

### 🚧 開発中 / 構想中
- **簿記・ビジネス会計トレーナー** — 仕訳→試算表→精算表→決算書の自動採点、決算整理、財務分析12指標、CVP・損益分岐点、減価償却、株式指標、ドリル、進捗ダッシュボードを備えた学習アプリ。現在 **デスクトップアプリ版・Webアプリ版** を計画中（教育現場での自作教材が原型）。

---

## 🧩 設計・品質で意識していること

- **アクセシビリティ / ユニバーサルデザイン**: 色＋アイコンの併用、ふりがな、キーボード操作、WCAG AA を意識した配色・コントラスト
- **セキュリティ**: Supabase の Row Level Security、認証情報のハッシュ化、子供向けサービスのプライバシー配慮（COPPA / GDPR）
- **ドキュメント文化**: 要件定義書・ER図・UX監査・マイグレーション設計を残し、後から入る人が理解できる状態を保つ
- **反復開発**: 小さくリリースして改善を重ねる（otetsudai-bank は v0.1→v0.22 まで継続）

---

## 👤 経歴サマリ

- 教育現場で **16年間** 勤務。現場の課題を起点に、学習用の自作ツールを多数開発。
- その経験をソフトウェアエンジニアリングに展開し、Web／モバイル／AI を組み合わせたプロダクトを継続的に制作。
- 「教える側」だった視点を活かし、**使う人が迷わないUX** と **学びを支える仕組み** づくりを重視。

---

## 📫 連絡先

GitHub のプロフィール・Issue 経由でご連絡ください。

<!-- 個人アカウントへコピーする際: 必要に応じてメール／SNS等の連絡先をここに追記してください -->