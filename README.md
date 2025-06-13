# XJTUSE-GUIDE

西安交通大学软件学院学习指南

> :fire: 目前该项目处于与大二上同步更新阶段，有更新电路，面向对象和数据结构。除此以外我们还有很多现存的内容。非常希望大家可以一起帮助完善内容，做成软工同学们一个交流学习的平台

## 为什么发起这个项目

首先不得不提的一点是**开源精神**！！！

起初只是[我](https://blog.csdn.net/qq_46311811)和[易俊泉学长](https://blog.csdn.net/weixin_47692652)把自己的笔记放在 CSDN 上让学弟学妹们参考，这种算是比较简单快捷的方式，但是由于 CSDN 并不是定制的笔记网站，因此相对来说内容会很乱，导致找资料什么的都不方便，泉佬也将自己的笔记[开源到了 Github ](https://github.com/yijunquan-afk/XJTUSE-NOTES)上，但是并没有制作一个阅读的网站，只能是 clone 后在本地看，也不是很方便。

我在 CSDN 发博客时候就在考虑要不要自己做个笔记网站来分享一些笔记内容，但是由于当时各种事情太忙加上我也比较懒，一直搁置到现在，最近中期答辩完了闲下来，然后慢慢开始准备这个项目，同时也是找到了一些学弟学妹也有相同的想法，希望将自己为考试准备的一些东西分享出来，毕业后就没有什么作用了，不如帮助学弟学妹们学习更简单一些，节省出一些时间去做自己想做的事情，同时避免一些重复劳动。

---- by 霍嘉

## 这个项目有什么

这个项目中主要包含有三个部分:

1. 对于所有课程的介绍，包括课内笔记，复习笔记，备考经验等
2. 毕业去向交流，包含四个模块：考研、保研、工作、出国，有对应的经验帖做介绍
3. 分流&转专业，主要是学长学姐们介绍自己为什么选择软件工程专业以及转专业的一些经验
4. 学长学姐有话说，主要是对于自己大学生活的一个回顾总结，以及对于学弟学妹们的一些建议

## 怎样使用这个项目
看到本页可能证明你会科学上网，建议以此方式浏览本网站，否则可能遇到加载不出等问题

本项目已部署到 Github Pages，可以[在线](https://xjtuse-guide.github.io/Xjtuse-Guide/#/)浏览

也可以将本项目拉取到本地运行，本项目使用 docsify 编译，因此本地需有 [nodejs](https://nodejs.org/en) 环境，建议下载 LTS 版本，下载后全局安装 docsify 依赖，然后运行即可。

```bash
git clone https://github.com/Hydrion-Qlz/XJTUSE-GUIDE.git
cd xjtuse-guide
npm i docsify-cli -g
docsify serve .
```

## Feature

通过集成 docsify 多样化的插件，文档支持 Latex 公式， [pdf文件渲染](How-to-Contribute?id=如何添加-pdf-文件预览)

## 如何参与贡献该项目

该项目由西安交通大学软件学院同学维护

- 如果你在阅读时候发现文档内容或者格式有问题，可以在仓库提 issue 或者修改后提 pr
- 如果添加新的文件，请尽可能在所有可能引用该文件的地方加入引入，确保侧边栏显示正确
- 如果你不懂如何自己提交，可提 issue 留下自己的联系方式，会有维护同学联系你进行文件上传
- [commit规范](https://blog.csdn.net/weixin_51474815/article/details/122652198)可以通过安装vscode插件git-commit-plugin来实现
- 部分图片来自[GitHub图床](https://blog.csdn.net/github_39655029/article/details/113181770)，若加载不出来，请进行科学上网

提交细节请参考[How to Contribute](How-to-Contribute.md)

> 如果是软工的同学，建议还是自己搞懂如何提 pr、如何使用 Github，算是一种必须掌握的技能

## 友群链接

- 西交软件保研交流群（qq）：636064912
  - 仅提供给西交软工专业的同学交流保研经验，入群验证请提供年级、学号和姓名。
- 西交软件学院水群（qq）：337125628
  - 给软件的大家一个聊天的qq群，本站有更新也会在群里面更新。

## TODO

- 内容完善
- 功能问题

  - [ ] [外链图片](https://docsify.js.org/#/zh-cn/configuration?id=crossoriginlinks)
  - [ ] [markdown 文档页内目录](https://github.com/mrpotatoes/docsify-toc)
  - [X] [pdf 渲染](https://github.com/lazypanda10117/docsify-pdf-embed)
  - [ ] 各种群的链接
  - [X] 分流&转专业模块
- [插件列表](https://docsify.js.org/#/awesome?id=plugins)

  - [X] [评论系统](https://docsify.js.org/#/zh-cn/plugins?id=disqus)
  - [ ] [在 github 编辑](https://docsify.js.org/#/zh-cn/plugins?id=%e5%9c%a8-github-%e4%b8%8a%e7%bc%96%e8%be%91)
  - [X] [分页](https://docsify.js.org/#/zh-cn/plugins?id=pagination)
  - [X] [导出 pdf 文件](https://github.com/meff34/docsify-to-pdf-converter) （插件不能集成使用，不做了）
  - [ ] [添加 footer](https://github.com/alertbox/docsify-footer)
  - [ ] [支持框图](https://github.com/Leward/mermaid-docsify)
  - [ ] [自动各级添加 header 前的数字](https://github.com/markbattistella/docsify-autoHeaders)
  - [X] [添加文档修改时间](https://github.com/pfeak/docsify-updated)
  - [X] [统计网站访问数量](https://github.com/mg0324/docsify-busuanzi)
