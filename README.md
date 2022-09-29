# 日本の国会議員のデータ
### Data on Japanese Diet Members

## 概要

日本の国会議員のデータをJSON形式でまとめて公開しています。

データの最終更新日

- 衆議院議員：2022年6月29日
- 参議院議員：2022年9月29日

今後の更新の予定は未定です。

## データ

### 衆議院議員
  - [shugiin.json](./2022-06-29/shugiin.json)
    - `name`: 氏名
    - `link`: 議員情報ページのURL
    - `sex`: 性別（`F`: 女性、`M`: 男性）
    - `wikiTitle`: Wikipedia日本語版の項目のタイトル
    - `birthday` : 生年月日（`YYYY-MM-DD`）

### 参議院議員
  - [sangiin.json](./2022-09-29/sangiin.json)
    - `name`: 氏名
    - `realName`: 本名氏名
    - `link`: 議員情報ページのURL
    - `sex`: 性別（`F`: 女性、`M`: 男性）
    - `wikiTitle`: Wikipedia日本語版の項目のタイトル
    - `birthday` : 生年月日（`YYYY-MM-DD`）

## データの利用について

- 本データは自由に閲覧・ダウンロードが可能で、商用・非商用を問わず自由に使用できます。
- クレジット表記は不要です。
- 本データの正確性は保証していません。
- 本データの利用によって生じたいかなる損害について、開発者は一切責任を負いません。

## データソース

以下のサイトで公開されている情報を収集しました。

- [衆議院ウェブサイト](https://www.shugiin.go.jp/)
- [参議院ウェブサイト](https://www.sangiin.go.jp/)
- [Wikipedia日本語版](https://ja.wikipedia.org/)

## 公開の動機

国会議員の人口ピラミッドを作りたかったため。

<blockquote class="twitter-tweet" data-conversation="none" data-dnt="true"><p lang="ja" dir="ltr">国会議員と日本人の人口ピラミッド。議員の年齢は2022年6月29日現在。人口の棒の長さは、2万分の1に縮めています。<br>データ：Wikipedia（議員情報）、国勢調査（日本人の人口）。 <a href="https://t.co/DYYmg8Jy7G">pic.twitter.com/DYYmg8Jy7G</a></p>&mdash; SUGIMOTO Tatsuo 杉本達應 (@sugi2000) <a href="https://twitter.com/sugi2000/status/1542069371962814464?ref_src=twsrc%5Etfw">June 29, 2022</a></blockquote>

## 開発者

杉本達應 [@sugi2000](https://twitter.com/sugi2000/)
