# 结合markdown、sublime text、puer来写作

[TOC]
## why markdown
引用维基百科的一段介绍
> Markdown 是一种轻量级标记语言，创始人为约翰·格鲁伯（John Gruber）。它允许人们“使用易读易写的纯文本格式编写文档，然后转换成有效的XHTML(或者HTML)文档”。这种语言吸收了很多在电子邮件中已有的纯文本标记的特性。

目前，markdown非常的流行。比如，javascript领域大名鼎鼎的《ECMAScript 6入门》就是使用使用markdown完成的。

## why sublime text
很多人推荐我使用，轻量、高效、插件众多，前端开发必备。个人非常喜欢command palette。

## puer介绍
live reload是一种非常优秀的提高前端开发效率的思想，那么puer即是一个这种思想的实现。它基于nodejs且开源，github上的star有1000多，这款国产的插件易用性还是可以的。有一款国外的更流行的live reload实现叫做browser-sync，有时间一定要尝试一下。puer和markdown的结合使用马上就会讲到。puer工具地址见参考。

## markdown preview 插件介绍
sublime text以及其plugin的安装见官方的文档。plugin文档以及markdown preview插件文档位于参考列表中。
引用官方的一段介绍
> Preview and build your markdown files quickly in your web browser from sublime text 2/3.

目前我所了解到到几个小技巧分享一下

- 使用Sublime text Build命令来快速导出html文件，结合puer就能够实现方便快速的预览。当然，如果能够有支持实时预览对工具就更好了。
- 使用command palette可以快速的打开markdown cheat sheet，这是一个示例文件,用过Build可以生成效果预览。这对markdown初学来说非常有用。
- 使用[TOC]来增加文档目录.


## 此博客由github pages驱动
thanks to github! 本博客所在仓库地址：https://github.com/hardeywang/hardeywang.github.io

## 最后
如果你对本文有任何的意见和建议，欢迎在我的github blogs issues区留言讨论。

## 参考
- [维基百科：markdown](https://zh.wikipedia.org/wiki/Markdown)
- [《ECMAScript 6入门》](web版本]http://es6.ruanyifeng.com)
- [sublime text插件的安装管理](https://packagecontrol.io/)
- [Markdown Preview](https://packagecontrol.io/packages/Markdown%20Preview)
- [puer](http://leeluolee.github.io/2014/10/24/use-puer-helpus-developer-frontend/)
