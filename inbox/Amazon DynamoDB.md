---
aliases:
  - Dynamo
tags:
  - t/term
---
Capacity Unit: 1秒間にどれくらい読み書きするか
- RCU -> can read up to 4kb twice every sec
- WCU -> can write up to 1kb once every sec

Reserved Capacity: 事前予約によるコスト削減

Auto Scaling
負荷が大きい場合に自動でCapacity Unitを拡張させる。
