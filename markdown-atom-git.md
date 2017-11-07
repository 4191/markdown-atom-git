## markdown-atom-git
```sh
https://github.com/4191/markdown-atom-git.git

```
---
## Atom-Git-Keymap
```sh
首先你自己系统上要安装git的环境，并且配置好用户名和邮箱，才能正常使用git 的功能 和git plus 这个扩展。
```
| 快捷键 | 功能 | 备注/描述 |
|:------:|:-----:|:--:|

这个包也提供了cmd-shift-B快捷键，用来显示所有未跟踪和已修改的文件列表。如果你运行git status，你在命令行中会看到相同的文件。g

---
## atom-keymap
| 快捷键 | 功能 | 备注/描述 |
|:------:|:-----:|:--:|
| ctrl-shift-M | markdown-preview | markdown预览|
| ctrl-d ctrl-u | find-and-replace:select-undo |取消上个选择 |
| ctrl-d ctrl-k | |跳过选择|
| ctrl-shift-p | |命令行，可以在里面输入，模糊查询快捷键|
|ctrl/cmd-T|| 搜索并快速打开项目中的文件 |
| | |

```sh
如果快捷键失灵，考虑是否是插件的快捷键关系影响了，
eg. ctrl-shift-M 、ctrl-d ctrl-u  失灵，就是因为emmet插件的快捷键覆盖了原来的快捷键；
处理办法：settings（ctrl-,）--> keybindings --> 搜索 ctrl-u --> 复制需要的keymap关系，粘贴在keymap.cson里；
原理：后来居上的覆盖原则。。
```

---
## 种草
|  |  |  |
|:------|:-----:|:----:|
|coffee| | |
|d3.js||||

---
## 书签
| 描述 | 网址 | 备注 |
|:------|:-----:|:----:|
|如何发布一个Atom的package| http://www.jianshu.com/p/98f99c20493c |发布Atom的package|
|atom编辑器和markdown| http://www.jianshu.com/p/f3fd881548ad |atom、markdown的文档、中文文档，还介绍了GFM（git for markdown）、pandoc（markdown编辑工具）|
|emmet语法手册| http://www.w3cplus.com/tools/emmet-cheat-sheet.html |前端码字效率提高工具|
|atom中文社区| https://atom-china.org |还是看英文的吧~|
|atom教程| https://www.w3cschool.cn/atom/ |片段补全等|
|atom教程| https://www.w3cschool.cn/atomflightmanualzhcn/uw6t1lo9.html |Atom中的版本控制 git|
|crlf| http://blog.csdn.net/ccfxue/article/details/52625806 |回车换行（windows）；unix只有换行lf；mac只有回车cf|

---
## 注册过的一些网站
| 网站名 | 网址 | 用户名 | 备注 |
|:------|:-----:|:----:|:----|
|简图网|http://jiantuku.com/#/ |419135619@qq.com|用于上传markdown所需图片，生成图片链接|
