#Markdown

##什么是 Markdown?

Markdown 是在Github平台上用来书写的文档格式语言？(轻量，易学易写)  
可以在Github上很多地方使用它：

- [Gists](https://gists.github.com)
- Issues and Pull Requests 里的评论
- 扩展名为 `.md` or `.markdown` 的文件

更多详细[内容](https://google.com)

##例子

###列表

1. One
2. Two

- Unordered
	+ in
	+ ini
- out

###链接和图片

来这里打开[Github][github]

[github]:https://github.com

图片前面加感叹号`!`[] () or [][]

![privateinvestocat](https://octodex.github.com/images/privateinvestocat.jpg)

###标题和引用

 用# ## ### 表示 <h>.

 >用 > 来开始引用.

###代码

缩进四个空格(tab)

    if (isAwesome){
      return true
    }

code fencing 前后用三个 ***`*** 围起来

```
if (isAwesome){
  return true
}
```

##GFM(GitHub Flavored Markdown)

###代码高亮

语法高亮在前面 ***`*** 后面 javascript, python, c...

```javascript
if (isAwesome){
  return true
}
```
###任务列表

- [x] 支持@mentions, #refs, [links](), **formatting**, and <del>tags</del>
- [x] 需要列表的语法 (支持有序或无序的)
- [x] 这是完成了的项目
- [ ] 这是未完成的项目

###Emoji

:sparkles: :camel: :boom:

:point_right:[home page](http://emoji-cheat-sheet.com)

###@mentions

在 `@`后跟用户名或一个团队名。@organization/team-name

###表格

菜品 | 价格
---- | ----
馒头 | 1.5
包子 | 2


##各种入门例子

- [Markdown: Basics （快速入门）](http://wowubuntu.com/markdown/basic.html)
- [Markdown 完整语法说明 (简体中文版)](http://wowubuntu.com/markdown/)
- [Github: Mastering Markdown](https://guides.github.com/features/mastering-markdown/) GitHub 帮助中关于 Markdown 的语法帮助
- [MarkDown 语法团队规范](https://github.com/hzlzh/1MarkDown) 语法规范简洁版
- [Markdown Style Guide](http://www.cirosantilli.com/markdown-style-guide/) 语法规范复杂版
- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- [GitHub Flavored Markdown](https://help.github.com/articles/github-flavored-markdown/) GitHub 使用的 Markdown 语法，略微不同于标准 Markdown 语法。提供了一些更加简洁的语法，类似 URL autolinking, Strikethrough, Fenced code blocks, Syntax highlighting 等等
- [MultiMarkdown 介绍](http://fletcherpenney.net/multimarkdown/) 对 markdown 进行的扩展功能
- [Markdown Tutorial](http://www.markdowntutorial.com/) 来操作操作呗