# PsMan
## 概要
パスワード管理アプリです。
このアプリがあれば、大量のパスワードを記憶するストレスや、漏洩の恐怖から開放されます。

## 仕様
 - ユーザは、アプリの初回起動時にマスターキーを設定します。
    - ユーザが記憶しないといけないのは、このマスターキーだけです。
 - マスターキーはアプリに保存せず、マスターキーを暗号化した文字列を保存します。
    - マスターキーを保存しないため、漏洩する危険はありません。
 - ユーザが入力したパスワードは、マスターキーを用いて暗号化してアプリに保存します。
 - ネットワーク通信は行いません。オフラインでも使用可能です。
