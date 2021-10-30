1.css简介

![image-20211027222915743](C:\Users\123\AppData\Roaming\Typora\typora-user-images\image-20211027222915743.png)

css也是一种标记语言

css主要用于设置html页面中的文本内容（字体、大小、对齐方式）、图片的外形（宽高、边框样式、边距等）以及版面的布局和外观显示样式等

html主要坐结构，显示元素内容；css美化html，布局网页

css最大价值：由html专注去做结构呈现，样式交给css，即结构（html）与样式（css）相分离

css规则由两个主要的部分构成：选择器以及一条或多条声明

![image-20211027223756483](C:\Users\123\AppData\Roaming\Typora\typora-user-images\image-20211027223756483.png)

选择器时用于指定css样式的html标签，花括号内是该对象设置的具体样式

属性和属性值以“链值对”的形式出现

属性是指对指定的对象设置的样式属性，例如字体大小、文本颜色等

属性和属性值之间用：隔开

![image-20211027224344217](C:\Users\123\AppData\Roaming\Typora\typora-user-images\image-20211027224344217.png)

css写在<head></head>里边的<style></style>的里边，结尾要有；	

空格规范

属性值前面，冒号后面，保留一个空格

选择器（标签）和大括号中间保留空格



选择器分为基础选择器和符合选择器

2.css基础选择器，由单个选择器组成

基础选择器又包括标签选择器、类选择器、id选择器和通配符选择器

2.1css选择器的的作用

选择器（选择符）就是工具不同需求把不同的标签选出来

2.3标签选择器（元素选择器）是指用html标签名称作为选择器，按标签名称分类，为页面中某一类标签指定统一的css样式

作用：标签选择器可以把某一类标签全部选择出来，比如所有的div标签和所有的span标签

只能快速为页面中同类型的标签统一设置样式，不能设计差异化样式，只能选择全部的当前标签

2.4类选择器

可以单独选一个或者某几个标签，可以使用类选择器

结构需要用class属性来调用class类的意思

样式点定义，结构类调用

![image-20211027230501353](C:\Users\123\AppData\Roaming\Typora\typora-user-images\image-20211027230501353.png)

注意：1类选择器使用.进行表示，后面紧跟类名（自定义）（不能用标签名）

2长名称或词组可以使用中横线来为选择器命名，不要使用纯数字。中文来命名，尽量使用英文字母



利用类选择器画三个盒子，设置北京颜色用background-color

![image-20211028204850966](C:\Users\123\AppData\Roaming\Typora\typora-user-images\image-20211028204850966.png)



类选择器-多类名

我们可以给一个标签指定多个类名，从而达到更多的选择目的。这些类名都可以选出这个标签。

简单理解就是一个标签有多个名字

多类名使用方式

![image-20211028224405709](C:\Users\123\AppData\Roaming\Typora\typora-user-images\image-20211028224405709.png)

2.5id选择器：可以为标有特点id的html元素指定特定的样式

html元素以id属性来设置id选择器，css中di选择器以#来定义

![image-20211028224833495](C:\Users\123\AppData\Roaming\Typora\typora-user-images\image-20211028224833495.png)

![image-20211028224954958](C:\Users\123\AppData\Roaming\Typora\typora-user-images\image-20211028224954958.png)

id选择器和类选择器的区别

类选择器（class）好比人的名字，，一个人可以有多个名字，同时一个名字也可以被多个人调用。

id选择器（id）：样式#定义，结构id调用，但只能调用一次

最大的区别在于使用次数上

类选择器在修改样式中用的最多，id选择器一般用于页面唯一性的元素上，经常和js搭配使用

2.6通配选择器

在css中，通配选择器使用*定义，它表示选取页面中所有元素（标签）

![image-20211028225604842](C:\Users\123\AppData\Roaming\Typora\typora-user-images\image-20211028225604842.png)

通配符选择器不需要调用，自动就给所有的元素使用样式

2.7基础选择器总结

![image-20211028225832817](C:\Users\123\AppData\Roaming\Typora\typora-user-images\image-20211028225832817.png)

3.css字体属性

css fonts（字体）属性用于定义字体系列、大小、粗细和文字样式(如斜体)

3.1字体系列

css使用fant-family属性定义文本的字体系列

![image-20211028230456643](C:\Users\123\AppData\Roaming\Typora\typora-user-images\image-20211028230456643.png)

3.2字体大小

css使用font-size属性定义字体大小

![image-20211028230754062](C:\Users\123\AppData\Roaming\Typora\typora-user-images\image-20211028230754062.png)

标题标签比较特殊，需要单独指定文字大小

3.3字体粗细

css使用font-weight属性设置文本字体的粗细

![image-20211029175327400](C:\Users\123\AppData\Roaming\Typora\typora-user-images\image-20211029175327400.png)

3.4

css使用font-style属性设置文本的风格

![image-20211029175551616](C:\Users\123\AppData\Roaming\Typora\typora-user-images\image-20211029175551616.png)

3.5字体复合属性

字体属性可以把以上文字样式综合来写，这样可以更节约代码

![image-20211029181501096](C:\Users\123\AppData\Roaming\Typora\typora-user-images\image-20211029181501096.png)

3.6字体属性总结

![image-20211029181604787](C:\Users\123\AppData\Roaming\Typora\typora-user-images\image-20211029181604787.png)

4.css文本属性

css text属性可以定义文本的外观，比如文本的颜色、对齐文本、装饰文本、文本缩进、行间距等

4.1文本颜色：color属性用于定义文本的颜色

![image-20211029182853974](C:\Users\123\AppData\Roaming\Typora\typora-user-images\image-20211029182853974.png)

4.2

text-align属性用于设置元素内文本内容的水平对齐方式

![image-20211029183427347](C:\Users\123\AppData\Roaming\Typora\typora-user-images\image-20211029183427347.png)

4.3装饰文本

text-decoration属性规定添加到文本的修饰。可以给文本添加下划线、删除线、上划线等

![image-20211029183735018](C:\Users\123\AppData\Roaming\Typora\typora-user-images\image-20211029183735018.png)

4.3文本缩进

text-indent属性用来指定文本的第一行的缩进，通常是将段落的首行缩进

![image-20211029184622175](C:\Users\123\AppData\Roaming\Typora\typora-user-images\image-20211029184622175.png)

4.5行间距

line-height属性用于设置行间的距离（行高）。可以控制文字行与行之间的距离

4.6文本属性总结

![image-20211029184923136](C:\Users\123\AppData\Roaming\Typora\typora-user-images\image-20211029184923136.png)

5css引入方式

5.1css的三种样式表

按照css样式书写的位置（或者引入的方式），css样式表可以分为三大类

行内样式表（行内式）

内部样式表（嵌入式）

外部样式表（链接式）

5.2内部样式表

内部样式表是写到html页面内部。是将所有的css代码抽取出来，单独放到一个style标签中

![image-20211029190207765](C:\Users\123\AppData\Roaming\Typora\typora-user-images\image-20211029190207765.png)

5.4实际开发都是外部样式。适合于样式比较多的情况。核心是：样式单独写到css文件中，之后把css文件引用到html页面中使用

css文件里面只有样式没有标签

引入外部样式表分为两步：

1.新建一个后缀名为.css的样式文件，把所有css代码都放入此文件中

2.在html页面中，使用link标签引入这个文件。

<link rel="stylesheet" href="css文件路径“>

![image-20211029195424039](C:\Users\123\AppData\Roaming\Typora\typora-user-images\image-20211029195424039.png)

5.5css引入方式总结

![image-20211029195600759](C:\Users\123\AppData\Roaming\Typora\typora-user-images\image-20211029195600759.png)

7.chrome调试工具

1.打开调试工具

打开chrome浏览器，按下f12键或者右击页面空白 检查

2使用调试工具

ctrl+滚轮可以放大开发者工具代码大小

左边是html元素结构，右边是css样式

右边css样式可以改动数值（左右箭头或直接输入）和查看颜色

ctrl+0复原浏览器大小

如果惦记元素，发现右侧没有样式引入，极有可能是类名或者样式引入错误

如果有样式，但是样式前面有黄色叹号提示，则是样式书写错误





1.emmet语法

1.1快速生成html结构语法

生成标签，直接输入标签名，按tab键即可，比如div然后tab键就可以生成<div></div>

如果想要生成多个相同标签，加上*就可以了 ，比如div*3就可以快速生成三个div

如果有父子级关系的标签，可以用>，比如ul>li就可以了

如果有兄弟关系的标签，用+就可以了，比如div+p

如果生成带有类名或者id名字的，直接写.demo或者#two tab键就可以了

如果生成的div类名是有顺序的，可以用自增符号￥

如果想要在生成的标签内部写内容可以用{}表示 

1.2快速生成css样式语法

css基本采取简写形式即可

比如w200按tab就可以生成width：200px

lh26按tab就可以生成line-height：26px

1.3快速格式化代码



1.css的复合选择器

1.1什么是复合选择器

在css中，可以根据选择器的类型把选择器分为基础选择器和复合选择器，复合选择器是建立在基础选择器之上，对基本选择器进行组合形成的

复合选择器可以更准确、高效的选择目标元素（标签）

复合选择器是由两个或多个基础选择器，通过不同的方式组合而成的

常用的复合选择器包括：后代选择器、子选择器、并集选择器、伪类选择器等等

1.2后代选择器（重要）

后代选择器又称为包含选择器 ，可以选择父元素里面子元素。其写法就是把外层标签写在前面，内层标签写在后面，中间用空格分隔。当标签发生嵌套时，内层标签就成为外层标签的后代

![image-20211030093407869](C:\Users\123\AppData\Roaming\Typora\typora-user-images\image-20211030093407869.png)

![image-20211030094226226](C:\Users\123\AppData\Roaming\Typora\typora-user-images\image-20211030094226226.png)

1.3子选择器（重要）

子元素选择器只能作为某元素的最近一级子元素。简单理解就是选亲儿子元素

![image-20211030094708229](C:\Users\123\AppData\Roaming\Typora\typora-user-images\image-20211030094708229.png)

![image-20211030094755482](C:\Users\123\AppData\Roaming\Typora\typora-user-images\image-20211030094755482.png)

1.4并集选择器（重要）

并集选择器可以选择多组标签，同时为它们定义相同的样式。通常用于集体声明

并集选择器时各选择器通过英文逗号（，）连接而成，任何形式的选择器都可以作为并集选择器的一部分

![image-20211030095407545](C:\Users\123\AppData\Roaming\Typora\typora-user-images\image-20211030095407545.png)

1.5伪类选择器

伪类选择器用于向某些选择器添加特殊的效果，比如给连接添加特殊效果，或选择第一个，第n个元素

1.6链接伪类选择器

![image-20211030100659665](C:\Users\123\AppData\Roaming\Typora\typora-user-images\image-20211030100659665.png)

注意：为了确保生效，请按照lvha的循顺序声明：link-：visited-：hover-：active。

因为a链接在浏览器中具有默认样式，所以我们实际工作中都需要给链接单独指定样式

1.7focus伪类选择器：用于选取获得焦点的表单元素

焦点就是光标，一般情况<input>类表单元素才能获取，因此这个选择器也主要针对表单元素

![image-20211030102624142](C:\Users\123\AppData\Roaming\Typora\typora-user-images\image-20211030102624142.png)

1.8复合选择器总结

![image-20211030102700814](C:\Users\123\AppData\Roaming\Typora\typora-user-images\image-20211030102700814.png)



2.css的元素显示模式

2.1元素显示模式就是元素（标签）以声明方式进行显示，比如<div> 自己占一行，比如一行可以放多个<span>

html元素一般分为块元素和行内元素两种类型

常见的块元素有<h1>~<h6>、<p>、<div>、<ul>、<ol>、<li>等，其中<div>标签是最典型的块元素

块级元素的特点：比较霸道，自己独占一行

高度、宽度、外边距以及内边距都可以控制

宽度默认是容器（父级宽度）的100%

是一个容器及盒子，里面可以放行内或者块级元素

注意：文字类的元素内不能使用块级元素

<!p>标签主要用于存放文字，因此<p>里面不能放块级元素，特别是不能放<div>

同理，<h1>~<h6>等都是文字类块级标签，里面也不能放其他块级元素

2.2行内元素

常见的行内元素有<a>、<strong>、<b>、<em>、<del>、<s>、<ins>、<u>、<span>等，其中<span>标签是最典型的行内元素。有的地方也将行内元素称为内联元素

行内元素的特点：相邻行内元素在一行上，一行可以显示多个。

高、宽直接设置是无效的。

默认宽度就是它本身内容的宽度。

行内元素只能容纳文本或其他行内元素

注意：链接里面不能再放链接

特殊情况链接<a>里面可以放块级元素，但是给<a>转换一下块级模式最安全

2.3行内块元素

在行内元素中有几个特殊的标签——<img/>、<input/>、<td>,它们同时具有块元素和行内元素的特点，有些资料称它们为行内块元素

行内块元素的特点：相邻行内元素（行内块）在一行上，但是它们之间会有空白缝隙。一行可以显示多个（行内元素特点）

默认宽度就是它本身内容的宽度（行内元素特点）

高度、行高、外边距以及内边距都可以控制（块元素特点）

2.4元素显示模式总结

![image-20211030110801394](C:\Users\123\AppData\Roaming\Typora\typora-user-images\image-20211030110801394.png)

