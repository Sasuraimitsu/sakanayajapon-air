# sakanayajapon-air

**このリポジトリは旧版です。メンテナンスされていません。**

法人向け商品カタログの試作版でした。後継は以下です。

- リポジトリ: https://github.com/sakanaya-japon/sakanaya-productlist
- 公開URL: https://sakanaya-japon.github.io/sakanaya-productlist/

後継版は Google Apps Script から商品・価格を動的に取得し、顧客登録・在庫表示・
Excel出力・Telegram Bot 連携に対応しています。本リポジトリの内容は使用しないでください。

## 2026-09-14 の変更

公開リポジトリに実売価格がハードコードされていたため、`script.js` の
`SAMPLE_PRODUCTS` から価格を削除しました（32件、すべて `price: null`）。
既存のフォールバック処理により「お問い合わせください」と表示されます。

過去のコミット履歴には価格が残っています。完全に削除する場合はリポジトリごと
削除してください。
