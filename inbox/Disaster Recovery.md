---
aliases:
  - DR
tags:
  - t/term
---
- Backup & Restore
	- 定期的にバックアップを取得し、災害時はそこから復旧
- Pilot Light
	- DBなどのコアサービスは常時稼働させておく
- Warm Stand-by
	- 本番よりも規模を落としたものを常時稼働させておく
- Multi-site
	- 本番と同じやつをサブ稼働


- Exponential Backoff