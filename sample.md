---
marp: true
theme: saitogo
paginate: true
---

<!-- _class: title -->
<!-- _paginate: false -->

# Marpカスタムテーマ サンプル

## saitogoテーマのプレビュー

2025年12月9日最終更新

---

<!-- _class: section -->
<!-- _paginate: false -->

## セクションタイトル

各セクションのタイトル用スライドとして使用する

---

## H2 見出し (スライドタイトル)

### H3 見出し

#### H4 見出し

##### H5 見出し

###### H6 見出し

---

## テキストスタイル

これは通常の段落テキストです。Noto Sans JPフォントが適用され、読みやすい行間が設定されています。

**強調テキスト**はアクセントカラー（青）で表示されます。

*イタリックテキスト*も使用できます。

***強調イタリック***を組み合わせることもできます。

---

## 見出しの強調表示

### H3の**強調**表示

#### H4の**強調**表示

##### H5の**強調**表示

###### H6の**強調**表示

---

## リストスタイル

### 箇条書きリスト

- 項目1
- 項目2
  - ネストされた項目
  - ネストされた項目2
- 項目3

### 番号付きリスト

1. 最初の項目
2. 2番目の項目
   1. ネストされた番号付き
   2. ネストされた番号付き2
3. 3番目の項目

---

## コードスタイル

インラインコード: `const message = "Hello, World!";`

### コードブロック

```javascript
function greet(name) {
  console.log(`Hello, ${name}!`);
  return true;
}

greet("Marp");
```

```python
def fibonacci(n):
    if n <= 1:
        return n
    return fibonacci(n-1) + fibonacci(n-2)
```

---

## 引用とリンク

### 引用（Blockquote）

> これは引用文です。左側に紫色のボーダーが表示され、
> イタリック体で表示されます。

### リンク

[Marp公式サイト](https://marp.app/)にアクセスしてください。

通常のテキストと[リンクテキスト](https://example.com)を混在させることができます。

---

## テーブルスタイル

| 項目 | 説明 | 値 |
|------|------|-----|
| フォントサイズ | 本文 | 1.75rem |
| 行間 | 通常 | 1.3 |
| アクセント | 青 | oklch(70.7% 0.165 254.624) |
| 背景 | ベース | #ffffff |

---

<!-- _class: only-image -->

## 画像のみレイアウト

![](https://picsum.photos/1200/600)

---

<!-- _class: content-image-right content-70 -->

## 右画像30% + コンテンツ70%

コンテンツ領域を広くとるレイアウトです。

- より多くのテキストを表示可能
- 画像は補助的な役割
- 詳細な説明に適しています

![](https://picsum.photos/400/400)

---

<!-- _class: content-image-right content-60 -->

## 右画像40% + コンテンツ60%

バランスの取れたレイアウトです。

- テキストと画像のバランス
- プレゼンテーション向き

![](https://picsum.photos/500/400)

---

<!-- _class: content-image-right -->

## 右画像50% + コンテンツ50%

デフォルトでは50%ずつの分割です。

- ポイント1
- ポイント2

![](https://picsum.photos/600/400)

---

<!-- _class: content-image-right content-40 -->

## 右画像60% + コンテンツ40%

画像を大きく表示するレイアウト。

- 簡潔な説明

![](https://picsum.photos/700/500)

---

<!-- _class: content-image-right content-30 -->

## 右画像70% + コンテンツ30%

画像中心のレイアウト。

- 最小限のテキスト

![](https://picsum.photos/800/500)

---

<!-- _class: content-image-left content-70 -->

## 左画像30% + コンテンツ70%

コンテンツ領域を広くとるレイアウトです。

- より多くのテキストを表示可能
- 画像は補助的な役割
- 詳細な説明に適しています

![](https://picsum.photos/400/400)

---

<!-- _class: content-image-left content-60 -->

## 左画像40% + コンテンツ60%

バランスの取れたレイアウトです。

- テキストと画像のバランス
- プレゼンテーション向き

![](https://picsum.photos/500/400)

---

<!-- _class: content-image-left -->

## 左画像50% + コンテンツ50%

デフォルトでは50%ずつの分割です。

- 説明文1
- 説明文2

![](https://picsum.photos/600/400)

---

<!-- _class: content-image-left content-40 -->

## 左画像60% + コンテンツ40%

画像を大きく表示するレイアウト。

- 簡潔な説明

![](https://picsum.photos/700/500)

---

<!-- _class: content-image-left content-30 -->

## 左画像70% + コンテンツ30%

画像中心のレイアウト。

- 最小限のテキスト

![](https://picsum.photos/800/500)

---

<!-- _class: title -->
<!-- _paginate: false -->

## サンプルは以上で終了
