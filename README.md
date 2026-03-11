# こえもじ

声を文字に、文字を記事に。

音声ファイルをアップロードするだけで、文字起こし→記事化まで一気に変換できるWebツールです。

## 🔗 デモ

**[こえもじ を使ってみる →](https://oyuwarilife.github.io/koemoji/)**

## 機能

- **音声入力**: ファイルアップロード（ドラッグ&ドロップ）/ ブラウザ録音 / 動画ファイル対応
- **文字起こし**: Gemini API（日本語対応・大容量ファイルOK）
- **記事化**: 3つのAIから選択可能
  - Gemini
  - OpenAI (GPT)
  - Claude
- **記事形式**: ブログ / note記事 / 要約 / SNS投稿 / 議事録 / カスタム
- **プロンプト編集**: 生成前にプロンプトを確認・カスタマイズ可能
- **出力**: コピー / Markdownダウンロード / 再生成

## 使い方

1. 「API設定」からAPIキーを入力（ブラウザに保存されます）
2. 音声ファイルをアップロード or 録音
3. 「文字起こしする」をクリック
4. 記事の形式とAIを選んで「記事を生成する」

## 必要なAPIキー

| 用途 | 必要なキー |
|------|-----------|
| 文字起こし | Gemini APIキー（必須） |
| 記事化 | Gemini / OpenAI / Claude のいずれか |

## 対応ファイル形式

MP3, WAV, M4A, OGG, WebM, MP4

## プライバシー

- APIキーはブラウザのlocalStorageにのみ保存されます
- 音声データ・テキストは各APIに直接送信され、このツール側にサーバーはありません

## 関連プロジェクト

| プロジェクト | 説明 |
|---|---|
| [context-engine](https://github.com/oyuwarilife/context-engine) | AIエージェント向けコンテキスト管理ツール |
| [katsu-celebration](https://github.com/oyuwarilife/katsu-celebration) | ポモ活スタンプシート |
| [sns-post-generator](https://github.com/oyuwarilife/sns-post-generator) | SNS投稿ジェネレーター |

## 作者

[@oyuwarilife](https://github.com/oyuwarilife)
