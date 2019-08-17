---
layout: post_layout
title:  jekyll安装及环境搭建、Github page博客
time: 2019年08月15日 星期四
location: 北京
pulished: true
excerpt_separator: "```"
---

我的第一篇 github 博客

- 安装jekyll软件支持
  - 安装gcc编译包 ：sudo apt install build-essential
  - 安装Ruby： sudo apt install ruby-full
  - 安装RubyGems ：sudo apt install rubygems
  - sudo apt-get install -y nodejs
- 安装jekyll
  - sudo gem install jekyll
- 查看jekyll是否安装成功
  - jekyll -v查看版本
- jekyll运用
  - jekyll new blog 
  - cd blog
  - bundle install
  - jekyll  serve
  - 登陆网址localhost:4000访问本地环境
- jekyll进行博客搜索
  - 访问jekyllthenme选择模板
- github进行代码fork及github page创建
  - github上fork别人代码
  - 登陆自己github，选择fork的项目，更改Repository name为"用户名.github.io"
  - 登陆“用户名.github.io”进行网站访问
- git 克隆远程库fork的博客
  - git clone git@github.com:用户名/用户名.github.io
- 博客编辑
  - 用typora进行_posts文件夹下博客编辑
- vi 修改_config.yml进行配置文件编辑。
- git文件上传github
  - git add .
  - git  commit -m "说明"
  - git push origin master
- 访问 "用户名.github.io"查看自己的博客