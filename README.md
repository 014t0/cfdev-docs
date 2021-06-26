# cfdev-docs

## 環境構築手順

1. PCF Dev をインストールする
1. cf コマンドのインストール  
1. PCF Dev の起動
    1. `cf dev start` コマンドで起動する
1. cf login する
    1. ```bash
        cf login --sso -a https://api.run.pivotal.io
        ```
1. Apps Manager にアクセスする
    1. https://console.run.pivotal.io/