# ros_setup_scripts_Ubuntu20.04

ROS（Melodic Morenia）をUbuntu 20.04に一発でインストール・セットアップするシェルスクリプトです。

# scripts

## step0.bash

このリポジトリを使う前の処理を書いたシェルスクリプトです。ブラウザ等で開いてコピペで使用します。

## step1.bash

これを実行すると、一度ログアウト（あるいはsource ~/.bashrc）したのちにroscore
が動くようになります。ロケールが設定されていない場合は、

    LANG=C roscore

で動作確認をします。ロケールの設定を行いたい場合、日本語環境でよければ次の
locale.ja.bashを実行してください。

## locale.ja.bash

Ubuntuに日本語環境をセットアップして、roscoreがLANG=C無しで動くようにします。

# 環境

以下で検証しました。

* Ubuntu Desktop 20.04

