## 关于项目

这是一个为了学习vue和webpack实现的一个todo-list demo。

### 本项目webpack的版本为4.36.1

因为教程中很多知识都比较老了，很多包现在都被弃用。为了与时俱进，我用了最新版本的webpack，并使用了官方文档推荐的新npm包，来代替已经被弃用的包，具体包的配置，请大家参考[package.json](https://github.com/carrieguo/vue.js-todolist/blob/master/package.json)

将项目克隆到本地之后，可通过以下三种方式下载项目依赖的包
1. 通过npm 命令，但是由于国内网速限制，很容易失败(在国外或者有VPN的同学可以使用)
```sh
npm install
```
2. 通过cnpm命令, 需要安装淘宝镜像 http://npm.taobao.org/ 
```sh
cnpm install
```
3. yarn (推荐使用yarn,需要先安装yarn https://yarnpkg.com/lang/zh-hans/docs/install/#windows-stable)
```sh
yarn
```

运行命令
```sh
npm run dev
```