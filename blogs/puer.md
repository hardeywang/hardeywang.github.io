# puer入门之web前端开发实时刷新

[TOC]
## puer介绍
在我的一篇历史文章[《结合markdown、sublime text、puer来写作》](https://hardeywang.github.io/blogs/first-blog-with-markdown-and-sublimetext.html#puer)里有介绍过这个工具。总的来说，易用性在我看来是不错的。

## 必要的环境支持：nodejs
nodejs官方资源见尾部的参考。
引用官方的简短介绍
> Node.js® is a JavaScript runtime built on Chrome's V8 JavaScript engine. Node.js uses an event-driven, non-blocking I/O model that makes it lightweight and efficient. Node.js' package ecosystem, npm, is the largest ecosystem of open source libraries in the world.

## 你需要了解npm的基本使用
入门教程推荐官方npm Getting Started，URL见尾部参考。

## puer的安装
	npm install puer -g

在mac环境下，你可能需要加上sudo来使用更高的权限
	
	sudo npm install puer -g

## sublime text plugin:terminal
> Launch terminals from the current file or the root project folder

在使用puer时，这个插件能够助你一臂之力。URL见参考。sublime text和插件相关资料请见我的一篇历史文章[《结合markdown、sublime text、puer来写作》](https://hardeywang.github.io/blogs/first-blog-with-markdown-and-sublimetext.html#markdown-preview).

## puer之实时刷新
本文只介绍前端刷新的功能，但puer的功能不只有这一点。
使用方法，命令行下切换到你指定的静态服务器目录，然后执行puer命令，puer会默认为你打开http://localhost:8000页面，编辑静态服务器目录下的文件，会实时更新页面。

	cd /path/to/workspace
	puer

## 此博客由github pages驱动
thanks to github! 本博客所在仓库地址：https://github.com/hardeywang/hardeywang.github.io

## 最后
如果你对本文有任何的意见和建议，欢迎在我的github blogs issues区留言讨论。

## 参考
- [puer官方](http://github.com/leeluolee/puer)
- [nodejs官方](https://nodejs.org/)
- [npm官方 Getting Started](https://docs.npmjs.com/)
- [sublime text plugin:terminal 官方](https://packagecontrol.io/packages/Terminal)