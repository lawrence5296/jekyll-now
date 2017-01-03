---
layout: post
title: Ubuntu 16.04を入れて初めにやったこと。
---

<h1>とりあえずCAPSLOCKは障害でしかないので、CapsLockを左Ctrlキーにマッピングを変更。</h1>
Linuxディストリビューションにかかわらず、キーバインドを設定する方法をいくつかある。
ただしバージョンによっても使えるものは異なる模様。
検索していくつかの方法を試みたが、Ubuntu16.04では下記の手法で実行できた。
xmodmapによるやり方ではできたあと何故か戻ってしまう時があった。
$ xev コマンドで、キーボード入力でどの操作が行われているかわかる。
<a href=http://blog.cnu.jp/blog/2014/05/12/use-xkb/>xkbでキーバインドを変更する。</a>

![_config.yml]({{ site.baseurl }}/images/config.png)

The easiest way to make your first post is to edit this one. Go into /_posts/ and update the Hello World markdown file. For more instructions head over to the [Jekyll Now repository](https://github.com/barryclark/jekyll-now) on GitHub.
