# GHC User Guide の翻訳のための Guide

## 環境

- Ubuntu 16.04

## 準備の準備

### Git Hub 関連

- git-core のインストール（すでに済んでいたので詳細は逆に不明^^;）
- hub のインストール github からマスターのソースインストール
    - go が必要，https://golang.org/dl/ からbinaryアーカイブ取得してインストール
	- ruby が必要，https://www.oiax.jp/rails/zakkan/rails_4_2_installation_on_ubunt.html を参考にする
    - gem で Bundler をインストールする
    - .zshrc に function git (){hub "$@"} を追加
	- hub create nobsun/ghcguide-guide
