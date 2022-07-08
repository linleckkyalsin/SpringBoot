## どのようなアプリケーションか？

- 学生のデータ（名前、生年月日、メール）を入れられて、作成、参照、更新、削除 （CRUD）という機能ができるシンプルなアプリでございます。

## 動作する環境（Javaのバージョン）

Oracle OpenJDK version 18.0.1

## 起動するための手順（データベースの準備やSpring Bootの起動）

- application.propertiesにpostgreSQLの接続先を記載します。
- studentパッケージにStudentクラスを作成します。
- student repository にはすべての学生のデータをセレクトします。
- student controller API からリクエストの処理、student serviceから機能を使います。
- student serviceにはCRUDの機能をかきます。
