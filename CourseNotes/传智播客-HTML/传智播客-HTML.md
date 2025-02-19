---
 学习目标:

  - 了解常用浏览器
  - 掌握WEB标准
  - 理解标签语义化
  - 掌握常用的排版标签
  - 掌握常用的文本格式化图像链接等标签
  - 掌握三种列表标签
  - 掌握表格标签
  - 掌握表格标签
  - 掌握表单标签
typora-copy-images-to: media
---

自我介绍

传智讲师   刘晓强     江湖人称  强哥  

但是不是

<img src="media/qq.jpg" />



也不是：

<img src="media/lk.jpg" />

其实这是我：



<img src="media/gt.jpg" />





前端基础  html +css    基础班        html 2 +css  7天    9 天 传统布局    +  3天 html 5 +css3 基础

就业班   js     移动web       php + 项目  15      node      vue     框架  微信 ...  大前端    

HTML 第一天目标

能够写出基本的页面（里面包含图片、各种标签和链接）

# 开发工具

我们主要用的 开发工具有   chrome  、  sublime 、  photoshop

浏览器（显示） 

```
浏览器是网页显示、运行的平台，常用的浏览器有IE、火狐（Firefox）、谷歌（Chrome）、Safari和Opera等。我们平时称为五大浏览器。
```

<img src="media/b.png" />

查看浏览器占有的市场份额（知晓）

查看网站： <a href="http://tongji.baidu.com/data/browser" target="_blank">http://tongji.baidu.com/data/browser</a>

<img src="media/count.png" />





 这些工具你认识几个？

sublime（书写）

 <img src="media/s.png" />

  普通青年    Dreamweaver

  文艺青年    sublime

  高手和傻子  用记事本

  其实。。。。











  <img src="media/node.png" />



Photoshop(协助)

![1498465020015](media/1498465020015.png)

PS 工具是我们使用频率比较高的软件之一， 我们学习PS目的不是为了设计海报做电商和UI的，而是要求：

1. **熟练的切图**
2. 能和网站美工美眉有共同话题。。。。。

# 认识网页

```
网页主要由文字、图像和超链接等元素构成。当然，除了这些元素，网页中还可以包含音频、视频以及Flash等。
```

<img src="media/mi.png"alt="">

```
思考：  网页是如何形成的呢?
```

<img src="media/web.png" />

## 常见浏览器内核介绍

```
浏览器是网页运行的平台，常用的浏览器有IE、火狐（Firefox）、谷歌（Chrome）、Safari和Opera等。我们平时称为五大浏览器。
```

<img src="media/b.png" />



### 浏览器内核（理解）             

```
浏览器内核又可以分成两部分：渲染引擎(layout engineer 或者 Rendering Engine)和 JS 引擎。
渲染引擎 它负责取得网页的内容（HTML、XML、图像等等）、整理讯息（例如加入 CSS 等），以及计算网页的显示方式，然后会输出至显示器或打印机。浏览器的内核的不同对于网页的语法解释会有不同，所以渲染的效果也不相同。
JS 引擎 则是解析 Javascript 语言，执行 javascript语言来实现网页的动态效果。

最开始渲染引擎和 JS 引擎并没有区分的很明确，后来 JS 引擎越来越独立，内核就倾向于只指渲染引擎。有一个网页标准计划小组制作了一个 ACID 来测试引擎的兼容性和性能。内核的种类很多，如加上没什么人使用的非商业的免费内核，可能会有10多种，但是常见的浏览器内核可以分这四种：Trident、Gecko、Blink、Webkit。
```

（1）Trident(IE内核) 

国内很多的双核浏览器的其中一核便是 Trident，美其名曰 "兼容模式"。

代表： IE、傲游、世界之窗浏览器、Avant、腾讯TT、猎豹安全浏览器、360极速浏览器、百度浏览器等。

Window10 发布后，IE 将其内置浏览器命名为 Edge，Edge 最显著的特点就是新内核 EdgeHTML。

（2）Gecko(firefox) 

Gecko(Firefox 内核)： Mozilla FireFox(火狐浏览器) 采用该内核，Gecko 的特点是代码完全公开，因此，其可开发程度很高，全世界的程序员都可以为其编写代码，增加功能。 可惜这几年已经没落了， 比如 打开速度慢、升级频繁、猪一样的队友flash、神一样的对手chrome。

（3） webkit(Safari)  

 Safari 是苹果公司开发的浏览器，所用浏览器内核的名称是大名鼎鼎的 WebKit。

 现在很多人错误地把 webkit 叫做 chrome内核（即使 chrome内核已经是 blink 了），苹果感觉像被别人抢了媳妇，都哭晕再厕所里面了。

 代表浏览器：傲游浏览器3、 Apple Safari (Win/Mac/iPhone/iPad)、Symbian手机浏览器、Android 默认浏览器，

（4） Chromium/Blink(chrome) 

   在 Chromium 项目中研发 Blink 渲染引擎（即浏览器核心），内置于 Chrome 浏览器之中。Blink 其实是 WebKit 的分支。 

​     大部分国产浏览器最新版都采用Blink内核。二次开发

（5） Presto(Opera) 

  Presto（已经废弃） 是挪威产浏览器 opera 的 "前任" 内核，为何说是 "前任"，因为最新的 opera 浏览器早已将之抛弃从而投入到了谷歌怀抱了。  

```
了解一点：
```

移动端的浏览器内核主要说的是系统内置浏览器的内核。

Android手机而言，使用率最高的就是Webkit内核，大部分国产浏览器宣称的自己的内核，基本上也是属于webkit二次开发。

iOS以及WP7平台上，由于系统原因，系统大部分自带浏览器内核，一般是Safari或者IE内核Trident的

## Web标准（重点）

通过以上浏览器的内核不同，我们知道他们工作原理、解析肯定不同，显示就会有差别。

```
问：  哪个语言再全国基本都可以听得懂？ 
```

<img src="media/bz.png" />

### Web 标准的好处

*1*、让Web的发展前景更广阔 
*2*、内容能被更广泛的设备访问
*3*、更容易被搜寻引擎搜索
*4*、降低网站流量费用
*5*、使网站更易于维护
*6*、提高页面浏览速度

###  Web 标准构成

 Web标准不是某一个标准，而是由W3C和其他标准化组织制定的一系列标准的集合。

主要包括结构（Structure）、表现（Presentation）和行为（Behavior）三个方面。

~~~
结构标准：结构用于对网页元素进行整理和分类，咱们主要学的是HTML。 最重要
表现标准：表现用于设置网页元素的版式、颜色、大小等外观样式，主要指的是CSS。
行为标准：行为是指网页模型的定义及交互的编写，咱们主要学的是 Javascript
~~~

理想状态我们的源码： .HTML    .css   .js 

直观感受：

<img src="media/gx.png" />

总结WEB标准：

结构标准：   <img src="media/hb1.png" />  决定你是否有个好天然身体 



表现标准：   <img src="media/hb2.png" />  决定你是否打扮的美丽外观



行为标准：   <img src="media/hb3.jpg"  width="420"   />  决定你是否有吸引人的行为



课堂一练：

**1.关于WEB标准下列说法正确的是: **

A html决定页面的行为，css决定页面的样式，js决定页面的结构

B html决定页面的样式，css决定页面的结构，js决定页面的行为

C html决定页面的结构，css决定页面的样式，js决定页面的行为

D 以上都不正确

2 **web 标准里边规定三层分离不包括哪部分**

A．HTML

B．CSS

C．JavaScript

D．PHP

3.**关于WEB标准下列说法正确的是**

A．html相当于人的动作行为，CSS相当于人的穿着打扮，javascript相当于人的骨架结构；

B．html相当于人的骨架结构，CSS相当于人的穿着打扮，javascript相当于人的动作行为；

C．html相当于人的穿着打扮，CSS相当于人的骨架结构，javascript相当于人的动作行为；

D．html相当于人的骨架结构，CSS相当于人的动作行为，javascript相当于人的穿着打扮；

## HTML 初识

一般先学习HTML+CSS， 这里我们先定一个小目标，先学HTML,后学习CSS。

HTML（英文Hyper Text Markup Language的缩写）中文译为“超文本标签语言”。是用来描述网页的一种语言。

所谓超文本，因为它可以加入图片、声音、动画、多媒体等内容，不仅如此，它还可以从一个文件跳转到另一个文件，与世界各地主机的文件连接。

```html
<h1> 我是一个大标题 </h1>
```

   注意：   体会 文本    标签    语言   几个词语

- HTML 指的是超文本标记语言 (**H**yper **T**ext **M**arkup **L**anguage)
- HTML 不是一种编程语言，而是一种标记语言 (markup language)
- 标记语言是一套标记标签 (markup tag)

总结： HTML 作用就是用标记标签来描述网页，把网页内容在浏览器中展示出来。 

用文字来描述网页标签

### HTML骨架格式

日常生活的书信，我们要遵循共同的约定。 

<img src="media/mess.png" alt="">

同理：HTML 有自己的语言语法骨架格式：

```html
<HTML>   
    <head>     
        <title></title>
    </head>
    <body>
    </body>
</HTML>
```

课堂练习1：    书写我们的第一个HTML 页面！

1. 新建一个demo 的 TXT 文件。
2. 里面写入刚才的HTML 骨架。月薪过万 你我之间  黑马洗练  一飞冲天
3. 把后缀名改为 .HTML。
4. 右击--谷歌浏览器打开。

~~~
1 HTML标签：

作用所有HTML中标签的一个根节点。 最大的标签   根标签

2 head标签： 文档的头部

文档的头部描述了文档的各种属性和信息，包括文档的标题、在 Web 中的位置以及和其他文档的关系等。绝大多数文档头部包含的数据都不会真正作为内容显示给读者。

注意在head标签中我们必须要设置的标签是title

3.title标签： 文档的标题

作用：让页面拥有一个属于自己的标题。

4.body标签：文档的主体  以后我们的页面内容 基本都是放到body里面的

body 元素包含文档的所有内容（比如文本、超链接、图像、表格和列表等等。）
~~~



为了便于记忆，我们请出刚才要辞职回家养猪的二师兄来帮忙， 我称之为  猪八戒记忆法

<img src="media/pig.png" />





### HTML标签分类

  在HTML页面中，带有“< >”符号的元素被称为HTML标签，如上面提到的 &lt;HTML&gt;、&lt;head&gt;、&lt;body&gt;都是HTML骨架结构标签。所谓标签就是放在“< >” 标签符中表示某个功能的编码命令，也称为HTML标签或 HTML元素

1.双标签

~~~html
<标签名> 内容 </标签名>
~~~

该语法中“<标签名>”表示该标签的作用开始，一般称为“开始标签（start tag）”，“</标签名>” 表示该标签的作用结束，一般称为“结束标签（end tag）”。和开始标签相比，结束标签只是在前面加了一个关闭符“/”。

> ~~~html
> 比如 <body>我是文字  </body>
> ~~~

2.单标签

~~~html
<标签名 />
~~~

  单标签也称空标签，是指用一个标签符号即可完整地描述某个功能的标签。

> ~~~html
> 比如  <br />
> ~~~

### HTML标签关系

标签的相互关系就分为两种：

1.嵌套关系

```html
<head>  <title> </title>  </head>
```

<img src="media/father.jpg">

2.并列关系

```html
<head></head>
<body></body>
```

<img src="media/xiong.jpg">

倡议： 如果两个标签之间的关系是嵌套关系，子元素最好缩进一个tab键的身位。如果是并列关系，最好上下对齐。

课堂一练



```
请问下列哪个标签是错误的？
```

```
A  <head></head><body></body>
```

```
B  <strong><div></div></strong>
```

```
C  <head><title></head></title>
```

```
D  <body><div></div></body>
```



 



  <a href="key.HTML" target="_blank">sublime 一些常用快捷键  点我查看 </a>



~~~
再页面中输入 以下2个单词
1.  html: 5   
2.  !
   在sublime里面然后按下tab键盘即可生成HTML骨架
~~~



## 文档类型<!DOCTYPE>

~~~html
<!DOCTYPE html> 
~~~

同学你用啥手机？你咋回答？  

这句话就是告诉我们使用哪个html版本？  我们使用的是 html 5 的版本。  html有很多版本，那我们应该告诉用户和浏览器我们使用的版本号。

<!DOCTYPE> 标签位于文档的最前面，用于向浏览器说明当前文档使用哪种 HTML 或 XHTML 标准规范，必需在开头处使用<!DOCTYPE>标签为所有的XHTML文档指定XHTML版本和类型，只有这样浏览器才能按指定的文档类型进行解析。

注意：  一些老网站可能用的还是老版本的文档类型比如 XHTML之类的，但是我们学的是HTML5,而且HTML5的文档类型兼容很好(向下兼容的原则)，所以大家放心的使用HTML5的文档类型就好了。

## 字符集charset

<meta charset="UTF-8" />

utf-8是目前最常用的字符集编码方式，常用的字符集编码方式还有gbk和gb2312。

gb2312 简单中文  包括6763个汉字

BIG5   繁体中文 港澳台等用

GBK包含全部中文字符    是GB2312的扩展，加入对繁体字的支持，兼容GB2312

UTF-8则包含全世界所有国家需要用到的字符

```
记住一点，以后我们统统使用UTF-8 字符集, 这样就避免出现字符集不统一而引起乱码的情况了。
```

## HTML标签的语义化

白话： 所谓标签语义化，就是指标签的含义。

### 为什么要有语义化标签

1. 方便代码的阅读和维护

2. 同时让浏览器或是网络爬虫可以很好地解析，从而更好分析其中的内容 

3. 使用语义化标签会具有更好地搜索引擎优化 


核心：合适的地方给一个最为合理的标签。

语义是否良好： 当我们去掉CSS之后，网页结构依然组织有序，并且有良好的可读性。

白话，一眼看去，就知道那个是重点，结构是什么，知道每块的内容是干啥的。

遵循的原则：先确定语义的HTML ，再选合适的CSS。



## 标签相关

### 标签属性

<img src="D:/BDND/StepFullStack/AANotes/%E5%89%8D%E7%AB%AF%E5%9F%BA%E7%A1%80/%E4%BC%A0%E6%99%BA%E6%92%AD%E5%AE%A2-HTML/media/ttt.jpg" width="300"  />

属性就是特性 比如 手机的颜色 手机的尺寸 ，总结就是手机的。。

手机的颜色是黑色   手机的尺寸是 8寸

水平线的长度是 200  

图片的宽度 是  300    键  值对

使用HTML制作网页时，如果想让HTML标签提供更多的信息，可以使用HTML标签的属性加以设置。其基本语法格式如下：

```html
<标签名 属性1="属性值1" 属性2="属性值2" …> 内容 </标签名>
```



在上面的语法中，

1.标签可以拥有多个属性，必须写在开始标签中，位于标签名后面。

2.属性之间不分先后顺序，标签名与属性、属性与属性之间均以空格分开。

3.任何标签的属性都有默认值，省略该属性则取默认值。

采取  键值对 的格式   key="value"  的格式  

比如:  

```html
<hr width="400" />
```

属性  是 宽度  

值    是 400 

提倡：   尽量不使用 样式属性。   <img src="D:/BDND/StepFullStack/AANotes/%E5%89%8D%E7%AB%AF%E5%9F%BA%E7%A1%80/%E4%BC%A0%E6%99%BA%E6%92%AD%E5%AE%A2-HTML/media/sm.jpg" /> 



### 路径(重点、难点)

<img src="D:/BDND/StepFullStack/AANotes/%E5%89%8D%E7%AB%AF%E5%9F%BA%E7%A1%80/%E4%BC%A0%E6%99%BA%E6%92%AD%E5%AE%A2-HTML/media/dt.png" width="400" />

<img src="D:/BDND/StepFullStack/AANotes/%E5%89%8D%E7%AB%AF%E5%9F%BA%E7%A1%80/%E4%BC%A0%E6%99%BA%E6%92%AD%E5%AE%A2-HTML/media/lj.png" />

实际工作中，通常新建一个文件夹专门用于存放图像文件，这时再插入图像，就需要采用“路径”的方式来指定图像文件的位置。

根目录  当前目录 



路径可以分为： 相对路径和绝对路径



#### 相对路径

以引用文件之网页所在位置为参考基础，而建立出的目录路径。因此，当保存于不同目录的网页引用同一个文件时，所使用的路径将不相同，故称之为相对路径。

1. 图像文件和HTML文件位于同一文件夹：只需输入图像文件的名称即可，如&lt;img src="logo.gif" /&gt;。
2. 图像文件位于HTML文件的下一级文件夹：输入文件夹名和文件名，之间用“/”隔开，如&lt;img src="img/img01/logo.gif" /&gt;。
3. 图像文件位于HTML文件的上一级文件夹：在文件名之前加入“../” ，如果是上两级，则需要使用 “../ ../”，以此类推，如&lt;img src="../logo.gif" /&gt;。

#### 绝对路径

绝对路径以Web站点根目录为参考基础的目录路径。之所以称为绝对，意指当所有网页引用同一个文件时，所使用的路径都是一样的

“D:\web\img\logo.gif”，或完整的网络地址，例如“http://www.itcast.cn/images/logo.gif”。







# HTML常用标签

 首先 HTML和CSS是两种完全不同的语言，我们学的是结构，就只写HTML标签，认识标签就可以了。 不会再给结构标签指定样式了。

 HTML标签有很多，这里我们学习最为常用的，后面有些较少用的，我们可以查下手册就可以了。 

## 排版标签

排版标签主要和css搭配使用，显示网页结构的标签，是网页布局最常用的标签。

### 标题标签hN&title (熟记)

 单词缩写：  head   头部. 标题     title  文档标题

为了使网页更具有语义化，我们经常会在页面中用到标题标签，HTML提供了6个等级的标题，即

 <h1>、<h2>、<h3>、<h4>、<h5>和<h6>


~~~
标题标签语义：  作为标题使用，并且依据重要性递减
~~~

其基本语法格式如下：

```html
<hn>   标题文本   </hn>
```



> 注意：  h1 标签因为重要，尽量少用，不要动不动就向你扔了一个h1。 一般h1 都是给logo使用，或者页面中最重要标题信息。

  <img src="media/dog.gif" />

```
    传智播客学前端，
　　前端学院四十班。
　　新班强哥讲台站，
　　又带新颜技术钻。
　　标题一共六级选，
　　具体效果刷新见。
　　        ------强哥
```



### 段落标签p( 熟记)

单词缩写：  paragraph  段落  [ˈpærəgræf]    无须记这个单词

 在网页中要把文字有条理地显示出来，离不开段落标签，就如同我们平常写文章一样，整个网页也可以分为若干个段落，而段落的标签就是

~~~html
<p>  文本内容  </p>
~~~

是HTML文档中最常见的标签，默认情况下，文本在一个段落中会根据浏览器窗口的大小自动换行。

### 水平线标签hr(认识)

单词缩写：  horizontal  横线    [ˌhɔrəˈzɑntl]    同上

在网页中常常看到一些水平线将段落与段落之间隔开，使得文档结构清晰，层次分明。这些水平线可以通过插入图片实现，也可以简单地通过标签来完成，<hr />就是创建横跨网页水平线的标签。其基本语法格式如下：

```html
<hr />是单标签
```

 在网页中显示默认样式的水平线。

课堂练习2：    新闻页面 

<img src="media/sh.png" /> 







### 换行标签br(熟记)

单词缩写：  break   打断 ,换行

在HTML中，一个段落中的文字会从左到右依次排列，直到浏览器窗口的右端，然后自动换行。如果希望某段文本强制换行显示，就需要使用换行标签

```html
<br />
```

这时如果还像在word中直接敲回车键换行就不起作用了。

课堂一练

关于标签下列说法正确的是 

(A) P1是段落标签

(B) H1 是标题标签

(C) Hr是换行标签

(D) Br 是一条直线

 2 关于标签下列说法不正确的是

(A) H标签有6个等级分别是<h1> <h2> <h3> <h4> <h5>和<h6>

(B) h1到h6 文字从小到大 

(C) p标签一行只能放一个

(D) P是段落标签会给文字加上段落的语义

### 盒子标签div span(重点)

div  span    是没有语义的     是我们网页布局主要的2个盒子     css+div

div 就是  division  的缩写   分割， 分区的意思  其实有很多div 来组合网页。

span, 跨度，跨距；范围    

语法格式：

~~~html
<div> 这是头部 </div>    <span>今日价格</span>
~~~



## 文本格式化标签 粗体斜体加线(熟记)

在网页中，有时需要为文字设置粗体、斜体或下划线效果，这时就需要用到HTML中的文本格式化标签，使文字以特殊的方式显示。

<img src="media/tab.png" />

  b  i  s  u   只有使用 没有 强调的意思       strong   em  del   ins  语义更强烈





## 图像标签img (重点)

单词缩写：   image  图像

HTML网页中任何元素的实现都要依靠HTML标签，要想在网页中显示图像就需要使用图像标签，接下来将详细介绍图像标签<img />以及和他相关的属性。其基本语法格式如下：

该语法中src属性用于指定图像文件的路径和文件名，他是img标签的必需属性。

```html
<img src="图像URL" />
```



<img src="media/img.png" />



**当网页显示图片时,鼠标滑上图片显示文字描述是以下哪个属性******

(A) 设置alt属性

(B) 设置title属性

(C) 设置href 属性

(D) 设置src 属性

 

**2  在HTML中，使用<img>标签插入图像，下列选项关于<img>的src属性说法正确的是 **

(A) 用来设置图片的格式

(B) 用来设置图片的所在位置

(C) 用来设置鼠标指向图片时显示的文字

(D) 用来设置图片是否能正确显示 



## 链接标签a(重点)

单词缩写：  anchor 的缩写  [ˈæŋkə(r)] 。基本解释 锚, 铁锚 的

在HTML中创建超链接非常简单，只需用标签环绕需要被链接的对象即可，其基本语法格式如下：

```html
<a href="跳转目标" target="目标窗口的弹出方式">文本或图像</a>
```

href：用于指定链接目标的url地址，当为标签应用href属性时，它就具有了超链接的功能。  Hypertext Reference的缩写。意思是超文本引用

target：用于指定链接页面的打开方式，其取值有_self和_blank两种，其中_self为默认值，_blank为在新窗口中打开方式。

注意：

1.外部链接 需要添加 http:// www.baidu.com

2.内部链接 直接链接内部页面名称即可 比如 < a href="index.html"> 首页 </a >

3.如果当时没有确定链接目标时，通常将链接标签的href属性值定义为“#”(即href="#")，表示该链接暂时为一个空链接。

4.不仅可以创建文本超链接，在网页中各种网页元素，如图像、表格、音频、视频等都可以添加超链接。

### 锚点定位 （难点）

通过创建锚点链接，用户能够快速定位到目标内容。
创建锚点链接分为两步：

~~~html
1.使用“a href=”#id名>“链接文本"</a>创建链接文本（被点击的）
  <a href="#two">   

2.使用相应的id名标注跳转目标的位置。
  <h3 id="two">第2集</h3> 
~~~





## 整体链接打开状态标签base(基本)

base 可以设置整体链接的打开状态   

base 写到  <head>  </head>  之间

把所有的连接 都默认添加 target="_blank"

 <img src="media/base.png" />

课堂一练

 1在HTML中，关于a标签说法不正确的是（）

(A) a标签可以通过href属性跳转到另外一个页面

(B) a标签可以通过targer属性设置在是否在新窗口中打开

(C) a标签只能在当前页面设置锚点链接，让用户能够快速定位到目标内

(D) a标签可以通过href="#"设置一个空链接

2如果想跳转到当前页面里名为show的锚点，下列写法是正确的

A  < a href=".show">跳转</a>

B < a href="#show">跳转</a>

C < a href=" show">跳转</a>

D < a src=" #show">跳转</a>

 

3如果想跳转到同目录下的名为success.html文件里名为show的锚点，下列写法是正确的

(A) < a href="success.html#show">跳转</a>

(B)  < a href="#show">跳转</a> 

(C)  < a href="success#show">跳转</a>
(D) < a src="success.html#show">跳转</a>

##  特殊字符标签 （理解）

 <img src="media/zifu.png" />

## 注释标签

在HTML中还有一种特殊的标签——注释标签。如果需要在HTML文档中添加一些便于阅读和理解但又不需要显示在页面中的注释文字，就需要使用注释标签。其基本语法格式如下：
​        

```html
    <!-- 注释语句 -->   ctrl + /       或者 ctrl +shift + / 
```

注释内容不会显示在浏览器窗口中，但是作为HTML文档内容的一部分，也会被下载到用户的计算机上，查看源代码时就可以看到。

注释重要性：



<img src="media/zs.png" />



总结

每一天都有一个主题 我们HTML第一天的主题就是 <认识标签>

学HTML 之前 觉得 很神秘  

<img src="media/z.png" />

等你学完之后忽然发现

<img src="media/rh.jpg" width="615" />



总结今天的思路贯穿线：

<img src="media/a.png" width="1000" />

## 列表标签

什么是列表？

<img src="media/list.png" />

把…制成表,以表显示

容器里面装载着文字或图表的一种形式，叫列表。

列表最大的特点就是  整齐 、整洁、 有序

### 无序列表 ul （重点）

无序列表的各个列表项之间没有顺序级别之分，是并列的。其基本语法格式如下：

```html
<ul>
  <li>列表项1</li>
  <li>列表项2</li>
  <li>列表项3</li>
  ......
</ul>
```

比如下面这些，新闻是没有顺序的，不用排队，先到先得，后发布先显示。

<img src="media/ul.png" />

脚下留心：

```
 1. <ul></ul>中只能嵌套<li></li>，直接在<ul></ul>标签中输入其他标签或者文字的做法是不被允许的。
 2. <li>与</li>之间相当于一个容器，可以容纳所有元素。
 3. 无序列表会带有自己样式属性，放下那个样式，一会让CSS来！
```

### 有序列表 ol （了解）
<img src="media/gold.png" />


有序列表即为有排列顺序的列表，其各个列表项按照一定的顺序排列定义，有序列表的基本语法格式如下：

```html
<ol>
  <li>列表项1</li>
  <li>列表项2</li>
  <li>列表项3</li>
  ......
</ol>
```

  所有特性基本与ul 一致。  

  但是实际工作中， 较少用 ol img src="media/1.jpg" />



### 自定义列表dl/dt/dd（理解）

定义列表常用于对术语或名词进行解释和描述，定义列表的列表项前没有任何项目符号。其基本语法如下：

```html
<dl>
  <dt>名词1</dt>
  <dd>名词1解释1</dd>
  <dd>名词1解释2</dd>
  ...
  <dt>名词2</dt>
  <dd>名词2解释1</dd>
  <dd>名词2解释2</dd>
  ...
</dl>
```

 <img src="media/2.jpg" /> 



用的还可以：

<img src="media/mix.png" />





## 表格标签(会使用)

![img](http://zcr4.ncfstatic.com/attachment/201403/27/10/5333888008f05_thumb_670x0.jpg)



存在即是合理的。  表格的现在还是较为常用的一种标签，但不是用来布局，常见处理、显示表格式数据。

<img src="media/table.png" />

ps:  这些地方用表格，你会觉得生活还是那么美好。。。。忍不住想说  PPAP i hava a pen  



### 创建表格

在HTML网页中，要想创建表格，就需要使用表格相关的标签。创建表格的基本语法格式如下：

```html
<table>
  <tr>
    <th>单元格内的文字</th>
    ...
  </tr>
  <tr>
    <td>单元格内的文字</td>
    ...
  </tr>
  ...
</table>
```

在上面的语法中包含三对HTML标签，分别为 &lt;table&gt;</table&gt;、&lt;tr&gt;</tr&gt;、&lt;td&gt;</td&gt;，他们是创建表格的基本标签，缺一不可，下面对他们进行具体地解释



~~~
1.table用于定义一个表格。

2.tr 用于定义表格中的一行，必须嵌套在 table标签中，在 table中包含几对 tr，就有几行表格。

3.td /td：用于定义表格中的单元格，必须嵌套在<tr></tr>标签中，一对 <tr> </tr>中包含几对<td></td>，就表示该行中有多少列（或多少个单元格）。
~~~

注意：

```
1. <tr></tr>中只能嵌套<td></td>
```

```
2. <td></td>标签，他就像一个容器，可以容纳所有的元素
```



### 表格属性

<img src="media/tt.png" />

三参为0    border  cellpadding  cellspacing  为  0

### 表头标签thead

表头单元格一般位于表格的第一行或第一列，其文本加粗居中，如下图所示，即为设置了表头的表格。设置表头非常简单，只需用表头标签&lt;th&gt;</th&gt;替代相应的单元格标签&lt;td&gt;</td&gt;即可。 

 <img src="media/th.png" />

### 表格结构thead+tbody（了解）

```
在使用表格进行布局时，可以将表格划分为头部、主体和页脚（页脚因为有兼容性问题，我们不在赘述），具体 如下所示：

<thead></thead>：用于定义表格的头部。

必须位于<table></table> 标签中，一般包含网页的logo和导航等头部信息。


<tbody></tbody>：用于定义表格的主体。

位于<table></table>标签中，一般包含网页中除头部和底部之外的其他内容。
```





<img src="media/thead.png" />

### 表格标题caption

**表格的标题： caption**

**定义和用法**

caption 元素定义表格标题。

```html
<table>
   <caption>我是表格标题</caption>
</table>
```

caption 标签必须紧随 table 标签之后。

只存在 表格里面





您只能对每个表格定义一个标题。通常这个标题会被居中于表格之上。

### 合并单元格rowspan,colspan(难点)

跨行合并：rowspan    跨列合并：colspan

合并单元格的思想：

​     将多个内容合并的时候，就会有多余的东西，把它删除。    例如 把 3个 td 合并成一个， 那就多余了2个，需要删除。

​     公式：  删除的个数  =  合并的个数  - 1   

   合并的顺序 先上 后下   先左  后右

1. 先确定是跨行还是跨列合并
2. 根据 先上 后下   先左  后右的原则找到目标单元格 
3. 删除单元格   删除的个数  =  合并的个数  - 1  

### 总结表格

1. 表格提供了HTML 中定义表格式数据的方法。

2. 表格中由行中的单元格组成。

3. 表格中没有列元素，列的个数取决于行的单元格个数。

4. 表格不要纠结于外观，那是CSS 的作用。

   

   **表格的学习要求：  能手写表格结构，并且能合并单元格。**

## 表单标签(掌握)

### 综合HTML样例

```
<!--表单域-->
<form name="FormName" action="demo_form.php" method="get" target="" enctype="">

    <!-- 单行文本域 -->
    <label for="forID">Male</label><!--label标签的for属性应当与相关元素的 id 属性相同。-->
    <input id="forID" type="text" name="" value=""><br>

    <!-- 多行文本框 -->
    <textarea rows="10" cols="30">我是一个文本框。</textarea><br>

    <!-- 密码框 -->
    <label for="Password">Password:</label>
    <input id="Password" type="password" name="pwd"><br>

    <!-- 单选按钮 -->
    <input type="radio" name="sex" value="male">Male<br>
    <input type="radio" name="sex" value="female">Female<br>

    <!-- 复选框 -->
    <input type="checkbox" name="vehicle" value="Bike" checked="true">I have a bike<br>
    <input type="checkbox" name="vehicle" value="Car" checked="true">I have a car<br>

    <!-- 下拉列表 -->
    <select>
      <option value="volvo" label="Volvo" selected="true"></option>
      <option value="saab" label="Saab"></option>
    </select><br>
    <!-- 下拉菜单 -->
    <select>
      <optgroup label="Swedish Cars">
        <option value="volvo">Volvo</option>
        <option value="saab">Saab</option>
      </optgroup>
      <optgroup label="German Cars">
        <option value="mercedes">Mercedes</option>
        <option value="audi">Audi</option>
      </optgroup>
    </select>

    <!-- 提交按钮 -->
    <input type="submit" value="提交">
    
</form>
```



现实中的表单，类似我们去银行办理信用卡填写的单子。 如下图

<img src="media/car.jpg"  width="500" />

表单目的是为了收集用户信息。

在我们网页中， 我们也需要跟用户进行交互，收集用户资料，此时也需要表单。

在HTML中，一个完整的表单通常由表单控件（也称为表单元素）、提示信息和表单域3个部分构成。

<img src="media/bd.png" />

  表单控件：

​       包含了具体的表单功能项，如单行文本输入框、密码输入框、复选框、提交按钮、重置按钮等。

  提示信息：

​        一个表单中通常还需要包含一些说明性的文字，提示用户进行填写和操作。

  表单域：  

​      他相当于一个容器，用来容纳所有的表单控件和提示信息，可以通过他定义处理表单数据所用程序的url地址，以及数据提交到服务器的方法。如果不定义表单域，表单中的数据就无法传送到后台服务器。

### input 控件(重点)

input 输入的意思 

在上面的语法中，&lt;input /&gt;标签为单标签，type属性为其最基本的属性  类型 ，其取值有多种，用于指定不同的控件类型。除了type属性之外，&lt;input /&gt;标签还可以定义很多其他的属性，其常用属性如下表所示。

type  说明了属于那种表单



radio  如果是一组，我们必须给他们命名相同的名字 name   这样就可以多个选其中的一个啦



<img src="media/input.png" />

###  label标签(理解)

label 标签为 input 元素定义标注（标签）。

table  

作用：  用于绑定一个表单元素, 当点击label标签的时候, 被绑定的表单元素就会获得输入焦点

如何绑定元素呢？

for 属性规定 label 与哪个表单元素绑定。

```html
<label for="male">Male</label>
<input type="radio" name="sex" id="male" value="male">
```

### textarea控件(文本域)

text  文本框  只能写一行文本呢

textarea 文本域

如果需要输入大量的信息，就需要用到&lt;textarea&gt;&lt;/textarea&gt;标签。通过textarea控件可以轻松地创建多行文本输入框，其基本语法格式如下：

```html
<textarea cols="每行中的字符数" rows="显示的行数">
  文本内容
</textarea>
```

<img src="media/textarea.png" />

### 下拉菜单 select,option

使用select控件定义下拉菜单的基本语法格式如下     select 选择

```html
<select>
  <option>选项1</option>
  <option>选项2</option>
  <option>选项3</option>
  ...
</select>
```

注意：

1. &lt;select&gt;</select&gt;中至少应包含一对&lt;option></option&gt;。
2. 在option 中定义selected =" selected "时，当前项即为默认选中项。

### 表单域 form

在HTML中，form标签被用于定义表单域，即创建一个表单，以实现用户信息的收集和传递，form中的所有内容都会被提交给服务器。创建表单的基本语法格式如下：

```html
<form action="url地址" method="提交方式" name="表单名称">
  各种表单控件
</form>
```

常用属性：

1. Action
   在表单收集到信息后，需要将信息传递给服务器进行处理，action属性用于指定接收并处理表单数据的服务器程序的url地址。
2. method
   用于设置表单数据的提交方式，其取值为get或post。
3. name
   用于指定表单的名称，以区分同一个页面中的多个表单。

注意：  每个表单都应该有自己表单域。





# 查文档

经常查阅文档是一个非常好的学习习惯。

W3C :  http://www.w3school.com.cn/

MDN: https://developer.mozilla.org/zh-CN/



