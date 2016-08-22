---
layout: default
date:   2014-04-06 23:26:12
photo: 1.png
caption_header: 美澜城 125平
caption:
categories: about
permalink:
---

## Windows 7 安装 ruby jekyll 在github pages 上搭建静态个人博客

1. Jekyll 介绍
  Jekyll是一个静态站点生成器，它会根据网页源码生成静态文件。它提供了模板、变量、插件等功能，可以用来生成整个网站。

  Jekyll生成的站点，可以直接发布到github上面，这样我们就有了一个免费的，无限流量的，有人维护的属于我们的自己的web网站。Jekyll是基于Ruby的程序，可以通过gem来下载安装。

2. 安装ruby 下载ruby [http://rubyinstaller.org/downloads](http://rubyinstaller.org/downloads/)
 下载证书 [cacert.pem](http://curl.haxx.se/ca/cacert.pem )
 放在 ruby 安装目录 例如： c:\ruby2000\bin

 设置环境变量

 ![环境变量1](/img/h/1.png)
 ![环境变量1](/img/h/2.png)
 ![环境变量1](/img/h/3.png)

 修改默认源
  `gem sources`
  `gem sources -a https://ruby.taobao.org/`
  `gem sources -r https://rubygems.org/`
  最后的斜杠不能少

3. 安装 jekyll
  在 命令行 运行 `gem install jekyll -V`

4. 安装 github
  可以参照 https://pages.github.com
  下载github [https://desktop.github.com](https://desktop.github.com)

5. 项目目录输入 `jekyll server` 在浏览器 输入 http://127.0.0.1:4000 就可以访问了

  >参考网址
  https://pages.github.com
  https://jekyllrb.com/
  https://rubygems.org
