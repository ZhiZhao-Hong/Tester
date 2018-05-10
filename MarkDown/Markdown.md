#Markdown:Basics(快速入门)#
本文所有的内容都源自于：<a>http://wowubuntu.com/markdown/basic</a>
## 段落、标题、区块代码 ##
>一个段落是由一个以上的连接的行句组成，而一个以上的空行则会划分出不同的段落（空行的定义是显示上看起来像是空行，就被视为空行，例如有一行只有空白和 tab，那该行也会被视为空行），一般的段落不需要用空白或换行缩进。
>
>Markdown 支持两种标题的语法，Setext 和 atx 形式。Setext 形式是用底线的形式，利用 = （最高阶标题）和 - （第二阶标题），Atx 形式在行首插入 1 到 6 个 # ，对应到标题 1 到 6 阶。
>
>区块引用则使用形式 `'>'` 来表示，所体现的效果就如这三段所示

## 修辞和强调 ##
Markdown 使用星号和底线来标记需要强调的区段<br>
>1. __单个下划线(*)__ ，表示斜体。如：\_我是斜体\_ == _我是斜体_
>2. __双下划线(*)__ ，表示加粗。如：\_\_我是加粗\_\_ == __我是加粗__
>3. __三下划线(*)__ ，表示斜体加粗。如：\_\_\_我是斜体加粗\_\_\_ == ***我是斜体加粗***

## 列表 ##
+ 无序列表使用**星号**、**加号**和**减号**来做为列表的项目标记，这些符号是都可以使用的，使用星号
+ 有序的列表则是使用一般的**数字**接着一个英文句点作为项目标记：

## 链接 ##
Markdown 支持两种形式的链接语法： **行内** 和 **参考** 两种形式，两种都是使用角括号来把文字转成链接。<br>
### 行内 ###
+ 行内形式是直接在后面用括号直接接上链接：<br>
`This is an [example link](http://example.com/).`
+ 你也可以选择性的加上 title 属性<br>
`This is an [example link](http://example.com/ "With a Title").`
### 参考 ###
	I get 10 times more traffic from [Google][1] than from
	[Yahoo][2] or [MSN][3].

	[1]: http://google.com/ "Google"
	[2]: http://search.yahoo.com/ "Yahoo Search"
	[3]: http://search.msn.com/ "MSN Search"
## 图片 ##
图片语法和链接很像
### 行内 ###
	![alt text](/path/to/img.jpg "Title")
#### 参考 ####
	![alt text][id]
	[id]: /path/to/img.jpg "Title"