# 実験レポート: 260414_009

このレポートは `photogrammetry-cli run` により自動生成されます。

## Run 概要

| 項目 | 値 |
|------|----|
| Run ID | `260414_009` |
| 実行日時 | `2026-04-14 19:57:10` |
| 入力フォルダ | `../input/260413_01_トラックボールマウス` |
| 入力画像の機種 | `iPhone SE (3rd generation)` |
| 実行結果 | `success` |
| 使用した出力形式 | `usdz`, `obj` |

### 出力成果物

- `events.jsonl`
- `input_manifest.json`
- `metrics.json`
- `model.usdz`
- `model_obj`

## 所要時間

### 前処理（起点: run_started）

| 到達点 | 経過時間 |
|--------|----------|
| `input_validated` | `0.0 秒 (00:00)` |
| `input_complete` | `2.0 秒 (00:02)` |

### 生成処理（起点: input_complete）

| 到達点 | 経過時間 |
|--------|----------|
| `usdz` 完了 | `111.0 秒 (01:51)` |
| `obj` 完了 | `114.0 秒 (01:54)` |

### 全体

| 区間 | 所要時間 |
|------|----------|
| `run_started -> processing_complete` | `116.0 秒 (01:56)` |
| `最後の request_complete -> processing_complete` | `0.0 秒 (00:00)` |

## 入力画像サマリ

### 全体

| 項目 | 値 |
|------|----|
| 入力画像枚数 | `64` |
| 拡張子の分布 | `heic`:`64` |
| 向きの分布 | `landscape`:`64` |
| 撮影時刻あり画像数 | `64` |
| 撮影時刻欠損画像数 | `0` |

### 画像サイズ分布

| 項目 | 値 |
|------|----|
| 最小 | `4032 x 3024` |
| 最大 | `4032 x 3024` |
| 中央 | `4032 x 3024` |
| 平均 | `4032 x 3024` |

### ファイルサイズ分布

| 項目 | 値 |
|------|----|
| 最小 | `1.64 MB` |
| 最大 | `2.62 MB` |
| 中央 | `2.40 MB` |
| 平均 | `2.40 MB` |

### 撮影時刻分布

| 項目 | 値 |
|------|----|
| 最初の撮影時刻 | `2026-04-13 13:07:10` |
| 最後の撮影時刻 | `2026-04-13 13:10:48` |
| 撮影継続時間 | `218.0 秒 (03:38)` |
| 欠損率 | `0.0%` |

## メタデータ品質レポート

### 主要メタデータ（core）

未検出項目なし

| メタデータキー | 表示名 | 意味 | 存在画像数 | 欠損画像数 | 欠損率 |
|----------------|--------|------|------------|------------|--------|
| `PixelWidth` | 画像幅 | 画像のピクセル幅 | `64` | `0` | `0.0%` |
| `PixelHeight` | 画像高さ | 画像のピクセル高さ | `64` | `0` | `0.0%` |
| `{Exif}.DateTimeOriginal` | 元の撮影日時 | シャッターを切った日時 | `64` | `0` | `0.0%` |
| `{Exif}.FNumber` | F値 | 絞り値 | `64` | `0` | `0.0%` |
| `{Exif}.ExposureTime` | 露光時間 | シャッター速度に相当する露光時間 | `64` | `0` | `0.0%` |
| `{Exif}.ISOSpeedRatings` | ISO感度 | 撮影時の ISO 感度 | `64` | `0` | `0.0%` |
| `{Exif}.FocalLength` | 焦点距離 | レンズの焦点距離 | `64` | `0` | `0.0%` |
| `{Exif}.FocalLenIn35mmFilm` | 35mm換算焦点距離 | 35mm 判換算の焦点距離 | `64` | `0` | `0.0%` |
| `{TIFF}.Make` | メーカー名 | 撮影機器のメーカー | `64` | `0` | `0.0%` |
| `{TIFF}.Model` | 機種名 | 撮影機器のモデル名 | `64` | `0` | `0.0%` |
| `{TIFF}.Orientation` | 画像向き | Exif Orientation の値。画像の回転や反転状態 | `64` | `0` | `0.0%` |

### 主要メタデータの代表値

| 表示名 | 値の概要 |
|--------|----------|
| 画像幅 | 4032 px |
| 画像高さ | 3024 px |
| 元の撮影日時 | 2026-04-13 13:07:10 〜 2026-04-13 13:10:48 |
| F値 | F1.80 |
| 露光時間 | 1/121 秒 〜 1/60 秒 |
| ISO感度 | 100 / 80 |
| 焦点距離 | 3.99 mm |
| 35mm換算焦点距離 | 28 mm |
| メーカー名 | Apple |
| 機種名 | iPhone SE (3rd generation) |
| 画像向き | 6（右に90°回転 / 縦位置） |

### 補助メタデータ（optional）

未検出項目: `デジタルズーム倍率`, `緯度`, `経度`, `高度`, `撮影方向`

| メタデータキー | 表示名 | 意味 | 存在画像数 | 欠損画像数 | 欠損率 |
|----------------|--------|------|------------|------------|--------|
| `Headroom` | HDR拡張輝度 | HDR や拡張輝度に関する補助情報 | `64` | `0` | `0.0%` |
| `PrimaryImage` | 主画像フラグ | HEIC コンテナ内で主画像として扱われることを示すフラグ | `64` | `0` | `0.0%` |
| `{Exif}.LensMake` | レンズメーカー | レンズのメーカー名 | `64` | `0` | `0.0%` |
| `{Exif}.LensModel` | レンズ名 | レンズのモデル名 | `64` | `0` | `0.0%` |
| `{Exif}.LensSpecification` | レンズ仕様 | 焦点距離や開放 F 値などのレンズ仕様 | `64` | `0` | `0.0%` |
| `{Exif}.ExposureBiasValue` | 露出補正 | 撮影時の露出補正量 | `64` | `0` | `0.0%` |
| `{Exif}.WhiteBalance` | ホワイトバランス | ホワイトバランス設定 | `64` | `0` | `0.0%` |
| `{Exif}.MeteringMode` | 測光モード | 露出測定のモード | `64` | `0` | `0.0%` |
| `{Exif}.Flash` | フラッシュ | フラッシュ使用状態 | `64` | `0` | `0.0%` |
| `{Exif}.ColorSpace` | 色空間 | 画像の色空間 | `64` | `0` | `0.0%` |
| `{Exif}.CompositeImage` | 合成画像フラグ | HDR や複数フレーム合成の有無を示す補助情報 | `64` | `0` | `0.0%` |
| `{Exif}.ExposureMode` | 露出モード | 自動露出や手動露出の状態 | `64` | `0` | `0.0%` |
| `{Exif}.ExposureProgram` | 露出プログラム | 全自動やプログラム AE などの露出方式 | `64` | `0` | `0.0%` |
| `{Exif}.DigitalZoomRatio` | デジタルズーム倍率 | デジタルズームの倍率。光学条件の混在確認に使う | `0` | `64` | `100.0%` |
| `{Exif}.BrightnessValue` | 輝度値 | 画像記録時の明るさの指標 | `64` | `0` | `0.0%` |
| `{Exif}.SceneType` | シーン種別 | 静止画や特殊な記録パイプラインを識別する補助情報 | `64` | `0` | `0.0%` |
| `{GPS}.GPSLatitude` | 緯度 | 撮影地点の緯度 | `0` | `64` | `100.0%` |
| `{GPS}.GPSLongitude` | 経度 | 撮影地点の経度 | `0` | `64` | `100.0%` |
| `{GPS}.GPSAltitude` | 高度 | 撮影地点の高度 | `0` | `64` | `100.0%` |
| `{GPS}.GPSImgDirection` | 撮影方向 | 撮影時に端末が向いていた方位 | `0` | `64` | `100.0%` |
| `ProfileName` | 色プロファイル名 | 埋め込まれた色プロファイル名 | `64` | `0` | `0.0%` |
| `{Exif}.OffsetTimeOriginal` | 撮影時タイムゾーン | 元の撮影日時に対応するタイムゾーンオフセット | `64` | `0` | `0.0%` |
| `{TIFF}.Software` | ソフトウェア | 画像生成・加工に使われたソフトウェア情報 | `64` | `0` | `0.0%` |
| `{TIFF}.HostComputer` | ホスト環境 | 生成元のホスト環境情報 | `64` | `0` | `0.0%` |

### 補助メタデータの代表値

| 表示名 | 値の概要 |
|--------|----------|
| レンズ名 | iPhone SE (3rd generation) back camera 3.99mm f/1.8 |
| レンズ仕様 | 焦点距離 3.99 mm、開放 F1.80 |
| 露出補正 | 0 EV |
| ホワイトバランス | 自動 |
| フラッシュ | 発光なし（フラッシュ機能あり） |
| 色空間 | 未校正（sRGB 以外） |
| デジタルズーム倍率 | 未検出 |
| 輝度値 | 3.33 〜 4.93 |
| 撮影方向 | 未検出 |

### 上記以外で今回観測されたメタデータ

| メタデータキー | 存在画像数 | 欠損画像数 | 欠損率 |
|----------------|------------|------------|--------|
| `ColorModel` | `64` | `0` | `0.0%` |
| `DPIHeight` | `64` | `0` | `0.0%` |
| `DPIWidth` | `64` | `0` | `0.0%` |
| `Depth` | `64` | `0` | `0.0%` |
| `Orientation` | `64` | `0` | `0.0%` |
| `{Exif}.ApertureValue` | `64` | `0` | `0.0%` |
| `{Exif}.DateTimeDigitized` | `64` | `0` | `0.0%` |
| `{Exif}.ExifVersion` | `64` | `0` | `0.0%` |
| `{Exif}.OffsetTime` | `64` | `0` | `0.0%` |
| `{Exif}.OffsetTimeDigitized` | `64` | `0` | `0.0%` |
| `{Exif}.PixelXDimension` | `64` | `0` | `0.0%` |
| `{Exif}.PixelYDimension` | `64` | `0` | `0.0%` |
| `{Exif}.SensingMethod` | `64` | `0` | `0.0%` |
| `{Exif}.ShutterSpeedValue` | `64` | `0` | `0.0%` |
| `{Exif}.SubjectArea` | `64` | `0` | `0.0%` |
| `{Exif}.SubsecTimeDigitized` | `64` | `0` | `0.0%` |
| `{Exif}.SubsecTimeOriginal` | `64` | `0` | `0.0%` |
| `{TIFF}.DateTime` | `64` | `0` | `0.0%` |
| `{TIFF}.ResolutionUnit` | `64` | `0` | `0.0%` |
| `{TIFF}.TileLength` | `64` | `0` | `0.0%` |
| `{TIFF}.TileWidth` | `64` | `0` | `0.0%` |
| `{TIFF}.XResolution` | `64` | `0` | `0.0%` |
| `{TIFF}.YResolution` | `64` | `0` | `0.0%` |

### 今回観測された Apple独自タグ

検出キー数: `63`

`{MakerApple}.1`, `{MakerApple}.12`, `{MakerApple}.13`, `{MakerApple}.14`, `{MakerApple}.16`, `{MakerApple}.2`, `{MakerApple}.20`, `{MakerApple}.23`, `{MakerApple}.25`, `{MakerApple}.26`, `{MakerApple}.3`, `{MakerApple}.3.epoch`, `{MakerApple}.3.flags`, `{MakerApple}.3.timescale`, `{MakerApple}.3.value`, `{MakerApple}.31`, `{MakerApple}.32`, `{MakerApple}.33`, `{MakerApple}.35`, `{MakerApple}.37`, `{MakerApple}.38`, `{MakerApple}.39`, `{MakerApple}.4`, `{MakerApple}.40`, `{MakerApple}.43`, `{MakerApple}.45`, `{MakerApple}.46`, `{MakerApple}.47`, `{MakerApple}.5`, `{MakerApple}.51`, `{MakerApple}.52`, `{MakerApple}.53`, `{MakerApple}.54`, `{MakerApple}.55`, `{MakerApple}.58`, `{MakerApple}.59`, `{MakerApple}.6`, `{MakerApple}.60`, `{MakerApple}.63`, `{MakerApple}.64`, `{MakerApple}.64.0`, `{MakerApple}.64.1`, `{MakerApple}.64.2`, `{MakerApple}.64.3`, `{MakerApple}.65`, `{MakerApple}.67`, `{MakerApple}.68`, `{MakerApple}.69`, `{MakerApple}.7`, `{MakerApple}.70`, `{MakerApple}.74`, `{MakerApple}.77`, `{MakerApple}.78`, `{MakerApple}.78.1`, `{MakerApple}.78.2`, `{MakerApple}.79`, `{MakerApple}.8`, `{MakerApple}.82`, `{MakerApple}.83`, `{MakerApple}.85`, `{MakerApple}.88`, `{MakerApple}.96`, `{MakerApple}.97`

### 使用データセットにおけるApple独自タグの差分項目

| メタデータキー | 表示名 | 意味 | 存在画像数 | 欠損画像数 | 欠損率 |
|----------------|--------|------|------------|------------|--------|
| `{MakerApple}.40` | Apple独自タグ | Apple独自タグ（詳細不明） | `63` | `1` | `1.6%` |
| `{MakerApple}.63` | Apple独自タグ | Apple独自タグ（詳細不明） | `63` | `1` | `1.6%` |

## イベント要約

### サマリ

| 項目 | 値 |
|------|----|
| `invalid_sample` 件数 | `0` |
| `skipped_sample` 件数 | `0` |
| `request_error` 件数 | `0` |
| `run_failed` 有無 | `なし` |
| 失敗理由 | `N/A` |

### イベント状態

異常イベントは検出されませんでした。
