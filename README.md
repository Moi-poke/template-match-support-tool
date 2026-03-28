# 画像検知ツール v1.0（ローカル同梱版）

スクリーンショット画像とテンプレート画像を用いたテンプレートマッチング検証を、ブラウザ上で行うためのツールです。

## 同梱方式について

この版は CDN ではなく、`vendor/` 配下のローカルファイルを参照する構成です。

- `vendor/opencv/opencv.js`
- `vendor/jszip/jszip.min.js`

公開前に、上記ファイルを公式配布物から配置してください。

## 使い方

1. `vendor/opencv/opencv.js` を配置します。
2. `vendor/jszip/jszip.min.js` を配置します。
3. GitHub Pages の公開ルートに、このフォルダ一式を配置します。
4. `index.html` にアクセスします。

## ライセンス

- OpenCV.js は、同梱する OpenCV のバージョンに応じたライセンスに従ってください。
  - OpenCV 4.5.0 以上: Apache License 2.0
  - OpenCV 4.4.0 以下: BSD 3-Clause
- JSZip は MIT または GPLv3 のデュアルライセンスですが、この構成では MIT として扱う想定です。

詳細は `THIRD_PARTY_NOTICES.md` と `licenses/` を参照してください。
