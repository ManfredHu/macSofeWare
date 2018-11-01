# macSofeWare
常用mac软件

## 终端Shell
终极解决方案 iTerm2 + zsh
再定义一些alias和自动登陆服务器的脚本，命令敲的飞起

## [Xee^3] 打不了数学公式了，三次方的意思,图片预览工具
预览下一张图是空格，不是向右向下方向键

## [截图](https://itunes.apple.com/cn/app/id1059334054) （屏幕截取&录制）
有屏幕录制和屏幕截图，默认快捷键为
- 区域截图 `command+shift+a`
- 屏幕录制 `command+shift+r`

## 编辑器
WebStorm 大项目用，搜索方便
SublimeText 笔记轻量，但是在大项目感觉没WebStorm好用
用过SublimeText,WebStorm现在已经投向vscode，体验过的最简单配置&好用没有之一。

## FTP&SFTP文件上传
SublimeText 可以装插件
FileZilla 可以试试
或者是shell的命令行直接实现哈哈哈
VScode的话有个sftp插件

## SVN
Mac:Cornerstone
Windows的话是小乌龟系列

## Paste(复制粘贴管理)
有时候复制的东西多了，会很蛋疼，这个可以管理近期复制的东西

## Mounty for NTFS for Mac（NTFS解决方案）
U盘插Mac不起作用，是Mac不支持NTFS的文件格式。

## 字体
有时候项目用到了特别的字体，然后才用几个字的那种。通常会压缩字体文件，剔除没用到的字体
这种情况，推荐**字蛛font-spider**
### [字蛛font-spider](http://font-spider.org/) 可以爬页面的字体并剔除无用字体

还有一种情况是，多种字体要合并成一个ttf，然后你还没有HTML。
这种情况，推荐**fontmin**，输入文字和选择字体来生成自定义的字体文件
### [fontmin](http://ecomfe.github.io/fontmin/#usage) IDE合并多种字体到一个字体文件

## 多电脑共享鼠标键盘
[Synergy](https://symless.com/synergy)

## Git
SourceTree或者命令行

# 前端相关
## 搭建组件库的模版
[Ant Design of Vue](https://tangjinzhou.gitee.io/ant-design-vue/docs/vue/introduce-cn/)

# npm库
### [ora](https://github.com/sindresorhus/ora)  终端过程展示用的，可以显示Loading什么
### [moment](https://github.com/moment/moment) 时间处理相关，基本时间相关都是这个库了
### [rimraf](https://github.com/isaacs/rimraf) 删除文件
### [chalk](https://github.com/chalk/chalk) 多颜色输出文本到终端
### [babel&webpack全家桶](https://www.webpackjs.com/guides/)
  - babel-core babel-loader babel的核心模块和loader模块
  - babel-preset-env 支持ES新语法特性模块
  - [html-webpack-plugin](https://github.com/jantimon/html-webpack-plugin) 支持生成入口html并内联生成的js模块
  - webpack & webpack-cli 打包器和命令行工具
  - [clean-webpack-plugin](https://www.npmjs.com/package/clean-webpack-plugin) 清理文件目录工具
  - [webpack-dev-server](https://www.npmjs.com/package/webpack-dev-server) webpack自动打开浏览器插件
  - [vue-loader](https://github.com/vuejs/vue-loader) 此 loader 支持用于 vue 组件的 HMR，提供开箱即用体验。
  
# 开源
### [shields](https://shields.io/#/) 徽标制作
### [travis-ci](https://travis-ci.org) 集成测试
### [jest](https://jestjs.io/) 单元测试脚本
### [codecov](https://codecov.io/) 覆盖率测试

