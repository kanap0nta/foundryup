# Foundryup on Docker

## 事前準備

1. VSCode をインストールする。

1. [本サイト](https://matsuand.github.io/docs.docker.jp.onthefly/get-docker/) のリンクから、 Docker をダウンロード・インストールする。

1. [本サイト]([https://qiita.com/75ks/items/b2961e8562c353f42d21](https://qiita.com/75ks/items/b2961e8562c353f42d21#vscode%E3%81%8B%E3%82%89%E3%82%B3%E3%83%B3%E3%83%86%E3%83%8A%E3%81%AB%E6%8E%A5%E7%B6%9A))などを参考に VSCode に [Devcontainers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) をインストールする。

## 実行手順

### Github Codespaces で利用する場合

1. 右上緑色の `< > Code　▼` ボタンをクリック

1. `Codespaces` のタブを選択

1. `Create codespace on mastar` を選択

### ローカル環境で利用する場合

1. 本リポジトリをクローンまたは、右上緑色の `< > Code　▼` ボタン　→ `Local`　→ `Download ZIP` からダウンロードし、そのまま解凍する。

1. Makefile を開いて、5 行目の `you@example.com` および 6 行目の `Your Name` を自身の環境に合わせ編集する。（コミット等を行わないのであれば本手順を飛ばしても問題ありません。）

   ```Makefile
   @git config --global user.email "you@example.com"
   @git config --global user.name "Your Name"
   ```

1. Windows は `ctrl + shift + P`、 Mac は `cmd + shift + P` でコマンドパレットを開き、`Dev containers: Open Folder in Container...` を選択し、ダウンロードした本リポジトリのフォルダ（例：zipをダウンロードした場合は `foundryup-mastar` フォルダ）の中に入り、`開く` を選択する。
