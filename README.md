# ブラウザ画像編集ワークベンチ

画像を読み込み、レイヤー、選択範囲、切り抜き、リサイズ、回転、色調補正、フィルタ、ブラシ、消しゴム、テキスト、透過保持、履歴管理をブラウザ上で扱う。Photoshop的な基本操作を軽量なWebツールとして提供し、編集後のPNG、WebP、JPEGを書き出す。

| 項目 | 内容 |
| --- | --- |
| Rank | 73 |
| Domain | WebApp |
| Idea No. | 11 |
| Repository | browser-image-editing-workbench |
| 主な公開先 | GitHub Pages / GitHub Release |

## Implementation

- `src/product-profile.mjs`: プロダクト定義。
- `src/core.mjs`: 入力正規化とバッチ評価。
- `src/validators.mjs`: 必須項目と warning 項目の検査。
- `src/review-model.mjs`: UI/レビュー向けモデル。
- `src/report.mjs`: Markdown / HTML レポート生成。
- `src/cli.mjs`: CLI。
- `public/`: 静的WebApp。

## Validation

`npm test` で代表シナリオ、QCDS、docs ZIP、文字化け、WebApp非blank表示を検証します。

## Strict QCDS Docs

- [Remote benchmark](docs/qcds-remote-benchmark.md)
- [Strict metrics](docs/qcds-strict-metrics.json)
- [Traceability matrix](docs/traceability-matrix.md)
- [Release evidence](docs/release-evidence.json)
