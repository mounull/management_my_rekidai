# 自己歴代

BPIM2 の「歴代ベストスコア」を、曲名(ひらがなでも可)で検索して EX スコアを確認する個人用ページです。

- 表示対象: SP の ANOTHER / LEGGENDARIA
- データ取得: BPIM2-API(トークンはブラウザ内にのみ保存。このリポジトリには含まれません)
- 非公式の個人プロジェクトであり、BPIM2 や関係各社とは関係ありません

## ライセンス

このリポジトリは GNU General Public License v2 (GPLv2) で公開しています。全文は `LICENSE` を参照してください。

## 使用しているデータ・ライブラリ

- `eng-kana.json`
  [alkana](https://github.com/cod-sushi/alkana.py)(GPLv2)の英単語→カタカナ辞書から、
  英数字の小文字だけの単語を取り出して JSON にしたものです。
- [kuromoji.js](https://github.com/takuyaa/kuromoji.js)(Apache License 2.0)
  漢字の読みを求めるために、jsDelivr 経由で読み込んでいます(同梱はしていません)。
