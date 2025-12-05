---
marp: true
theme: saitogo
paginate: true

# Saitogo テーマ デモ
### 全機能サンプル

---

<!-- _class: title -->
<!-- _paginate: skip -->

# saitogo テーマ

全クラス & レイアウトのデモ

---

<!-- _class: section -->
<!-- _paginate: skip -->

## セクション（章区切り）

---

## h2 のボーダー

このスライドはデフォルトの本文・見出しスタイルを示します。強調や斜体、small などのテキスト要素もここで確認できます。

- **強調 (strong)** で重要な箇所を示す
- *斜体 (em)* を併用
- small は脚注や補足に最適

> 引用は blockquote スタイルで表示されます。

---

<!-- _class: content-image-right -->
## 右に画像（デフォルト 50%）

- 左にテキスト、右に画像を配置する基本パターン

Lorem ipsum dolor sit amet, consectetur adipiscing elit.

![プレースホルダ画像](https://placehold.jp/CCCCCC/ffffff/400x300.jpg?text=Sample%0AImage)

---

<!-- _class: content-image-right content-30 -->
## content-30 (テキスト30% / 右画像70%)

- テキストを狭め、画像を広めに表示します。

![大きい画像](https://placehold.jp/CCCCCC/ffffff/400x300.jpg?text=Sample%0AImage)

---

<!-- _class: content-image-right content-40 -->
## content-40 (テキスト40% / 右画像60%)

画像領域が少し狭くなっています。

![中くらいの画像](https://placehold.jp/CCCCCC/ffffff/400x300.jpg?text=Sample%0AImage)

---

<!-- _class: content-image-right content-60 -->
## content-60 (テキスト60% / 右画像40%)

テキストを多く見せたい場面に。

![小さめ画像](https://placehold.jp/CCCCCC/ffffff/400x300.jpg?text=Sample%0AImage)

---

<!-- _class: content-image-right content-70 -->
## content-70 (テキスト70% / 右画像30%)

よりテキスト寄りのレイアウト。

![小さい画像](https://placehold.jp/CCCCCC/ffffff/400x300.jpg?text=Sample%0AImage)

---

<!-- _class: content-image-right content-80 -->
## content-80 (テキスト80% / 右画像20%)

最もテキスト寄りの配置。

![アイコン的画像](https://placehold.jp/CCCCCC/ffffff/400x300.jpg?text=Sample%0AImage)

---

<!-- _class: content-image-left -->
## 左に画像（デフォルト 50%）

画像を左に置いたパターンも確認してください。

![左画像](https://placehold.jp/CCCCCC/ffffff/400x300.jpg?text=Sample%0AImage)

---

<!-- _class: content-image-left content-30 -->
## content-30（左画像 70% / テキスト 30%）

画像が左、テキストが右に来るパターンです。

![左大画像](https://placehold.jp/CCCCCC/ffffff/400x300.jpg?text=Sample%0AImage)

---

<!-- _class: content-image-left content-40 -->
## content-40（左画像 60% / テキスト 40%）

画像領域が少し狭くなっています。

![左中画像](https://placehold.jp/CCCCCC/ffffff/400x300.jpg?text=Sample%0AImage)

---

<!-- _class: content-image-left content-60 -->
## content-60（左画像 40% / テキスト 60%）

テキストを多く見せたい場面に。

![左小画像](https://placehold.jp/CCCCCC/ffffff/400x300.jpg?text=Sample%0AImage)

---

<!-- _class: content-image-left content-70 -->
## content-70（左画像 30% / テキスト 70%）

よりテキスト寄りのレイアウト。

![左小さい画像](https://placehold.jp/CCCCCC/ffffff/400x300.jpg?text=Sample%0AImage)

---

<!-- _class: content-image-left content-80 -->
## content-80（左画像 20% / テキスト 80%）

最もテキスト寄りの配置。

![左アイコン的画像](https://placehold.jp/CCCCCC/ffffff/400x300.jpg?text=Sample%0AImage)

---

<!-- _class: only-image -->
## 画像のみ

![フルサイズ画像](https://placehold.jp/222222/ffffff/1280x720.png?text=Only%20Image)

---

## 表（table）

| 項目 | 説明 |
|---:|:---|
| content-xx | テキスト幅を比率で制御 |
| p:has(img) | 画像を含む段落用のスタイル |

---

## インラインコードとコードブロック

: `const x = 10;`

```js
// ブロックコードの表示
function hello() {
  console.log('Hello, Saitogo theme!');
}
```

---

## 箇条書きとネストリスト

- 主要ポイント
  - サブポイント A
  - サブポイント B
- もうひとつのポイント

1. 主要ポイント
    1. サブポイント A
    1. サブポイント B
1. もうひとつのポイント

---

<!-- _class: title -->
<!-- _paginate: skip -->

## 以上 — テーマ全体のデモ終了
