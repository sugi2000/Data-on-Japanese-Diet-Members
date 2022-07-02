# 日本の国会議員のデータ
### Members of the Diet of Japan

## 概要

日本の国会議員のデータをJSON形式でまとめて公開しています。

データは、2022年6月29日現在のものです。今後の更新の予定は未定です。

## データ

### 衆議院議員
  - [shugiin.json](./shugiin.json)
    - `name`: 氏名
    - `link`: 議員情報ページのURL
    - `sex`: 性別（`F`: 女性、`M`: 男性）
    - `wikiTitle`: Wikipedia日本語版の項目のタイトル
    - `birthday` : 生年月日（`YYYY-MM-DD`）

### 参議院議員
  - [sangiin.json](./sangiin.json)
    - `name`: 氏名
    - `realName`: 本名氏名
    - `link`: 議員情報ページのURL
    - `sex`: 性別（`F`: 女性、`M`: 男性）
    - `wikiTitle`: Wikipedia日本語版の項目のタイトル
    - `birthday` : 生年月日（`YYYY-MM-DD`）

## データの利用について

- 本データは自由に閲覧・ダウンロードが可能です。
- GitHubプロジェクトのライセンスはMITライセンスとし、商用・非商用を問わず自由に使用できます。
- クレジット表記は不要です。
- 本データの正確性は保証していません。
- 本データの利用によって生じたいかなる損害について、開発者は一切責任を負いません。

## データソース

以下のサイトで公開されている情報を収集しました。

- [衆議院ウェブサイト](https://www.shugiin.go.jp/)
- [参議院ウェブサイト](https://www.sangiin.go.jp/)
- [Wikipedia日本語版](https://ja.wikipedia.org/)

## 開発者

杉本達應 [@sugi2000](https://twitter.com/sugi2000/)
