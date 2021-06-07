# Terraform 
## はじめに
クラウド環境における構築作業では、通常、コンソール上で多数の画面や入力フォームを操作することでリソースを作成できますが、毎回手作業が発生するため、作業時間の増加や設定ミスが発生するといった問題があります。  
その問題を解決するために、近年では、IaC(Infrastructure as Code)と呼ばれる、コードを用いてインフラストラクチャの管理やプロビジョニングを行う手法が注目・活用されています。  
本ページではインフラ自動構築ツールである Terraform のサンプルスクリプトを提供します。

## Terraform とは
HashiCorp社により開発されているオープンソースのインフラ自動構築ツールです。  
主にクラウド環境(クラウド以外でも利用可能)を構築する際に利用されます。
Terraform構成ファイルの作成やメンテナンスこそ必要ですが、手作業よりも素早くかつミスなく、様々な環境をプログラマブルに構築できるようになり、作業コストや作業ミスを抑えることができます。

## ディレクトリ構成
```
Terraform
   |- OCI
   |   |- clp-lin-2node-lb-md.zip (2ノード ミラーディスク型クラスタ(Linux))
   |   |- clp-win-2node-lb-md.zip (3ノード ミラーディスク型クラスタ(Windows))
   |
   |- README_JP.md
   |- README.md
```

## 参考URL
[Oracle Cloud InfrastructureでResource Managerを使用したHAクラスター環境の自動構築を試してみました(Windows/Linux)](https://jpn.nec.com/clusterpro/blog/20210531.html?)  
