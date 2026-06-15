# KurokoCast アップデート情報

このリポジトリは、**KurokoCast** のアップデート確認用データと配布情報を公開するためのリポジトリです。

KurokoCast は、Windows向けのリアルタイム字幕・OCR翻訳・配信補助アプリです。

## このリポジトリの目的

このリポジトリは、KurokoCast本体のソースコード公開用ではありません。

主な用途は以下です。

* アップデート確認用JSONの公開
* プレプレテスト版・ベータ版の配布情報管理
* GitHub Releases によるインストーラー配布
* リリースノートの管理

## 含まれるファイル

このリポジトリには、主に以下のファイルを置きます。

* `latest-beta.json`
* `latest-stable.json`
* 必要に応じたリリース案内

インストーラー本体は、このリポジトリに直接コミットせず、GitHub Releases の Assets として公開します。

## アップデート確認の仕組み

KurokoCast は、このリポジトリにあるアップデート情報ファイルを確認して、新しいバージョンがあるかどうかを判定します。

### ベータ版チャンネル

```text
latest-beta.json
```

### 安定版チャンネル

```text
latest-stable.json
```

## ダウンロード

以下からダウンロードしてください。

【最新版】
[KurokoCast 0.1.0-beta.1 をダウンロード]([https://github.com/kuroko-cast/KurokoCast-updates/releases/download/v0.1.0-beta.0/KurokoCast-0.1.0-beta.0-Setup.exe](https://github.com/kuroko-cast/KurokoCast-updates/releases/download/v0.1.0-beta.1/KurokoCast-0.1.0-beta.1-Setup.exe))

【過去バージョンはこちら】
[バージョン一覧](https://github.com/kuroko-cast/KurokoCast-updates/releases)


インストーラーをダウンロード後、`KurokoCast-x.x.x-beta.x-Setup.exe` を実行してください。

## 注意事項

* Windows用のテスト版です。
* 初回起動時に Windows Defender や SmartScreen の確認が出る場合があります。
* 不具合が発生した場合は、アプリ内のサポートZIPを作成して共有してください。


`.exe` ファイルをこのリポジトリに直接コミットしないでください。

## 現在の状態

KurokoCast は現在、プレプレテスト版・ベータ版として開発中です。

正式公開前のため、機能、画面、アップデート方法、配布方法は今後変更される可能性があります。

## 注意事項

このリポジトリには、KurokoCast本体のソースコード、開発用ファイル、テストコード、ログ、サポートZIP、OCRデバッグ画像などは置きません。

本体開発リポジトリは別管理です。
