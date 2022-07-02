# Members of the Diet of-Japan
# 日本の国会議員のデータ

## 概要

日本の国会議員のデータをJSON形式でまとめて公開しています。

データソース：

- [衆議院ウェブサイト](https://www.shugiin.go.jp/)
- [参議院ウェブサイト](https://www.sangiin.go.jp/)
- [Wikipedia日本語版](https://ja.wikipedia.org/)

データは、2022年6月29日現在です。

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

## 二次利用とライセンスについて

- すべてのデータとソースコードは自由に閲覧・ダウンロードが可能です。
- GitHubプロジェクトのライセンスはMITライセンスとし、商用・非商用を問わずご自由にお使いいただけます。
- 本データの正確性は保証していません。データの利用によって生じたいかなる損害について、開発者は一切責任を負いません。

## 開発者

杉本達應 [@sugi2000](https://twitter.com/sugi2000/)
