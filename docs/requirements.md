# 要件定義

| 項目 | 内容 |
| --- | --- |
| Rank | 73 |
| Domain | WebApp |
| Idea No. | 11 |
| Repository | browser-image-editing-workbench |
| 主な公開先 | GitHub Pages / GitHub Release |

## 背景

ちょっとした画像編集のために重いデスクトップアプリを起動する必要があり、透過や書き出し設定も用途ごとに確認しづらい。

## 目的

画像を読み込み、レイヤー、選択範囲、切り抜き、リサイズ、回転、色調補正、フィルタ、ブラシ、消しゴム、テキスト、透過保持、履歴管理をブラウザ上で扱う。Photoshop的な基本操作を軽量なWebツールとして提供し、編集後のPNG、WebP、JPEGを書き出す。

## 必須要件

- image edit job を複数件まとめて検証できる。
- required fields: `id`, `title`, `imagePath`, `operation`, `exportFormat`, `owner`。
- warning field: `nonDestructiveNote`。
- 代表シナリオ、QCDS metrics、docs ZIP、release evidence を再生成できる。
