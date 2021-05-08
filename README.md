# dockerディレクトリの説明

## はじめに
ローカルPCでの環境を汚さないようにしたいため、必要な言語の開発環境を設定することを目的にしています。

## 用意している言語環境
### C言語
C言語の開発環境
cディレクトリを参照
### C++
C++の開発環境
docker/.devcontainerをVScodeの拡張機能"remote container"で開く

## 使い方
### ①github
- githubアカウントの作成
  https://qiita.com/kooohei/items/361da3c9dbb6e0c7946b
- PCローカルにgitをインストールする
  https://git-scm.com/book/ja/v2/%E4%BD%BF%E3%81%84%E5%A7%8B%E3%82%81%E3%82%8B-Git%E3%81%AE%E3%82%A4%E3%83%B3%E3%82%B9%E3%83%88%E3%83%BC%E3%83%AB
- 当リポジトリをクローンする
  git clone https://github.com/hirokidiv/docker.git

### ②Docker
  以下の公式ページからインストーラをダウンロードする
  https://www.docker.com/products/docker-desktop
### ③VScode
- PCローカルにVScodeをインストールする
  https://code.visualstudio.com/docs
- VScodeの拡張機能のRemote Containersをインストール
  vscodeの拡張機能検索(四角いボックスみたいなやつ)からRemote Containersと入力してインストール
### ④ Remote Container
VSCode左下の緑の｢><」マークをクリックし、『Open Folder in Container』
からgitでインストールしたdocker/cディレクトリを選択して起動
