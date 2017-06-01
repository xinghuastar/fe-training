# ch1

0517
newnewnew
https://www.tutorialspoint.com/html/html_overview.htm
50 hours (6 hours/per day) 4 days ,
Day 1:
html 
定义:
HTML 是用来描述网页的一种语言。
•	HTML 指的是超文本标记语言 (Hyper Text Markup Language)
•	HTML 不是一种编程语言，而是一种标记语言 (markup language)
•	标记语言是一套标记标签 (markup tag)
•	HTML 使用标记标签来描述网页

Html 发展史
版本	年份
HTML	1991
HTML+	1993
HTML 2.0	1995
HTML 3.2	1997
HTML 4.01	1999
XHTML 1.0	2000
HTML5	2012
XHTML5	2013

XHTML, XHTML 与 HTMl
什么是 XHTML？
•	XHTML 指的是可扩展超文本标记语言
•	XHTML 与 HTML 4.01 几乎是相同的
•	XHTML 是更严格更纯净的 HTML 版本
•	XHTML 是以 XML 应用的方式定义的 HTML
•	XHTML 是 2001 年 1 月发布的 W3C 推荐标准
•	XHTML 得到所有主流浏览器的支持

1.	html Doctype
<!DOCTYPE> 声明
Web 世界中存在许多不同的文档。只有了解文档的类型，浏览器才能正确地显示文档。
HTML 也有多个不同的版本，只有完全明白页面中使用的确切 HTML 版本，浏览器才能完全正确地显示出 HTML 页面。这就是 <!DOCTYPE> 的用处。
<!DOCTYPE> 不是 HTML 标签。它为浏览器提供一项信息（声明），即 HTML 是用什么版本编写的。

浏览器内核:(主流)
Trident(又称为MSHTML): IE
Gecko: Mozilla Firefox
WEbkit内核: Safari Chrome

Quirks mode:
quirks mode和strict mode是浏览器解析css的两种模式
浏览器如何判断何用哪种方式解析CSS？
解决方案就是采用doctype声明，大多数浏览器采用下面的这些判断规则
•	    浏览器要使老旧的网页正常工作，但这部分网页是没有doctype声明的，所以浏览器对没有doctype声明的网页采用quirks mode解析。
•	    对于拥有doctype声明的网页，什么浏览器采用何种模式解析，这里有一张详细列表可参考：http://hsivonen.iki.fi/doctype/
•	    对于拥有doctype声明的网页，这里有几条简单的规则可用于判断：
对于那些浏览器不能识别的doctype声明，浏览器采用strict mode解析
 
在doctype声明中，没有使用DTD声明或者使用HTML4以下（不包括HTML4）的DTD声明时，基本所有的浏览器都是使用quirks mode呈现，其他的则使用strict mode解析。
可以这么说，在现有有doctype声明的网页，绝大多数是采用strict mode进行解析的。
在ie6中，如果在doctype声明前有一个xml声明(比如:<?xml version="1.0" encoding="iso-8859-1"?>)，则采用quirks mode解析。这条规则在ie7中已经移除了。

HTML 元素和属性
HTML 元素语法
•	HTML 元素以开始标签起始
•	HTML 元素以结束标签终止
•	元素的内容是开始标签与结束标签之间的内容
•	某些 HTML 元素具有空内容（empty content）
•	空元素在开始标签中进行关闭（以开始标签的结束而结束）
•	大多数 HTML 元素可拥有属性
Html 属性：（主要）
id class style title
HTMl 元素 : h1-h6 p hr a img table(tr td) ul(li) ol(li) dl(dt dd) div span input
Block elements: p h1-h6 ul ol dl pre hr blockquote address div 
Inline elements: <b>, <i>, <u>, <em>, <strong>, <sup>, <sub>, <big>, <small>, <li>, <ins>, <del>, <code>, <cite>, <dfn>, <kbd>, and <var> span 
Div 
Span
Html 注释<!--注释内容-->
Html 表单 form : Input ,Select, Textarea, Button.
Input type: text , radio, checkbox, submit button.
Html 5 新特性：
语义化：新增语义元素：header section footer aside nav main article figure figcaption mark summary details time
新增 表单元素:datalist, keygen, output
新增 input type: color date datetime datetime-local email month number range search tel time url week

HTML canvas(使用js)
HTMl 音频 视频
HTML API
Geolocation Drag/Drop LocalStorage/sessionStorage webworkers

