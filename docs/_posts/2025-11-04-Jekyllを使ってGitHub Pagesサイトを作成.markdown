---
layout: post
title:  "Jekyllを使ってGitHub Pagesサイトを作成"
date:   2025-11-04 22:59 +0900
categories: jekyll update
---

以下を参考にしてGitHub Pagesサイトを作成。
- [GitHub Pages のドキュメント - GitHub Docs](https://docs.github.com/ja/pages)
- [GitHub PagesとJekyllについて - GitHub Docs](https://docs.github.com/ja/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll)
- [BundlerでJekyllを使う \| Jekyll • シンプルで、ブログのような、静的サイト](https://jekyllrb-ja.github.io/tutorials/using-jekyll-with-bundler/)

Jekyllの日本語訳ページはこちら: [Jekyll • シンプルで、ブログのような、静的サイト \| プレーンテキストを静的サイトやブログに変えましょう](https://jekyllrb-ja.github.io/)

以下に、初期化時に書かれている解説を残しておく。

> You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.
> 
> Jekyll requires blog post files to be named according to the following format:
> 
> `YEAR-MONTH-DAY-title.MARKUP`
> 
> Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `MARKUP` is the file extension representing the format used in the file. After that, include the necessary front matter. Take a look at the source for this post to get an idea about how it works.
> 
> Jekyll also offers powerful support for code snippets:
> 
{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}
> 
> Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].
> 
> [jekyll-docs]: https://jekyllrb.com/docs/home
> [jekyll-gh]:   https://github.com/jekyll/jekyll
> [jekyll-talk]: https://talk.jekyllrb.com/


また、初期化時の「about」の内容も残しておく。

> This is the base Jekyll theme. You can find out more info about customizing your Jekyll theme, as well as basic Jekyll usage documentation at [jekyllrb.com](https://jekyllrb.com/)

> You can find the source code for Minima at GitHub:
> [jekyll][jekyll-organization] /
> [minima](https://github.com/jekyll/minima)

> You can find the source code for Jekyll at GitHub:
> [jekyll][jekyll-organization] /
> [jekyll](https://github.com/jekyll/jekyll)

> [jekyll-organization]: https://github.com/jekyll

これを参考にテーマを変更したり、レイアウトを編集([テーマ#テーマのデフォルトを上書きする \| Jekyll • シンプルで、ブログのような、静的サイト](https://jekyllrb-ja.github.io/docs/themes/#%E3%83%86%E3%83%BC%E3%83%9E%E3%81%AE%E3%83%87%E3%83%95%E3%82%A9%E3%83%AB%E3%83%88%E3%82%92%E4%B8%8A%E6%9B%B8%E3%81%8D%E3%81%99%E3%82%8B))することができる。
