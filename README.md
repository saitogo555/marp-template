
# Marp theme template — saitogo

このリポジトリはMarp用のカスタムテーマテンプレート(`saitogo`)です。

Marp CLI を使ってHTML / PDF / PPTX などにビルドできるように設定されています。

## 主要ファイル

- `sample.md` — テーマの全機能サンプル (見出し・画像・コードブロック・テーブルなど)
- `theme.css` — Marpカスタムテーマ

## セットアップ

1. 依存関係をインストールする。

    ```bash
    npm install
    ```

1. プレビューを見る。

    ```bash
    npm run serve
    ```

## ビルド

成果物は`dist/`に出力されます。

```bash
# すべてビルド
npm run build:all

# 個別ビルド
npm run build:html   # → dist/sample.html
npm run build:pdf    # → dist/sample.pdf
npm run build:pptx   # → dist/sample.pptx
```

> ⚠️ 注意 ⚠️
>
> PDF や PPTX を生成するためには内部でヘッドレスブラウザ（Chromium）が必要になります。Debian / Ubuntu 系の環境では以下のコマンドでインストールできます。

```bash
sudo apt-get install -y chromium
```

## ライセンス

[MIT LICENSE](https://opensource.org/license/mit)
