---
aliases: []
tags:
  - t/term
---
使い慣れたファイルサーバーを、そのままAWS上で使える
1. FSx for Windows File Server
    - 用途: [[Windows]]の共有フォルダ（[[Active Directory]]連携など）。
    - メリット 会社のWindows PCから「Zドライブ」として繋ぐような使い方がそのままできます。
2. FSx for Lustre
    - 用途: 機械学習やスパコンのような、超高速な読み書きが必要な場合。 -> [[HPC]]など
    - メリット: [[S3]]と連携して、大量のデータを爆速で処理できます。
3. FSx for NetApp ONTAP
    - 用途: すでにオンプレミスで[[NetApp]]を使っている企業の移行。
4. FSx for OpenZFS
    - 用途: ZFSを利用しているLinux環境の移行。