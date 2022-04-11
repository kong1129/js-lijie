## 以下内容是描述JavaScript的历史
js是一种高级的解释类型的语言，是一门基于原形或者是头疼函数的语言内容
## JavaScript
编程范型	事件驱动、函数式、指令式
设计者	创造者布兰登·艾克及ECMAScript规范的其他关键贡献者
发行时间	1995年12月4日，​26年前[1]
稳定版本	
ECMAScript 2019[2] （ 2019年6月，​2年前 ）
预览版本	
ECMAScript 2020
类型系统	动态类型、鸭子类型
文件扩展名	
.js.mjs[3]
主要实现产品
V8、JavaScriptCore、SpiderMonkey、Chakra

## 肇始于网景
1993年，国家超级电脑应用中心（NCSA）发表了NCSA Mosaic，这是最早流行的图形接口网页浏览器，它在万维网的普及上发挥了重要作用[11]。1994年，Mosaic的主要开发人员随即创立了Netscape公司，并雇用了许多原来的NCSA Mosaic开发者用来开发Netscape Navigator，该公司的目标是取代NCSA Mosaic成为世界第一的网页浏览器。在四个月内，已经占据了四分之三的浏览器市场，并成为1990年代互联网的主要浏览器[12]。网景预见到网络需要变得更动态。公司的创始人马克·安德森认为HTML需要一种胶水语言，让网页设计师和兼职程序员可以很容易地使用它来组装图片和插件之类的组件，且代码可以直接编写在网页标记中。
1995年，网景招募了布兰登·艾克，目标是把Scheme语言嵌入到Netscape Navigator浏览器当中[13]。但更早之前，网景已经跟昇阳合作在Netscape Navigator中支持Java，这时网景内部产生激烈的争论[14]。后来网景决定发明一种与Java搭配使用的辅助脚本语言并且语法上有些类似[15]，这个决策导致排除了采用现有的语言，例如Perl、Python、Tcl或Scheme。为了在其他竞争提案中捍卫JavaScript这个想法，公司需要有一个可以运作的原型。艾克在1995年5月仅花了十天时间就把原型设计出来了。
最初命名为Mocha，1995年9月在Netscape Navigator 2.0的Beta版中改名为LiveScript，同年12月，Netscape Navigator 2.0 Beta 3中部署时被重命名为JavaScript[1][16]，当时网景公司与昇阳电脑公司组成的开发联盟为了让这门语言搭上Java这个编程语言“热词”，因此将其临时改名为JavaScript，日后这成为大众对这门语言有诸多误解的原因之一[17]。
微软采纳
微软公司于1995年首次推出Internet Explorer，从而引发了与Netscape的浏览器大战。微软对Netscape Navigator解释器进行了逆向工程，创建了JScript，以与处于市场领导地位的网景产品同台竞争。JScript也是一种JavaScript实现，这两个JavaScript语言版本在浏览器端共存意味着语言标准化的缺失，发展初期，JavaScript的标准并未确定，同期有网景的JavaScript，微软的JScript双峰并峙。除此之外，微软也在网页技术上加入了不少专属对象，使不少网页使用非微软平台及浏览器无法正常显示[18][19]，导致在浏览器大战期间网页设计者通常会把“用Netscape可达到最佳效果”或“用IE可达到最佳效果”的标志放在主页[18][20]。
标准化
1996年11月，网景正式向ECMA（欧洲计算机制造商协会）提交语言标准。1997年6月，ECMA以JavaScript语言为基础制定了ECMAScript标准规范ECMA-262。JavaScript成为了ECMAScript最著名的实现之一[21]。除此之外，ActionScript和JScript也都是ECMAScript规范的实现语言。尽管JavaScript作为给非程序人员的脚本语言，而非作为给程序人员的脚本语言来推广和宣传，但是JavaScript具有非常丰富的特性。
## 概论
一般来说，完整的JavaScript包括以下几个部分：
ECMAScript，描述了该语言的语法和基本对象
文档对象模型（DOM），描述处理网页内容的方法和接口
浏览器对象模型（BOM），描述与浏览器进行交互的方法和接口
JavaScript的基本特点如下：
是一种解释性脚本语言（代码不进行预编译）。
主要用来向HTML页面添加交互行为。
可以直接嵌入HTML页面，但写成单独的js文件有利于结构和行为的分离。
JavaScript常用来完成以下任务：
嵌入动态文本于HTML页面
对浏览器事件作出响应
读写HTML元素
在数据被提交到服务器之前验证数据
检测访客的浏览器信息
控制cookie，包括创建和修改等

## 　以下内容是javaScript诞生记
（1）借鉴C语言的基本语法；

（2）借鉴Java语言的数据类型和内存管理；

（3）借鉴Scheme语言，将函数提升到"第一等公民"（first class）的地位；
（4）借鉴Self语言，使用基于原型（prototype）的继承机制。

javascript语言实际上两种语言风格的混合产物--(简化的)函数式编程 +(简化的)面向对象编程

##  1.为什么javaScript有设计缺陷
导致javascript的设计不够完善  

1.不适合开发大型程序 
2.非常小的标准库
3.null和undefined
4.全局变量难以控制
5.自动插入行尾分号
6.加号运算符
7.NaN
8.数组和对象的区分  9.==和===
10.基本类型的包装对象

## 看待javascript的设计缺陷
javascript 









