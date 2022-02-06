# docsify :id=begin

## 官网

> [docsify 官网中文版](https://docsify.js.org/#/zh-cn/)

> [docsify Official website](https://docsify.js.org/#/)

## docsify 的简单使用

```bash
$ npm i docsify-cli -g
安装 docsify

$ docsify init ./docs
创建一个 docsify 

接下来可以简单的修改 README.MD 文件

$ docsify serve docs
本地预览

```

## 部署到 github page 上面

```bash

创建仓库，然后复制该仓库中的链接<HTTPS_URL>，比如 https://github.com/Linhieng/docsify.git

$ git clone <HTTPS_URL>
克隆远程仓库

$ docsify init ./docs
初始化 docsify （可以修改 README.md）

$ git push origin master
推送到云端

然后都 github page 中开启 page，并且设置路径为 docs 就可以看到效果了

```


