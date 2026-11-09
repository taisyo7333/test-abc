# test-abc

Namespace `test` の DEMO アプリです。S3 バケット `test-abc-dinoue` の `message.txt` を読み、画面に出します。オブジェクトが無い、または S3 に届かないときは `Hello World` を出します。

AWS の読み取り権限は Pod の IRSA です。Deployment にはアクセスキーを置きません。
