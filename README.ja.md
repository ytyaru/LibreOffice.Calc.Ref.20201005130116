[en](./README.md)

# LibreOffice.Calc.Ref

　Calcで他のファイルにあるセルを参照する。

```
='file://フルパス'#$シート.セル
```
```
='file:///tmp/work/LibreOffice.Calc.Ref.20201005130116/src/namelist.ods'#$namelist.A2
```

# 注意

* ファイルを開くたび毎回`Enable Content`ボタンをクリックせねばならない
    * 参照データを最新にするために

![note0](https://github.com/ytyaru/LibreOffice.Calc.Ref.20201005130116/blob/master/doc/note0.png?raw=true)

# 開発環境

* <time datetime="2020-10-05T13:00:50+0900">2020-10-05</time>
* [Raspbierry Pi](https://ja.wikipedia.org/wiki/Raspberry_Pi) 4 Model B Rev 1.2
* [Raspbian](https://ja.wikipedia.org/wiki/Raspbian) buster 10.0 2019-09-26 <small>[setup](http://ytyaru.hatenablog.com/entry/2019/12/25/222222)</small>
* bash 5.0.3(1)-release

```sh
$ uname -a
Linux raspberrypi 5.4.51-v7l+ #1333 SMP Mon Aug 10 16:51:40 BST 2020 armv7l GNU/Linux
```

# インストール

```sh
git clone https://github.com/ytyaru/LibreOffice.Calc.Ref.20201005130116
```

# 使い方

```sh
cd LibreOffice.Calc.Ref.20201005130116/src
./run.sh
```

# 著者

　ytyaru

* [![github](http://www.google.com/s2/favicons?domain=github.com)](https://github.com/ytyaru "github")
* [![hatena](http://www.google.com/s2/favicons?domain=www.hatena.ne.jp)](http://ytyaru.hatenablog.com/ytyaru "hatena")
* [![mastodon](http://www.google.com/s2/favicons?domain=mstdn.jp)](https://mstdn.jp/web/accounts/233143 "mastdon")

# ライセンス

　このソフトウェアはCC0ライセンスである。

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png "CC0")](http://creativecommons.org/publicdomain/zero/1.0/deed.ja)

