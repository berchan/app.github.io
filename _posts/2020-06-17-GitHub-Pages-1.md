---
layout:     post
title:      初识GitHub Pages
date:       2020-06-17
summary:    GitHub Pages 是一项免费静态站点托管服务，服务由GitHub提供
categories: GitHub GitHub Pages
---

GitHub Pages 是一项免费静态站点托管服务，由GitHub提供。该服务会直接从GitHub仓库获取HTML、CSS和JS文件，构建运行文件（可选），然后发布网站。
### GitHub Pages站点类型
GitHub Pages 分为项目、用户和组织三种类型站点。
#### 项目站点
项目站点连接到GitHub上托管的特定项目。

功能特性：
* 创建无限制
* 站点源文件与项目存储同一仓库
* 站点默认访问地址http(s)://\<custom\>.github.io/\<repository\>
* 项目站点的默认发布来源是gh-pages分支，也可以设置master分支为发布来源

#### 用户和组织站点
用户和组织站点连接到特定的GitHub账户
* 只能创建一个
* 仓库必须命名为\<custom\>.github.io,同时仓库必须由自己账户创建
* 站点默认访问地址：http(s)://\<custom\>.github.io
* 默认发布来源是master分支，无法自定义发布来源

#### GitHub Pages静态站点生成器
GitHub Pages 会发布推送到仓库的任何静态文件。
1. 可以直接创建静态文件推送到仓库。
2. 使用静态站点生成器构建站点。
3. GitHub Pages默认使用Jekyll构建站点。如果想使用其他生成器，可以在发布来源的根目录中创建.nojekyll空文件禁止，然后安装静态站点生成器说明在本地构建站点。
4. GitHub Pages 不支持服务器端语言，例如 PHP、Ruby 或 Python

#### 使用限制
* GitHub Pages 源仓库建议的限制为 1GB。

* 发布的 GitHub Pages 站点不得超过 1 GB。

* GitHub Pages 站点的软带宽限制为每月 100GB。

* GitHub Pages 站点的软限制为每小时 10 次构建。







[1] [关于 GitHub Pages - GitHub 帮助](https://help.github.com/cn/github/working-with-github-pages/about-github-pages)

