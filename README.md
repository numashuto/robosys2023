# plusコマンド
![test](https://github.com/numashuto/robosys2023/actions/workflows/test.yml/badge.svg)

標準入力から読み込んだ数字を足す。

## インストール方法
以下のコマンドを実行
```
$ git clone https://github.com/numashuto/robosys2023.git
```

## 使用方法
以下のコマンドで「robosys2023」ディレクトリに移動
```
$ cd robosys2023
```
実行例
```
$ seq 10 | ./plus
55
```

## 必要なソフトウェア
* Python
  * テスト済み: 3.7〜3.10

## テスト環境
* Ubuntu 20.04

## ライセンス
* このソフトウェアパッケージは、３条項BSDライセンスの下、再頒布および使用が許可されます
* このパッケージのコードは，下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを，本人の許可を得て自身の著作としたものです．
     * [ryuichiueda/my_slides/robosys_2022](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022)
* © 2023 Shuto Numata
