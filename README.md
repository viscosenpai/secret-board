秘密の匿名掲示板
====

N予備校のプログラミングコース Webアプリ基礎の授業で作成した簡易匿名掲示板です。

## Description
HTML,CSS,JavaScriptを用いて作成された匿名掲示板です。
HTTPでBASIC認証を行いログインしたユーザーがテキストを投稿、削除できます。
Cookieでセッションを管理しユーザーに日毎に変わるセッションIDを付与しています。
ユーザーの投稿はPostgreSQLでデータベースを作成し保存しています。
HTMLはjadeで出力し、デザインはBootstrapを使用しました。
XSS脆弱性、OSコマンドインジェクション、SQLインジェクション、セッションハイジャック、CSRF脆弱性に対応しています。

ゲストアカウント
ID: guest1
PASSWORD: dUtr7spupHuY

ID: guest2
PASSWORD: 7WeteKacrAta