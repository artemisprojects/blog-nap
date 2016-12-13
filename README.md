# blog-nap 使用说明

## 环境准备

[blog-nap 网站](http://blog.nxap.org) 由[hexo](http://hexo.io) 生成，请使用`npm install hexo-cli -g`命令安装hexo环境

## 从github获取既有代码

`git clone https://github.com/artemisprojects/blog-nap.git`

## 安装hexo工程依赖包

`cd blog-nap`

`npm install` 或 `tar axf node_modules.tar.gz`

## 添加、修改内容

使用`hexo new "article title"` 创建新文章或编辑`source\_posts\`目录下已有markdown文件修改已有文章的内容

## 发布内容

使用`hexo generate` 命令重新生成网页内容，并使用`hexo deploy`命令发布生产的内容到网站。

## 提交更新内容

按git流程提交对blog-nap的hexo内容所做修改（`git add .` -> `git commit -a` -> `git push origin master`）。
然后执行`hexo d -g`，hexo根据markdown文件生成静态html页，并将其push到`gh-pages`分支上去。
