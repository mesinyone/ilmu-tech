---
aliases: []
tags:
  - t/term
---
Health check of the system.

- [[Amazon CloudWatch]]
	- [Network Synthetic Monitor](Network%20Synthetic%20Monitor.md)


リソースごとの標準メトリクスでカバーできない項目は、カスタムメトリクスとして定義し、CLIコマンドやAPIで集計できる。EC2のメモリ使用量はカスタムメトリクス。メモリ使用量が標準メトリクスにない理由は、恐らくEC2のOS領域はユーザー側の責任領域にあたるから。

複数のメトリクスがしきい値を超えたときにアラームを通知したい場合は「複合アラーム」を作成