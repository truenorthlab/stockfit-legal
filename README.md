# StockFit — 法的文書 / 법적 문서 / Legal

App Store が求める公開ページ（プライバシーポリシー・利用規約・オープンソースライセンス）を
GitHub Pages で配信するための**ミラー**です。

⛔ **ここを直接編集しない。** 単一の出典はアプリ本体のリポジトリの `docs/` で、
アプリ内の文言（`Localizable.xcstrings` の `legal.*`）と対になっています。
片方だけ直すとその場が虚偽告知になります。更新は本体側で行い、`tools/publish_legal.sh` で反映します。

- privacy.html — プライバシーポリシー（ja / ko / en）
- terms.html — 利用規約
- licenses.html — オープンソースライセンス
- index.html — 目次
