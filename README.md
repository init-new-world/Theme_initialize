# Theme_initialize
## 版本
* 0.1.1

## 功能
* 一个Firekylin的非官方主题。
* 整体基于Bootstrap 4和jQuery。
* 图标部分使用了Fontawesome。
* Markdown CSS使用了经过修改的github-markdown。
* 代码高亮使用了Highlight.js。
* 数学公式显示使用了MathJax。(使用了CDN,可以在layout.html中进行修改)
* 动态背景使用了经过修改的Canvas-Nest。
* 动态文字部分使用了typed.js。
* 参考了部分官方主题的格式和CSS。

## 什么是Firekylin?
* 一个博客系统，基于Node.JS和ThinkJS。[链接](https://github.com/firekylin/firekylin)

## 使用方法
* 放在你Firekylin主目录的<kbd>www/theme</kbd>的文件夹下，随后你可以在后台的<kbd>外观设置</kbd>-><kbd>主题管理</kbd>中选择。

## FAQ
* 为什么点击Tag后的Tag页面似乎有点丑？因为没有提供主题接口。
* 为什么这么大？我更换了Markdown渲染CSS，同时支持所有Highlight.js的语言高亮，如果对高亮不满意的可以在layout.html中进行更换，或是删除<kbd>css/styles</kbd>中的多余显示风格。
* 为什么后台主题没改？一样也没有接口= =
* 轮播图如何更改&取消？在<kbd>res/photos</kbd>中更换图片。取消或进行更多修改请参照layout.html。(没接口啊！这样修改就只能直接在html上改了)

## 反馈意见
* 反馈意见请提出Issue，不过我可能没时间看QAQ

## 更新日志
* 0.1.2:修正了一个搜索界面的BUG
* 0.1.1:增加了一个小的H5文字效果
* 0.1.0:修正了主题内部的一些语法错误，改进了git存储方式
* 0.0.3:增加了Canvas-Nest动态背景，改进了部分代码风格，根据舍友的建议将footer固定在底部，统一了页面风格，修改了评论框样式
* 0.0.2:加入了图片轮播，调整了自适应的效果，修正了无文章时的显示风格
* 0.0.1:最初的版本

## 壁纸版权
* 如果有默认轮播壁纸的版权问题，请用Issue告诉我，我确认后将立刻删除有版权争议的轮播壁纸。

## 开源许可
* 本工程由Init_new_world(Initialize)独立开发完成，请遵循GPL V3开源许可证。
