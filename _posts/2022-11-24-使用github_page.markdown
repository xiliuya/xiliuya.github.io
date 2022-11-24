---
layout: post
title:  "使用github_page"
date:   2022-11-24 18:45:20 +0800
categories: jekyll update
---

# Table of Contents

1.  [安装jekyll](#orgfd57645)
2.  [新建github page 仓库](#org0f45115)
3.  [将生成的页面上传到仓库](#org5fcfa0a)
4.  [测试并使用页面](#orge9ef5b5)

配置github page


<a id="orgfd57645"></a>

# 安装jekyll

通过:

    gem install bundler jekyll

安装jekyll
配置环境变量 **$PATH** 加入 **~/.local/share/gem/ruby/3.0.0/bin**


<a id="org0f45115"></a>

# 新建github page 仓库

点击 new 建立一个名为 username.github.io 的public 仓库(username 改为用户名) 


<a id="org5fcfa0a"></a>

# 将生成的页面上传到仓库

    cd username.github.io
    jekyll new .
    git add -A
    git commint -m "first commit"
    git push origin main


<a id="orge9ef5b5"></a>

# 测试并使用页面

放弃使用主题 由于不符合个人对于简洁而美的要求 
**主要是太麻烦懒得弄**

