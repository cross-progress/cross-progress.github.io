# Cross Progress Official HP

[https://cross-progress.github.io/](https://cross-progress.github.io/)

![cross-progress](figure/logo.png)

## 編集用メモ

以下では，Ubuntu 18.04, 20.04での編集作業を想定しています．

### セットアップ

以下のコマンドを実行してください．本リポジトリをクローンしたディレクトリでやるのがオススメです．

```bash
sudo apt install ruby-dev
git clone https://github.com/pages-themes/cayman
cd cayman
./script/bootstrap
```

最後のコマンドでは，`sudo`権限が必要な場合があります．

続いて以下のコマンドを実行します．

```bash
cd ${root of this repo.}
sudo bundle install
```

### プレビュー

以下のコマンドを実行すると，ブラウザで[localhost:4000](http://localhost:4000/)でプレビューできます．

```bash
bundle exec jekyll serve
```

本リポジトリには，上記コマンドを実行するシェルスクリプトファイルを用意しています．

```bash
./preview.sh
```

## Acknowledgement

This site is based on the [Cayman](https://github.com/pages-themes/cayman) theme.
