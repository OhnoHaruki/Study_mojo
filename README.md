# MOjOを使ってみる

## 概要

Mojoを使ってみたいという単純な興味から始めた。  
公式ドキュメントは[こちら](https://docs.modular.com/mojo/manual/get-started/)

## セットアップ

インストールドキュメントは[こちら](https://docs.modular.com/mojo/manual/install/)  

1. まずはPythonのセットアップする。(UVで行った)
    - `$ uv init`
    - `$ uv venv && source .venv/bin/activate`

2. Mojoをインストールする。(安定版か最新版があるが、今回安定版)
    - `$ uv pip install mojo --extra-index-url https://modular.gateway.scarf.sh/simple/`

3. Mojoのバージョンを確認する(バージョンが出力されればok)
    - `$ mojo --version`

- VSCodeを使用している場合の拡張機能は[こちら](https://marketplace.visualstudio.com/items?itemName=modular-mojotools.vscode-mojo)
  - コード補完や、ドキュメントヒント表示など行える。

## コードの実行

以下のコマンドで実行。

```zsh

$ mojo hello.mojo

Hello World!
```

```zsh

$ mojo hello_2.🔥

Hello World!
```

