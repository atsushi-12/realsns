# Node.js を用いたバックエンド開発の練習

## 使用フレームワーク

- EXPRESS
- MongoDB
- Mongoose
- nodemon
- React.js

## 概要

- クライアント(React)
- サーバー(node.js)
- データベース(mongoDB)

### mongoose とは？

> [OpenAI ChatGPT からの引用]  
> mongoose は MongoDB との対話を簡素化するための Node.js のオドメトリです。mongoose は、MongoDB のデータベース操作に対する抽象化レイヤーを提供し、MongoDB のスキーマベースのデータモデリングをサポートします。具体的には、以下のような機能を提供します。
>
> - スキーマ定義: mongoose は、MongoDB のドキュメント構造を定義するためのスキーマを提供します。スキーマは、データモデルのフィールド、タイプ、バリデーションルールなどを定義します。これにより、データの整合性を確保し、MongoDB のコレクション内のドキュメントの構造を制御することができます。
> - モデル: mongoose は、MongoDB のコレクションとの対話を容易にするためのモデルを提供します。モデルは、スキーマを使用して MongoDB のドキュメントを作成、読み取り、更新、削除するためのインタフェースを提供します。モデルを使用することで、MongoDB へのクエリや操作を簡潔に記述できます。
> - クエリ: mongoose は、MongoDB へのクエリの作成や実行をサポートします。クエリは、データベース内のドキュメントを検索、フィルタリング、ソートするための方法を提供します。mongoose のクエリ API は、MongoDB のクエリ言語をより簡単に扱えるように抽象化されています。
> - ミドルウェア: mongoose は、データベース操作の前後にフックするためのミドルウェア機能を提供します。これにより、データのバリデーション、変換、ロギングなどの追加処理を実行できます。
>   mongoose は、MongoDB をより簡単に使用するための便利なツールであり、Node.js アプリケーションでのデータベースアクセスを効率化します。
