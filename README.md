# compornent（共通部品）

## イメージ画像

## 概要

- `position: relative/absolute`で中央揃えする。
-
- `.box1`で以下を指定して中央に揃えてます。
- `position: absolute;`
- `top: 50%;`
- `left: 50%;`
- `transform: translate(-50%, -50%);`
-
- https://www.notion.so/000_web-component-index-c4b399010bf342e9b4e2ed516cf9c730

## 仕様

- スマホファースト
- rem 記述
- ルートフォントを vw で設定していることから PC サイズのレイアウトをタブレットで表示させることが出来ます（rem で書いた場合のみ）。
- xxx

## 注意事項

- `position: relative;`は設定した親要素配下の全てに効いてるのが判明した。

## 使い方

- 「copy start」から「copy end」をコピペ。
- css: src -> module -> xxx をコピペ。

## w3c html チェック結果

- https://validator.w3.org/nu/

## w3c css チェック結果

- https://jigsaw.w3.org/css-validator/

## portfolio url:

- https://c-0041.wtb.cfbx.jp/

## 参考にしたサイト

- transform プロパティを使って要素を上下中央に配置する
- https://qiita.com/yukinaka/items/1da62535553b62cc50aa

## 更新履歴

- 2022/3/30 初版 作成完了(position: relative/absolute で中央揃え)

## 環境・使い方

- ダウンロードしたフォルダを開く。
- ターミナルを開き、 npm i とコマンドを入力する。
- node_modules と package-lock.json が生成されるのを確認する。
- 「 npx gulp 」とコマンドを入力すると動き出します。

## 備考
