# Clojure チュートリアル

Clojure による Web 開発の入門書

## 目次(TODO)

- [ ] はじめに
- [ ] 目次
- [ ] Clojure を学ぶことがなぜ重要なのか
- [ ] Clojure / ClojureScript 開発環境の構築
  - [ ] Windows における開発環境構築
  - [ ] Mac における開発環境構築
  - [ ] Linux における開発環境構築
- [ ] Clojure で遊んでみよう
  - [ ] Clojure Test Flight
    - [ ] フィボナッチ数列、バブルソートなど簡単なアルゴリズム書く
  - [ ] データ型の説明
  - [ ] アルゴリズムを書いてみる
    - [ ] quick sort
    - [ ] 階層のある flatten
    - [ ] 4clojure あたりから問題参考にしたい
- [ ] Duct でバックエンド環境構築、Duct の基礎説明
  - [ ] PostgreSQL 環境構築 (Docker 使うかどうか悩む...)
- [ ] Reagent、re-frame でフロントエンド構築、これらの基礎説明
  - [ ] CSS は stylefy を使う
- [ ] データベース設計・スキーマ作成
  - [ ] 画像投稿サイトのデータベース設計(ER 図)
  - [ ] Ragtime によるマイグレーション
- [ ] Firebase Authentication を用いた認証機能
  - [ ] Firebase のセットアップ
  - [ ] ログイン前後の画面構築
  - [ ] Firebase Emulator
- [ ] 画像投稿機能
  - [ ] REST API の説明
  - [ ] バックエンド作成
  - [ ] フロントエンド作成
  - [ ] CORS の説明
- [ ] 自分で投稿した画像の表示
- [ ] 他のユーザーの画像の表示
  - [ ] テストデータの投入
- [ ] ユーザーのフォロー・フォロワー
- [ ] 本番デプロイ
  - [ ] フロントエンドは Firebase Hosting
  - [ ] バックエンドは Heroku / CloudRun / DesitalOcean あたりのどれか (いずれにせよお金かかる)
- [ ] まとめ

## 執筆方法

```bash
npm install
npm run preview  # プレビューしながら執筆できます
npm run build    # PDF等を生成します
```

## license

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="クリエイティブ・コモンズ・ライセンス" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />この 作品 は <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">クリエイティブ・コモンズ 表示 - 継承 4.0 国際 ライセンス</a>の下に提供されています。
