[![](https://img.shields.io/github/issues/zhouie/markdown-doc.svg)](https://github.com/zhouie/markdown-doc/issues)
[![](https://img.shields.io/github/forks/zhouie/markdown-doc.svg)](https://github.com/zhouie/markdown-doc/network) 
[![](https://img.shields.io/github/stars/zhouie/markdown-doc.svg)](https://github.com/zhouie/markdown-doc/stargazers)

> 欢迎关注微信公众号：**北岛向南**（id：nanzhouie）

![扫一扫 + 微信公众号](http://upload-images.jianshu.io/upload_images/9934558-5686cd20ab879929.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

---

**GitHub Pages：**[https://zhouie.cn/markdown-doc/](https://zhouie.cn/markdown-doc/)

<!-- MarkdownTOC -->

- [1. 认识 Markdown](#1-%E8%AE%A4%E8%AF%86-markdown)
  - [1.1 Markdown的优点](#11-markdown%E7%9A%84%E4%BC%98%E7%82%B9)
  - [1.2 Markdown 的现状](#12-markdown-%E7%9A%84%E7%8E%B0%E7%8A%B6)
  - [1.3 Markdown官方文档](#13-markdown%E5%AE%98%E6%96%B9%E6%96%87%E6%A1%A3)
- [2. 使用Markdown](#2-%E4%BD%BF%E7%94%A8markdown)
  - [2.1 标题](#21-%E6%A0%87%E9%A2%98)
  - [2.2 加粗、斜体 和 删除线](#22-%E5%8A%A0%E7%B2%97%E3%80%81%E6%96%9C%E4%BD%93-%E5%92%8C-%E5%88%A0%E9%99%A4%E7%BA%BF)
  - [2.3 列表](#23-%E5%88%97%E8%A1%A8)
  - [2.4 引用](#24-%E5%BC%95%E7%94%A8)
  - [2.5 分割线](#25-%E5%88%86%E5%89%B2%E7%BA%BF)
  - [2.6 插入链接](#26-%E6%8F%92%E5%85%A5%E9%93%BE%E6%8E%A5)
  - [2.7 插入图片](#27-%E6%8F%92%E5%85%A5%E5%9B%BE%E7%89%87)
  - [2.8 表格](#28-%E8%A1%A8%E6%A0%BC)
  - [2.9 角标](#29-%E8%A7%92%E6%A0%87)
  - [2.10 上下标](#210-%E4%B8%8A%E4%B8%8B%E6%A0%87)
  - [2.11 直接链接与邮箱](#211-%E7%9B%B4%E6%8E%A5%E9%93%BE%E6%8E%A5%E4%B8%8E%E9%82%AE%E7%AE%B1)
  - [2.12 换行](#212-%E6%8D%A2%E8%A1%8C)
  - [2.13 反斜杠](#213-%E5%8F%8D%E6%96%9C%E6%9D%A0)
  - [2.14 代码高亮](#214-%E4%BB%A3%E7%A0%81%E9%AB%98%E4%BA%AE)
  - [2.15  其他](#215-%E5%85%B6%E4%BB%96)
    - [2.15.1  锚点](#2151-%E9%94%9A%E7%82%B9)
    - [2.15.2 空格](#2152-%E7%A9%BA%E6%A0%BC)
    - [2.15.3 图片图床](#2153-%E5%9B%BE%E7%89%87%E5%9B%BE%E5%BA%8A)
    - [2.15.4 LaTeX公式](#2154-latex%E5%85%AC%E5%BC%8F)
      - [行内公式（`$`表示）](#%E8%A1%8C%E5%86%85%E5%85%AC%E5%BC%8F%EF%BC%88%24%E8%A1%A8%E7%A4%BA%EF%BC%89)
      - [整行公式（`$$`表示）](#%E6%95%B4%E8%A1%8C%E5%85%AC%E5%BC%8F%EF%BC%88%24%24%E8%A1%A8%E7%A4%BA%EF%BC%89)
    - [2.15.5 流程图、渲染序列图](#2155-%E6%B5%81%E7%A8%8B%E5%9B%BE%E3%80%81%E6%B8%B2%E6%9F%93%E5%BA%8F%E5%88%97%E5%9B%BE)
      - [流程图](#%E6%B5%81%E7%A8%8B%E5%9B%BE)
      - [渲染序列图](#%E6%B8%B2%E6%9F%93%E5%BA%8F%E5%88%97%E5%9B%BE)
    - [2.15.6 GitHub Emoji](#2156-github-emoji)
  - [2.16 Markdown的局限性](#216-markdown%E7%9A%84%E5%B1%80%E9%99%90%E6%80%A7)
- [3. Markdown 工具的选择](#3-markdown-%E5%B7%A5%E5%85%B7%E7%9A%84%E9%80%89%E6%8B%A9)
  - [3.1 Windows 平台](#31-windows-%E5%B9%B3%E5%8F%B0)
    - [3.1.1 Sublime](#311-sublime)
    - [3.1.2 简书](#312-%E7%AE%80%E4%B9%A6)
    - [3.1.3 Cmd Markdown](#313-cmd-markdown)
    - [3.1.4 马克飞象](#314-%E9%A9%AC%E5%85%8B%E9%A3%9E%E8%B1%A1)
    - [3.1.5 为知笔记](#315-%E4%B8%BA%E7%9F%A5%E7%AC%94%E8%AE%B0)
    - [3.1.6 Simple MarkPad](#316-simple-markpad)
    - [3.1.7 MarkPad](#317-markpad)
    - [3.1.8 Miu](#318-miu)
  - [3.2 Mac 平台](#32-mac-%E5%B9%B3%E5%8F%B0)
    - [3.2.1 Mou](#321-mou)
    - [3.2.2 Ulysses](#322-ulysses)
    - [3.2.3 Byword](#323-byword)
    - [3.2.4 typora](#324-typora)
    - [3.2.5 Quiver](#325-quiver)
    - [3.2.6 Alternote](#326-alternote)
    - [3.2.7 SnippetsLab](#327-snippetslab)
    - [3.2.8 MarkdownPad](#328-markdownpad)
  - [3.3 网页版\(线上\)](#33-%E7%BD%91%E9%A1%B5%E7%89%88%E7%BA%BF%E4%B8%8A)
  - [3.4 Others](#34-others)
  - [3.5 More](#35-more)
- [4. 推荐阅读](#4-%E6%8E%A8%E8%8D%90%E9%98%85%E8%AF%BB)
- [5. 补充](#5-%E8%A1%A5%E5%85%85)

<!-- /MarkdownTOC -->


<a id="1-%E8%AE%A4%E8%AF%86-markdown"></a>
## 1. 认识 Markdown

> HTML ( `HyperText Markup Language` ) 作为一种超文本标记语言 ( `Markup Language` ) 应运而生，无数的网页从此有了主次分明，层次清晰的格式。
> 如果将 HTML 比作一架重机枪，那么 Markdown 就是一把手枪，满足了主要的文本格式标记的需求，可是操作性却大大简化。
> 秉承 **易读易写** 的宗旨，Markdown 作为一种轻量级标记语言 ( `Lightweight Markup Language` ) ，让无数的程序猿和文字工作者爱不释手。

<a id="11-markdown%E7%9A%84%E4%BC%98%E7%82%B9"></a>
### 1.1 Markdown的优点

* 专注你的文字内容而不是排版样式，安心写作
* 轻松的导出 `HTML`、`PDF` 和本身的 `.md` 文件
* 纯文本内容，兼容所有的文本编辑器与字处理软件
* 随时修改你的文章版本，不必像字处理软件生成若干文件版本导致混乱
* 可读、直观、学习成本低

<a id="12-markdown-%E7%9A%84%E7%8E%B0%E7%8A%B6"></a>
### 1.2 Markdown 的现状

> 有时候一件事情的真相，不是来自于对它的思考，而是来自于对它的感觉。
> ——Stanley Kubrick

这是 John Grumber 最喜欢的用来解释 Markdown 设计初衷的一句话，Markdown 语言希望带来的就是纯粹的写作的感觉，旨在简洁、高效，也由于 Markdown 的易读易写，人们用不同的编程语言实现了多个版本的解析器和生成器。

目前不同的 Markdown 工具集成了不同的功能（但基础功能大致相同），例如 **流程图** 与 **时序图** ，**复杂表格** 与 **复杂公式** 的呈现。
我相信随着 Markdown 语法的逐渐普及开来，以后更多的平台会支持 Markdown 书写模式，并集成更加完整的功能模块。

虽然功能的 “**丰富**” 并没有什么本质的缺点，但这个程度一旦 “过” 了头，终归有些背离初衷，与 “易读易写” 出现矛盾，开始在编写的过程中觉得有些许吃力了。那这个时候，用户可能会觉得，不如使用专业化的工具来撰写更有效率。

<a id="13-markdown%E5%AE%98%E6%96%B9%E6%96%87%E6%A1%A3"></a>
### 1.3 Markdown官方文档

*   [创始人 John Gruber 的 Markdown 语法说明](http://daringfireball.net/projects/markdown/syntax)
*   [Markdown 中文版语法说明](https://zhouie.cn/markdown-doc/markdown-doc-syntax-zh)

> 了解一下 John Gruber

2004 年 John Gruber创造 Markdown 语言，14年间，Markdown 语言从程序员圈子中逐渐扩散开来，成为了越来越多的电脑写作者第一选择。

John Gruber 是一个资深果粉，他的个人博客 [Daring Fireball](https://daringfireball.net/) 被人戏称为 苹果官方喉舌博客。所以你应该懂为什么最好的 Markdown 编辑器都集中在 Mac 平台上了吧。

---
<a id="2-%E4%BD%BF%E7%94%A8markdown"></a>
## 2. 使用Markdown

<a id="21-%E6%A0%87%E9%A2%98"></a>
### 2.1 标题

Markdown 通过在行首添加 1 ~ 6个 `#` 符号来定义不同级别的标题，最多到六级标题。
注意 ：`#` 后最好是需要加一个空格。

* 书写格式

```
# 一级标题
## 二级标题
### 三级标题
###### 六级标题
```

* 解析效果

![# 标题样式](http://pcx2lec2u.bkt.clouddn.com/201808051352_845.png)

特别的，还可使用 `=` (高阶标题) 和 `-` (次阶标题) 标记 一级 和 二级 标题。
注意：`=` 和 `-` 的个数在不同 Markdown 工具中都有不同，但这倒不是多大的问题了，简单试试就知道了。 

* 书写格式

```
效果和一级标题一样
=
效果和二级标题一样
-
```

* 解析效果

![- = 标题样式](http://pcx2lec2u.bkt.clouddn.com/201808051356_386.png)

<a id="22-%E5%8A%A0%E7%B2%97%E3%80%81%E6%96%9C%E4%BD%93-%E5%92%8C-%E5%88%A0%E9%99%A4%E7%BA%BF"></a>
### 2.2 加粗、斜体 和 删除线

* markdown使用 `*` 和 `_`  强调文本，使用一个 `*` 和 `_` 包围的文本会被转化为 *斜体* ；而用两个 `*` 和 `_` 包围的文本则会被转化成 **加粗** ；使用两个`~`包围的文本会被转化为 ~~删除线~~
* 但如果你的 `*` 、` _` 和 `~` 两边都有空白的话，它们就只会被当成普通的符号，这其实也是一个需要注意的地方
* 如果要在文字前后直接插入普通的 星号 `*` 或 下划线 `_` ，你可以用 反斜杠 `\` 转义

* 书写格式
  
```
*斜体文字*
_斜体文字_
**加粗文字**
__加粗文字__
~~删除内容~~
```

* 解析效果

*斜体文字*
*斜体文字*
**加粗文字**
**加粗文字**
~~删除内容~~

<a id="23-%E5%88%97%E8%A1%A8"></a>
### 2.3 列表

Markdown支持 无序列表 和 有序列表。
无序列表可以使用 `*` ， `+` ， `-` 三者中任意符号来标记；有序列表则使用 `数字` 加 `.` 来标记。
注意：标记后面最好是需要加一个空格，有序列表的数字会被按顺序自动更正。通常情况下，无序列表的项目符号是按照实心圆、空心圆、实心方格的层级关系递进的。

* 书写格式

```
有序列表
1. 第一点
2. 第二点
5. 第三点

无序列表
* 这是无序列表项目
- 这是无序列表项目
+ 这是无序列表项目

嵌套的列表
- 呵呵
    + 嘉嘉
    * 嘻嘻
    * 吼吼
        * 嘎嘎
        - 桀桀
+ 哈哈
```

* 解析效果

有序列表
1. 第一点
2. 第二点
5. 第三点

无序列表
* 这是无序列表项目
- 这是无序列表项目
+ 这是无序列表项目

嵌套的列表
- 呵呵
    + 嘉嘉
    * 嘻嘻
    * 吼吼
        * 嘎嘎
        - 桀桀
+ 哈哈

<a id="24-%E5%BC%95%E7%94%A8"></a>
### 2.4 引用

在段落前添加一个 `>` 符号即可将该段落标记为引用
注意： `>` 后最好是需要加一个空格；`>`、`>>` 和 `>>>` 等多层嵌套的使用，有点不太好总结，不要问我为什么，实践出真知。

* 书写格式

```
一般用法
> 这是引用

迭代使用（引用中的引用）
> 这是一级引用
>> 这是二级引用
>>> 这是三级引用
>>
>> 这是二级引用
>
> 这是一级引用

引用的区块内也可使用其他 Markdown 语法
> 1.   这是第一行列表项。
> 3.   这是第二行列表项。
> 5.   这是第三行列表项。
>
> 给出一些例子代码：
>
>     return shell_exec("echo $input | $markdown_script");
```

* 解析效果 

一般用法
> 这是引用

迭代使用（引用中的引用）
> 这是一级引用
>> 这是二级引用
>>> 这是三级引用
>>
>> 这是二级引用
>
> 这是一级引用

引用的区块内也可使用其他 Markdown 语法
> 1.   这是第一行列表项。
> 3.   这是第二行列表项。
> 5.   这是第三行列表项。
>
> 给出一些例子代码：
>
>     return shell_exec("echo $input | $markdown_script");

* 补充一下
引用区块 `>` 和代码区块 ` ``` ` 的区别：
`>`引用区块中的文本保留Markdown语法，而` ``` `代码块中的文本不保留Markdown语法。

<a id="25-%E5%88%86%E5%89%B2%E7%BA%BF"></a>
### 2.5 分割线
分割线最常使用就是三个或以上 `*` ，还可以使用 `-` 和 `_` 。 
注意：使用 `---` 作为水平分割线时，要在它的前面空一行，防止 `---` 被当成标题标记的表示方式。

* 书写格式

```
---
***
___
```

* 解析效果

---
***
___

<a id="26-%E6%8F%92%E5%85%A5%E9%93%BE%E6%8E%A5"></a>
### 2.6 插入链接
markdown文本中插入链接非常方便，有 `文内链接` 和 `引用链接` 两种方式。

注意：文内链接 和 引用链接 显示效果是一样的，但是在编辑状态下的使用情况不一样。文内链接紧跟链接文字，可以在看到链接文字的同时清楚的知道链接地址，但是不便于多次重复利用。

引用链接可以重复使用，但一般都是将一些链接放在一起统一管理，如一段文字后面或文章结尾，因此在找到链接和链接文字的对应关系上有些麻烦，各有利弊，分情况使用吧。

* 书写格式

```
文内链接
这是一个文内链接的[例子](http://example.com/ "鼠标悬浮此处显示的标题")。
[这个](http://example.net/)链接在鼠标悬浮时没有标题。
[这个](/about/)链接是本地资源。

引用链接
这是一个引用链接的 [例子][id]，[例子2][]。
[id]: http://example.com/  "鼠标悬浮标题（可选）"
[例子2]: http://example.com/ 
注意，这里的 id 没有大小写区分，如果省略 id ，则前面方括号的内容会被用作 id 。

我常用的网站包括 [Google][1]， [Yahoo][2] 和 [MSN][3] 。
[1]: http://google.com/        "Google"
[2]: http://search.yahoo.com/  "Yahoo Search"
[3]: http://search.msn.com/    "MSN Search"
  
也可以写成

我常用的网站包括 [Google][]，[Yahoo][] 和 [MSN][] 。
[google]: http://google.com/        "Google"
[yahoo]:  http://search.yahoo.com/  "Yahoo Search"
[msn]:    http://search.msn.com/    "MSN Search"
```

* 解析效果

文内链接
这是一个文内链接的
这是一个链接的[例子](http://example.com/ "鼠标悬浮此处显示的标题")。
[这个](http://example.net/)链接在鼠标悬浮时没有标题。
[这个](/about/)链接是本地资源。

![引用链接的解析效果](http://pcx2lec2u.bkt.clouddn.com/201808051442_773.png)

<a id="27-%E6%8F%92%E5%85%A5%E5%9B%BE%E7%89%87"></a>
### 2.7 插入图片

插入图片和插入链接非常类似，只是在方括号前多一个 `!` 。

`![Alt text](/path/to/img.jpg "Optional title")`

* Alt text为如果图片无法显示时显示的文字。
* /path/to/img.jpg为图片所在路径。
* Optional title为显示标题。显示效果为在你将鼠标放到图片上后，会显示一个小框提示，提示的内容就是Optional title。

注意：Markdown 语法目前还没有某种合适的办法指定图片的宽高，但据我所知，很多平台以及在这个方向作出相当多的改进了，一起期待吧！

* 书写格式

```
文内链接
![idol](http://pcx2lec2u.bkt.clouddn.com/201808051449_378.jpg)

引用链接

![idol][idol]
[idol]: http://pcx2lec2u.bkt.clouddn.com/201808051449_378.jpg
```

* 解析效果

文内链接

![idol](http://pcx2lec2u.bkt.clouddn.com/201808051449_378.jpg)

![引用链接解析效果](http://pcx2lec2u.bkt.clouddn.com/201808051452_718.png)

<a id="28-%E8%A1%A8%E6%A0%BC"></a>
### 2.8 表格
表格的书写格式一目了然，还是很方便简洁的。

* 书写格式

```
| 左对齐 | 中间对齐 | 右对齐 |
| :---   |  :---:   |   ---: |
| 左1    |  中1     |  右1   |
| 左2    |  中2     |  右3   |
```

* 解析效果

| 左对齐 | 中间对齐 | 右对齐 |
| :---   |  :---:   |   ---: |
| 左1    |  中1     |  右1   |
| 左2    |  中2     |  右2   |

<a id="29-%E8%A7%92%E6%A0%87"></a>
### 2.9 角标

不同于前面说的链接，这里的角标内容会被放在文末，点击可以实现跳转，使用 `[^]` 来定义脚注。

* 书写格式

```
使用 Markdown[^1] 可以效率的书写文档，直接转换成 HTML[^2] ，你可以使用Leanote[^Le] 编辑器进行书写。
[^1]: Markdown是一种纯文本标记语言
[^2]: HyperText Markup Language 超文本标记语言
[^Le]: 开源笔记平台，支持Markdown和笔记直接发为博文
```

* 解析效果

使用 Markdown[^1] 可以效率的书写文档，直接转换成 HTML[^2] ，你可以使用Leanote[^Le] 编辑器进行书写。

[^1]: Markdown是一种纯文本标记语言。

[^2]: HyperText Markup Language 超文本标记语言。

[^Le]: 开源笔记平台，支持Markdown和笔记直接发为博文。

<a id="210-%E4%B8%8A%E4%B8%8B%E6%A0%87"></a>
### 2.10 上下标
`<sub>`、`<sup>` 用作表示上下标

* 书写格式

```
E = mc<sup>2</sup>

Water : H<sub>2</sub>O
```

* 解析效果

E = mc<sup>2</sup>

Water : H<sub>2</sub>O

<a id="211-%E7%9B%B4%E6%8E%A5%E9%93%BE%E6%8E%A5%E4%B8%8E%E9%82%AE%E7%AE%B1"></a>
### 2.11 直接链接与邮箱
在 markdown 中将 链接地址 或 邮箱地址 用 `<>` 包围，则会被自动转换成可点击的链接地址。

* 书写格式

```
<http://haoeric.com>

<haoeric0520@gmail.com>
```

* 解析效果

<http://haoeric.com>

<haoeric0520@gmail.com>

<a id="212-%E6%8D%A2%E8%A1%8C"></a>
### 2.12 换行
使用html标签 `<br/>` 、 `<br>` 换行

* 书写格式

```
第一行hahaha <br/> 第二行6666
```

* 解析效果

第一行hahaha <br/> 第二行6666

<a id="213-%E5%8F%8D%E6%96%9C%E6%9D%A0"></a>
### 2.13 反斜杠
如果需要避免文本中的符号被当做 markdown 标识符而发生不必要的格式转化，可以在符号前加 `\` 来避免。

* 书写格式

```
\*不是斜体\*
```

* 解析效果

\* 不是斜体 \*

整理一下，Markdown 支持以下这些符号前面加上 反斜杠 来帮助插入普通的符号：

| 符号 | 含义 |
| :-: | :-: |
| `\` | `反斜线` |
| ` | `反引号` |
| `*` | `星号` |
| `_ ` | `底线` |
| `{}` | `花括号` |
| `[]` | `方括号` |
| `()` | `括弧` |
| `#` | `井字号` |
| `+` | `加号` |
| `-` | `减号` |
| `.` | `英文句点` |
| `!` | `惊叹号` |

<a id="214-%E4%BB%A3%E7%A0%81%E9%AB%98%E4%BA%AE"></a>
### 2.14 代码高亮
使用栅栏标记代码块的一个好处是可以标明代码的语种，然后实现代码的高亮。

* 书写格式

````
```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```
````
* 解析效果

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

<a id="215-%E5%85%B6%E4%BB%96"></a>
### 2.15  其他
<a id="2151-%E9%94%9A%E7%82%B9"></a>
#### 2.15.1  锚点

网页中，`锚点` 其实就是页内超链接，也就是 链接本文档内部的某些元素 ，实现当前页面中的跳转，最典型的例子就是 `目录` 这种结构了。比如我这里写下一个锚点，点击 `回到目录`，就能跳转到 `目录`。 在 `目录` 中点击 这一节，就能跳过来。

在 `Github` 的 `md` 文件中，会为每个 `h1~h6` 标签(即 `# ... ######` )，自动塞入一个 `a` 标签，并渲染好 `id` 。 

比如 `# h1`，被渲染成html如下：

``` html
<h1>
  <a id="user-content-h1" class="anchor" href="#h1" aria-hidden="true">
      <svg aria-hidden="true" class="octicon octicon-link" height="16" role="img" version="1.1" viewBox="0 0 16 16" width="16">
        <path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z">
        </path>
      </svg>
    </a>
    h1
</h1>
```

不去管 `svg` 部分，可以看到 `h1` 标签内嵌入了一个 `id` 为  `"user-content-h1"` 的 `a` 标签，如果标题为 `# h5` ，那么 `id` 就会是 `user-content-h5 ` 。

<a id="2152-%E7%A9%BA%E6%A0%BC"></a>
#### 2.15.2 空格
在段首加入 `&emsp;`、`&ensp;`、`&nbsp;` 来输入空格，其中，`&emsp;` 是一个中文字符，`&ensp;` 是半个中文字符 ，`&nbsp;` 是1/4中文字符。

<a id="2153-%E5%9B%BE%E7%89%87%E5%9B%BE%E5%BA%8A"></a>
#### 2.15.3 图片图床
插入图片的地址需要图床，那么，究竟什么是图床呢？

**图床**，顾名思义，图片床，即大量图片汇聚地，每一张图片都有一个`url`,供所需站点使用。

详情可以参考我之前写的博文 [图床工具分享](https://zhouie.cn/posts/201804241/) 。

另外，越来越多的 Markdown 工具现在开始支持 **一键上传图片至云端并生成 Markdown 引用链接至剪切板**，可以看看最近的我最近在这方面的 收获总结 —— [Md2All Markdown排版利器](https://zhouie.cn/posts/201808032/) 以及 [qiniu_upload windows工具](https://zhouie.cn/posts/201808033/)。

ps：七牛云邀请注册链接：[https://portal.qiniu.com/signup?code=3lowm9s25ur82](https://portal.qiniu.com/signup?code=3lowm9s25ur82)

<a id="2154-latex%E5%85%AC%E5%BC%8F"></a>
#### 2.15.4 LaTeX公式
* [LaTeX公式参考语法](https://math.meta.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference)

<a id="%E8%A1%8C%E5%86%85%E5%85%AC%E5%BC%8F%EF%BC%88%24%E8%A1%A8%E7%A4%BA%EF%BC%89"></a>
##### 行内公式（`$`表示）
* 书写格式

```
爱因斯坦发明的质能方程是：$E=mc^2$
```

* 显示效果

爱因斯坦发明的质能方程是：![](http://pcx2lec2u.bkt.clouddn.com/201808052329_486.png)

<a id="%E6%95%B4%E8%A1%8C%E5%85%AC%E5%BC%8F%EF%BC%88%24%24%E8%A1%A8%E7%A4%BA%EF%BC%89"></a>
##### 整行公式（`$$`表示）
* 书写格式

```
$$\sum_{i=1}^n a_i=0$$
$$f(x_1,x_x,\ldots,x_n) = x_1^2 + x_2^2 + \cdots + x_n^2 $$
$$\sum^{j-1}_{k=0}{\widehat{\gamma}_{kj} z_k}$$
```

* 显示效果

![](http://pcx2lec2u.bkt.clouddn.com/201808052327_103.png)

<a id="2155-%E6%B5%81%E7%A8%8B%E5%9B%BE%E3%80%81%E6%B8%B2%E6%9F%93%E5%BA%8F%E5%88%97%E5%9B%BE"></a>
#### 2.15.5 流程图、渲染序列图
* [流程图参考语法](http://adrai.github.io/flowchart.js/)
* [渲染序列图参考语法](https://bramp.github.io/js-sequence-diagrams/)

<a id="%E6%B5%81%E7%A8%8B%E5%9B%BE"></a>
##### 流程图
````
  ```flow
  st=>start: Start:>https://www.zybuluo.com
  io=>inputoutput: verification
  op=>operation: Your Operation
  cond=>condition: Yes or No?
  sub=>subroutine: Your Subroutine
  e=>end

  st->io->op->cond
  cond(yes)->e
  cond(no)->sub->io
  ```
````
![流程图 显示效果图](http://pcx2lec2u.bkt.clouddn.com/201808051300_914.png)

<a id="%E6%B8%B2%E6%9F%93%E5%BA%8F%E5%88%97%E5%9B%BE"></a>
##### 渲染序列图
````
  ```sequence
  Alice->Bob: Hello Bob, how are you?
  Note right of Bob: Bob thinks
  Bob-->Alice: I am good thanks!
  ```
````
![渲染序列图 显示效果图](http://pcx2lec2u.bkt.clouddn.com/201808051309_694.png)

<a id="2156-github-emoji"></a>
#### 2.15.6 GitHub Emoji
Github 的 Markdown 语法支持添加 emoji 表情，输入不同的符号码（两个冒号包围的字符）可以显示出不同的表情。
我在 github 上分享了 [markdown-emoji 列表](https://github.com/zhouie/markdown-emoji)，可以去看看。
![markdown-emoji 列表](http://pcx2lec2u.bkt.clouddn.com/201808051255_854.png)

> 可是奇怪的是，我的GitHub Pages 采用 Hexo框架，渲染不出 emoji 表情(不支持)，这是为什么呢？

这是因为 Hexo 默认的 markdown 渲染引擎不会渲染 emoji 表情，详情可参阅 [搭建Hexo博客进阶篇](https://www.jianshu.com/p/732240700424)

<a id="216-markdown%E7%9A%84%E5%B1%80%E9%99%90%E6%80%A7"></a>
### 2.16 Markdown的局限性
* 不同的 Markdown 工具功能细节上可能会不一样
* 写技术类文章条理很重要，因此在开篇有个目录，也显得非常有必要，因此越来越多工具支持 `[TOC]` 一键生成目录列表，具体可参看我的 [github-md-toc](https://github.com/zhouie/github-md-toc)
* 另外还有，`流程图`，`渲染序列图`，`LaTex数学公式`，`代码语法高亮`，`显示代码行号`，`图片/文字 居中/左右对齐`，`[TOC]目录生成`，等等这些，其实都是非常必要的功能，值得去做一些扩展。

---
<a id="3-markdown-%E5%B7%A5%E5%85%B7%E7%9A%84%E9%80%89%E6%8B%A9"></a>
## 3. Markdown 工具的选择
> 还是那句话，编辑器的兴盛固然是好事，但工具的过度丰富也是一种麻烦，如何选出适合自己的 Markdown 编辑器让很多人大伤脑筋，甚至在很多时候，一个设计不佳的 Markdown 编辑器会让初次尝试 Markdown 的写作者放弃使用 Markdown 来写作。

<a id="31-windows-%E5%B9%B3%E5%8F%B0"></a>
### 3.1 Windows 平台

<a id="311-sublime"></a>
#### 3.1.1 [Sublime](http://www.sublimetext.com/)
* **支持 OS X、Windows、Ubuntu 等 UNIX 及 Linux 平台**
* 关联阅读：[强大的Sublime编辑器](https://blog.csdn.net/jave_f/article/details/79894028)
* Sublime Text 是程序员圈子里口口相传的「神器」级代码编辑器，它基于 Vim 开发，各种功能性组件层出不穷，功能极度强大，是代码编辑器中的标杆作品。
* 同时，它也支持 Markdown 语法高亮，于是很多人都习惯于用它来进行 Markdown 文档书写。由于有着诸如 Markdown Preview、Sublime-Evernote 等扩展性插件，在 Sublime Text 里完全可以完成 Makrdown 书写预览与导出的过程。
* 如果你是一名开发者，Sublime Text 基本可以满足你对 Markdown 编辑的全部需求，如果你是一名普通用户，我则更推荐你使用专业的 Markdown 编辑器。
![](http://pcx2lec2u.bkt.clouddn.com/201808052055_396.png)

<a id="312-%E7%AE%80%E4%B9%A6"></a>
#### 3.1.2 [简书](https://www.jianshu.com/) 
* 简书的Web 端使用 Markdown 很舒服，它同样支持左右两栏的实时预览，字体优雅、简洁。
![简书](http://pcx2lec2u.bkt.clouddn.com/201808052035_825.png)

<a id="313-cmd-markdown"></a>
#### 3.1.3 [Cmd Markdown](https://www.zybuluo.com/cmd/) 
* 除了编辑，管理您的私有文档，Cmd Markdown 还支持发布文稿，您可以在这里将文稿共享给朋友、亲友、同事。
* **支持 Linux、Mac、Windows 三大平台**，轻松选择适合你的客户端
![Cmd Markdown](http://pcx2lec2u.bkt.clouddn.com/201808051220_899.png)
![Cmd Markdown 全平台端 优势](http://pcx2lec2u.bkt.clouddn.com/201808051621_986.png)

<a id="314-%E9%A9%AC%E5%85%8B%E9%A3%9E%E8%B1%A1"></a>
#### 3.1.4 [马克飞象](https://maxiang.io)
* **支持 Windows 平台**
* 专为 [印象笔记](https://app.yinxiang.com/referral/Registration.action?sig=1b8f0696566f3d6d59044226739bab4069e3723d147381eb8ebe9c849f6711ff&uid=18502813) 打造的 Markdown 编辑器
![马克飞象](http://pcx2lec2u.bkt.clouddn.com/201808051219_34.png)

<a id="315-%E4%B8%BA%E7%9F%A5%E7%AC%94%E8%AE%B0"></a>
#### 3.1.5 [为知笔记](http://www.wiz.cn/)
* **支持 Windows 平台**
* 作为一个支持全平台的云笔记应用，为知笔记完全可以当作 Markdown 编辑器来使用，当我们需要跨大平台进行 Markdown 协作写作的时候，会是一个不错的选择。
![为知笔记](http://pcx2lec2u.bkt.clouddn.com/201808052121_82.png)

<a id="316-simple-markpad"></a>
#### 3.1.6 [Simple MarkPad](http://simple-markpad.qiniudn.com/)
* Simple Markpad 最吸引人的一点就是，在诸多看起来就让人觉复杂的 Windows 平台的 Markdown 编辑器中，它始终保持着简约的风格。
* 它支持自动列表、图片拖入、Markdown 语法高亮、全屏写作模式、字数统计，还有丰富的快捷键，同时具有着素雅而克制的界面风格。
![](http://pcx2lec2u.bkt.clouddn.com/201808052128_580.png)

<a id="317-markpad"></a>
#### 3.1.7 [MarkPad](http://code52.org/DownmarkerWPF/)
* **支持 Windows 平台**
![MarkPad](http://pcx2lec2u.bkt.clouddn.com/201808051211_257.png)

<a id="318-miu"></a>
#### 3.1.8 [Miu](https://github.com/egoist/Miu)
* **支持 Windows 平台**
* 一个很优秀的工具，但是由于和 [Mou](http://25.io/mou/) 重复性比较高，同时与其有些争议问题，故并未介绍，有兴趣的话可以自行查看。
![Miu](http://pcx2lec2u.bkt.clouddn.com/201808051636_421.png)


<a id="32-mac-%E5%B9%B3%E5%8F%B0"></a>
### 3.2 Mac 平台
<a id="321-mou"></a>
#### 3.2.1 [Mou](http://25.io/mou/)
* Mou 是一款由国人开发的 Mac 平台上的 Markdown 编辑器，支持自定义界面主题，导入输出CSS格式文件，最重要的是 Mou 支持 Markdown 实时预览，这让不少初学者能快速上手 Markdown 写作。
* Mou 除了直观的实时预览功能之外，还是目前对中文支持最好的 Markdown 编辑器，无论是多种的编辑主题，还是各式的输出样式，在支持自定义的同时，对中文的优化也是目前的最好的，Mou 甚至支持竖排编写。同时，Mou 还具有发布功能，支持发布到 Tumblr。
![](http://pcx2lec2u.bkt.clouddn.com/201808052107_285.png)

<a id="322-ulysses"></a>
#### 3.2.2 [Ulysses](http://www.ulyssesapp.com/)
* 作为 Markdown 编辑器领域的老牌王者，这款应用入围了苹果2013年 Mac App Store 的 The Best of 2013。Ulysses 有着经典的文档库架构，多样化的可供自定义的编辑主题，大量的输出格式选择，功能丰富，最适合长文写作与颜控用户。
* 无论是 PDF 还是 ePub 格式你都可以在官网下载到大量的现成格式模版，省去大量的用在排版上的时间，你需要做的只是按照自己的想法写完文章，之后就可以通过 Ulysses 导出成任意自己想要的格式了。
![](http://pcx2lec2u.bkt.clouddn.com/201808052100_74.png)

<a id="323-byword"></a>
#### 3.2.3 [Byword](https://bywordapp.com/)
* 如果说 Ulysses 是功能最丰富的 Markdown 编辑器，Byword 就是最简约的 Markdown 编辑器。同样作为 Apple 平台上的老牌编辑器，Byword 有着一种简约克制的气质，仅有 **6.4 MB** 的体量，却创造出了一个完美而纯粹的写作环境。
* 在我看来 Byword 应该是目前编辑器中最忠于 Markdown 语言发明初衷的的编辑器 —— 简单、干净、利落，**All for writing feelings**。
![](http://pcx2lec2u.bkt.clouddn.com/201808052102_20.png)

<a id="324-typora"></a>
#### 3.2.4 [typora](https://www.typora.io/)
* **支持 Mac 与 Windows 平台**
* 关联阅读： [《让 Markdown 写作更简单，免费极简编辑器：Typora》](https://sspai.com/30292)
这款编辑器在大家都还在苦恼如何处理预览和写作界面之间的关系时候，机智的将「写作」和「预览」合二为一了，你输入的地方，即是你输出的地方。
* Markdown 标记成为了类似快捷键一样的存在，你就像在使用一个所见即所编辑器一样，自然而快速的进行写作。可以说，Typora 完全颠覆了目前的 Markdown 编辑器的交互模式，将 Markdown 写作向普通用户推进了一大步。
![](http://pcx2lec2u.bkt.clouddn.com/201808051641_372.gif)
* Typora 的革新不止于此，它还提供了了类似 Office 的图像式表格建立方式，支持目录大纲生成，支持拖拽插入图片，并且支持所有主流代码的高亮与 LaTeX 公式编写。
* 可以说 Typora 是目前 Markdown 编辑器中功能最与众不同的一个，诸多新鲜而强大的功能让它卓尔不群，绝对值得尝试。
![](http://pcx2lec2u.bkt.clouddn.com/201808051644_157.gif)

<a id="325-quiver"></a>
#### 3.2.5 [Quiver](http://happenapps.com/)
* 关联阅读：[《技术写作者的专属笔记本：Quiver》](https://sspai.com/32193)
* Quiver 同样是一款国人开发的软件。它具有着强大的 Markdown 编辑能力，但同时又不仅限于此。
* 它集合了写作软件与笔记软件的特点，它既有着传统 Markdown 写作软件的实时编辑预览，又有着笔记软件的文件逻辑结构，同时它还内置了 Ace 代码编辑器，通过 Cell 的概念，将各种不同的格式组合在一起，最后形成一个个文件。
* Quiver 可以说是一款为技术写作设计的，专注于笔记方向的 Markdown 编辑器，它能够在为你提供流畅的 Markdown 写作体验的同时，为你构建起一个良好的知识管理结构。
![](http://pcx2lec2u.bkt.clouddn.com/201808052113_322.png)

<a id="326-alternote"></a>
#### 3.2.6 [Alternote](http://alternoteapp.com/)
* 同为 Mac 平台上的笔记式 Markdown 编辑软件，Alternote 则是为印象笔记进行了深度定制，成为了一款简约轻量的第三方印象笔记客户端。它抛弃了印象笔记臃肿的架构，专注于对写作体验的优化，深度重构了印象笔记对对于 Markdown 写作者的意义。
* 在 Alternote 里，Markdown 标记在输入完成后会自动转换成对应的富文本格式，并不需要额外的预览，不过美中不足的是，这样也造成了一旦转换为富文本就无法再转换回来的问题。
![](http://pcx2lec2u.bkt.clouddn.com/201808052119_566.gif)

<a id="327-snippetslab"></a>
#### 3.2.7 [SnippetsLab](http://www.renfei.org/snippets-lab/)
* Snippetslab9 是一款 Mac 平台的面向开发者的代码管理与编写工具，专注于帮助使用者收集整理代码片段，快速调用有价值的代码片段，打造属于个人的代码仓库。
* 那么它和 Markdown 的关系在哪里呢？奥秘就在它的菜单栏助手上。Snippetslab 的菜单栏助手有着类似印象笔记菜单栏助手的特性，支持在菜单栏打开小窗口进行程序编写，同时可以对代码进行语法高亮，而它正好也支持 Markdown。
* 目前所有平台中，Snippetslab 是唯一一款提供了菜单栏 Markdown 文字输入的应用，你可以在不用打开主题程序的情况下，以小视窗形式快速的进行 Markdown 编写。
![](http://pcx2lec2u.bkt.clouddn.com/201808052130_568.png)

<a id="328-markdownpad"></a>
#### 3.2.8 [MarkdownPad](http://markdownpad.com/) 
* **支持 Mac 平台**
![](http://pcx2lec2u.bkt.clouddn.com/201808051212_371.png)


<a id="33-%E7%BD%91%E9%A1%B5%E7%89%88%E7%BA%BF%E4%B8%8A"></a>
### 3.3 网页版(线上)
* [程序猿DD - 常用工具：Markdown转换工具](http://blog.didispace.com/tools/online-markdown/)
* [马克飞象 - 专为印象笔记打造的Markdown编辑器](https://maxiang.io/)
* [Cmd Markdown编辑阅读器 - 作业部落出品](https://www.zybuluo.com/mdeditor)
* [Dillinger, the Last Markdown Editor ever.](http://dillinger.io/)
* [StackEdit – In-browser Markdown editor](https://stackedit.io/)
* [Scribble - Simple Markdown Wiki](http://www.tryscribble.com/)
* [Free Markdown to HTML Converter](https://markdowntohtml.com/)
* [Draft. Write Better.](https://draftin.com/)
* [Markable.in](https://markable.in/)
* [Markdown.css](https://mrcoles.com/demo/markdown-css/)

同时，也有一些 Markdown 相关浏览器插件也是很棒的，最典型的便是：[Markdown-Here](https://markdown-here.com/)，我也有写一篇博文专门介绍分享了它 —— [Markdown-Here md-2-html渲染](https://zhouie.cn/posts/201808031/)

<a id="34-others"></a>
### 3.4 Others
* [Editor.md - 开源在线 Markdown 编辑器](http://pandao.github.io/editor.md/index.html)
* [WriteMonkey](http://writemonkey.com/index.php)
* [DAUX.IO](http://daux.io/index)
* [ReText](https://github.com/retext-project/retext)
* [Cmd Markdown](https://www.zybuluo.com/cmd/)
* [vim](https://www.vim.org/)
* [Mango](https://github.com/egrcc/Mango)
* [Haroopad](http://pad.haroopress.com/user.html)
* [iA Writer](https://ia.net/writer)
* [MarkdownX](http://www.wandoujia.com/apps-com.ryeeeeee.markdownx?mt=8&uo=4&ct=appcards)
* [markItUp! Universal Markup jQuery Editor](http://markitup.jaysalvat.com/home/)

<a id="35-more"></a>
### 3.5 More
如有更好的 Markdown 免费编辑器推荐，请到[这里留言反馈](https://github.com/Javef/Markdown/issues)，谢谢~

---

<a id="4-%E6%8E%A8%E8%8D%90%E9%98%85%E8%AF%BB"></a>
## 4. 推荐阅读
* [MarkDown学习笔记](https://www.jianshu.com/p/564bdf3a9462?utm_campaign=maleskine&utm_content=note&utm_medium=seo_notes&utm_source=recommendation)
* [首次使用MarkDown好激动](https://www.zybuluo.com/liayun/note/371635)
* [让你的Markdown用起来得心应手](https://www.jianshu.com/p/d7d6da4b7c60?utm_campaign=maleskine&utm_content=note&utm_medium=seo_notes&utm_source=recommendation)
* [一段JS代码让Markdown自动生成侧边栏目录](https://www.jianshu.com/p/34c92cbd0aaf/)
* [Markdown 语法说明 (简体中文版)](https://zhouie.cn/markdown-doc/markdown-doc-syntax-zh)
* [码字必备：18 款优秀的 Markdown 写作工具 - 2015 年度盘点 - 少数派](https://sspai.com/post/32483#fn5)

---

<a id="5-%E8%A1%A5%E5%85%85"></a>
## 5. 补充

2018/04/20 07:12
![Markdown_desktop_tool_rank.png](https://upload-images.jianshu.io/upload_images/9934558-a23a100ba5d35018.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

2018/08/05 20:36
![整理于2015年](http://pcx2lec2u.bkt.clouddn.com/201808052037_635.png)
