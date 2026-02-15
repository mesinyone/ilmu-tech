---
aliases: []
tags:
  - t/term
---
[[ETL]]サービスです。複数のデータソースからデータを抽出し、統合・変換したデータをターゲットへ格納する一連の処理を行う。

[[Amazon EMR]]は、AWS Glueよりも大規模なデータを扱う

Glue Crawler
データソースをクロールし、スキーマを自動検出。[[Glue Data Catalog]]に登録

[[Amazon Kinesis]]はストリーミングデータの処理を行い、S3などに保存。それをGlueで[[ETL]]する