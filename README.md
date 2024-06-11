# Foundryup on Docker

## 事前準備

1. VSCode をインストールする。

1. [本サイト](https://matsuand.github.io/docs.docker.jp.onthefly/get-docker/) のリンクから、 Docker をダウンロード・インストールする。

1. [本サイトの『左サイドバーの拡張機能で「Dev Containers」を検索し、インストール』](https://qiita.com/75ks/items/b2961e8562c353f42d21#%E5%B7%A6%E3%82%B5%E3%82%A4%E3%83%89%E3%83%90%E3%83%BC%E3%81%AE%E6%8B%A1%E5%BC%B5%E6%A9%9F%E8%83%BD%E3%81%A7dev-containers%E3%82%92%E6%A4%9C%E7%B4%A2%E3%81%97%E3%82%A4%E3%83%B3%E3%82%B9%E3%83%88%E3%83%BC%E3%83%AB) を参考に VSCode に [Devcontainers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) をインストールする。

## 実行手順

### Github Codespaces で利用する場合

1. 右上緑色の `< > Code　▼` ボタンをクリック

1. `Codespaces` のタブを選択

1. `Create codespace on mastar` を選択

### ローカル環境で利用する場合

1. 本リポジトリをクローンまたは、[本リンク](https://github.com/kanap0nta/foundryup/archive/refs/heads/master.zip) から zip ファイルをダウンロードし、そのまま解凍する。

1. Makefile を開いて、5 行目の `you@example.com` および 6 行目の `Your Name` を自身の環境に合わせ編集する。（コミット等を行わないのであれば本手順を飛ばしても問題ありません。）

   ```Makefile
   @git config --global user.email "you@example.com"
   @git config --global user.name "Your Name"
   ```

1. Windows は `ctrl + shift + P`、 Mac は `cmd + shift + P` でコマンドパレットを開き、`Dev containers: Open Folder in Container...` を選択し、ダウンロードした本リポジトリのフォルダ（例：zipをダウンロードした場合は `foundryup-mastar` フォルダ）の中に入り、`開く` を選択する。
