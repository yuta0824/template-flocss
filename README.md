# Template FLOCSS

## 使用方法

1. パッケージのダウンロード<br>`$ git clone https://github.com/yuta0824/template-flocss`

2. プロジェクトディレクトリに配置
3. コンパイル

### コンパイル環境

- gulp
- [gulp-sass-glob-use-forward](https://github.com/jakerambo/gulp-sass-glob-use-forward)
  - ファイルを手動で index.scss にまとめています。

## CSS 設計

### レスポンシブコーディング

- モバイルファースト

### 設計

- [FLOCSS](https://github.com/hiloki/flocss "FLOCSS") を採用

### クラスの命名規則

- `Block__Element--Modifire`
- 単語の繋がりはハイフンで繋ぎ、頭文字-役割-名前空間で統一。
  - 例) フッターのボタン `c-btn-footer`
