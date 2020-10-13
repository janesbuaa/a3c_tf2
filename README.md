# A3C tensorflow 2

## 概要

このプログラムは[【強化学習】実装しながら学ぶA3C【CartPoleで棒立て：1ファイルで完結】](https://qiita.com/sugulu/items/acbc909dd9b74b043e45)に記載されているコードをTensorFlow 2、Google Colaboratory上で動かすことができるように修正を加えたものです。

A3Cのアルゴリズムに関しては、上記の参照元か[元論文](http://proceedings.mlr.press/v48/mniha16.pdf)を参照してください。

また、Google Colaboratory 上で gymの結果を正常に出力するために[【強化学習】OpenAI Gym を Google Corab上で描画する方法 (2020.6版)](https://qiita.com/ymd_h/items/c393797deb72e1779269)の`gym-notebook-wrapper`を使用しています。

## 実行結果

![result](https://github.com/kazuaki-i/a3c_tf2/blob/master/cartpole.gif?raw=true)

## TODO
- コード内コメント整理
- パラメータ設定方法まとめ
- cartpole以外のタスクの実装
