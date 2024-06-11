# Foundryup on Docker

## 事前準備

1. VSCode をインストールする。

1. [本サイト](https://matsuand.github.io/docs.docker.jp.onthefly/get-docker/) のリンクから、 Docker をダウンロード・インストールする。

1. [本サイト](https://qiita.com/75ks/items/b2961e8562c353f42d21)などを参考に VSCode に [Devcontainers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) をインストールする。

## 実行手順

### Github Codespaces で利用する場合

1. 右上緑色の `< > Code　▼` ボタンをクリック

1. `Codespaces` のタブを選択

1. `Create codespace on mastar` を選択

### ローカル環境で利用する場合

1. 次のコマンドを実行して、このリポジトリをクローンまたは、右上緑色の `< > Code　▼` ボタン　→ `Local`　→ `Download ZIP` からダウンロードし、そのまま解凍する。

1. Makefile を開いて、5 行目の `you@example.com` および 6 行目の `Your Name` を自身の環境に合わせ編集する。（コミット等を行わないのであれば本手順を飛ばしても問題ありません。）

   ```Makefile
   @git config --global user.email "you@example.com"
   @git config --global user.name "Your Name"
   ```

1. Windows は `ctrl + shift + P`、 Mac は `cmd + shift + P` でコマンドパレットを開き、`Dev containers: Open Folder in Container...` を選択し、ダウンロードした本リポジトリのフォルダ（例：zipをダウンロードした場合は `foundryup-mastar` フォルダ）の中に入り、`開く` を選択する。
