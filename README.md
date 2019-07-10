# vue-demo1

> demo1

## Build Setup

``` bash
# 全局安装 vue-cli
npm install --global vue-cli

# 创建一个基于webpack模板的新项目
vue init webpack demo

# 安装依赖
cd demo
npm run dev/start

# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

```

## Git命令行

``` bash

# 在目录中创建新的 Git 仓库
git init

# 拷贝一个 Git 仓库到本地
git clone [url]

# 将该文件添加到缓存
git add

# 查看在你上次提交之后是否有修改
git status

# 查看执行 git status 的结果的详细信息
git diff

# 使用 git add 命令将想要快照的内容写入缓存区， 而执行 git commit 将缓存区内容添加到仓库中。
git commit -m ‘’

# 用于取消已缓存的内容
git reset HEAD

# 简单地从工作目录中手工删除文件
git rm

# 用于移动或重命名一个文件、目录、软连接
git mv

# 将本地的master分支推送到origin主机，同时指定origin为默认主机，后面就可以不加任何参数使用git push了
git push -u origin

```

``` bash

build  项目都webpack配置文件
config 开发环境或线上环境的配置
node_modules 项目的依赖
src 源代码
  - main.js 项目的入口文件
  - App.vue 页面显示内容
static 项目的静态资源

```
