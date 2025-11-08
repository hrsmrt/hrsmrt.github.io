---
layout: default
title: matplotlib スタイルシート
permalink: /matplotlib/style-sheet
nav_exclude: true
---

## matplotlib スタイルシート

以下のようなstyle sheetを、`hogehote.style`などに保存し、`make_figure.py`などで`plt.style.use(path/to/stylesheet)`とすれば、styleが反映される。

プレゼン用style sheet
```
figure.constrained_layout.use: True

# font
## 前にあるものが優先的に使われる
font.sans-serif: Noto Sans JP, DejaVu Sans, Bitstream Vera Sans, Computer Modern Sans Serif, Lucida Grande, Verdana, Geneva, Lucid, Arial, Helvetica, Avant Garde, sans-serif
# Noto Sans JP
# MS mincho
# Hiragino Mincho ProN
# Hiragino Sans
# Hiragino Maru Gothic Pro
# Times New Roman
# Helvetica Neue
font.size : 18
pdf.fonttype: 42

# mathtext
# mathtext.fontset: cm

# axes
axes.grid: True
axes.linewidth : 1.0

# tick
xtick.direction : in
ytick.direction : in
xtick.major.width : 0.55
ytick.major.width : 0.55

# savefig
savefig.dpi: 300
savefig.bbox: tight
savefig.pad_inches: 0.05
```