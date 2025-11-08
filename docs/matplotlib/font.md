---
layout: default
title: matplotlib フォント
permalink: /matplotlib/font
nav_exclude: true
---

## matplotlib フォント

MatplotlibのデフォルトのフォントはDejaVu fonts([Fonts in Matplotlib — Matplotlib documentation](https://matplotlib.org/stable/users/explain/text/fonts.html))で、このままでは日本語は使えない。したがって、日本語を使いたい場合は、フォントを変更する必要がある。matplotlibでは、システムで利用できるフォントが使えるので、それぞれの環境で使用可能なフォントから選択する。

フォントを追加するときは、フォントをシステムにインストールし、matplotlibのフォント関連のキャッシュ(`~/.matplotlib/`内などにある)を削除するか、addfontメソッド( [matplotlib.font_manager — Matplotlib documentation](https://matplotlib.org/stable/api/font_manager_api.html#))を用いる。

個人的な発表スライド用のおすすめフォントは、Noto Sans JP([Noto Sans Japanese - Google Fonts](https://fonts.google.com/noto/specimen/Noto+Sans+JP))。フリーなので、MacやLinuxなど環境によらず統一して用いることができる。

`matplotlib.font_manager`モジュール([matplotlib.font_manager — Matplotlib documentation](https://matplotlib.org/stable/api/font_manager_api.html))を使って、フォントを操作できる。

使用例
```python
# 使用可能なフォント一覧の取得
import matplotlib.font_manager as fm
font_list = fm.get_font_names()
for font in font_list:
    print(font)
```

`import matplotlib`ではfont_managerは読み込まれないので注意。
