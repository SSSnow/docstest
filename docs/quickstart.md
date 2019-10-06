# 快速开始

推荐安装 `docsify-cli` 工具，可以方便创建及本地预览文档网站。

```bash
npm i docsify-cli -g
```

## 初始化项目

如果想创建自己文档项目，则在自己的项目文档里执行如下语句，则会创建 一个docs的文件夹，然后即可在`./docs` 目录里写文档。

```bash
docsify init ./docs
```

如果在已创建好的文档系统下，直接开始文档编写，则可以跳过该步。

## 开始写文档

初始化成功后，可以看到 `./docs` 目录下创建的几个文件

- `index.html` 入口文件
- `README.md` 会做为主页内容渲染
- `.nojekyll` 用于阻止 GitHub Pages 会忽略掉下划线开头的文件

如果在已创建好的文档系统下，直接开始文档编写，则可以跳过该步。

## 本地文档预览

运行一个本地服务器通过 `docsify serve` 可以方便的预览效果，而且提供 LiveReload 功能，可以让实时的预览。默认访问 [http://localhost:3000](http://localhost:3000/) 。

```bash
docsify serve docs
```

一般在编写文档之前，先开启本地文档服务器，然后用浏览器就可以访问[http://localhost:3000](http://localhost:3000/) 就可以查看当前文档编写状态。

## 开发工具

开发方式采用[markdown](https://baike.baidu.com/item/markdown/3245829?fr=aladdin)语言，通过团队私有[Bitbucket](https://bitbucket.org/innovation_future/develop_doc/src/master/)进行文档版本管理。

- [Typora](https://www.typora.io/):markdown编辑器
- [notepad++](https://notepad-plus-plus.org/):html编辑器
- [Bitbucket](https://bitbucket.org):版本管理工具

## 新建一个文档

1. 打开[_sidebar.md](_sidebar),在其中添加一个条目

   ```markdown
   [示例](example)
   ```

2. 在`\docs`文件夹下创建一个`example.md`的文件

**注意：文档名字需要用英文命名，且文档名需要与创建条目中的链接文件名相同**



