1. lang=en对于网页翻译或屏幕阅读浏览器有指导意义.

```html
<html lang="en">
```

lang 属性规定元素内容的语言。（即language的简写）

en：显示为英语\(有的浏览器会提示你是否需要翻译\)  
zh\_CN：显示为中文

UTF-8：是字符集。

字符集\(Character set\)是多个字符的集合，字符集种类较多，每个字符集包含的字符个数不同，常见字符集名称：ASCII字符集、GB2312字符集、BIG5字符集、 GB18030字符集、Unicode字符集等。

2.锚点

```html
在HTML页面中适当位置定义如下的锚点：
<a id="top">这里是TOP部分</a>
<a id="content">这里是CONTENT部分</a>
<a id="foot">这里是FOOT部分</a>
（您可以使用 id 属性来替代 name 属性，命名锚同样有效。[1]  ）
对于如上锚点的访问有两种方法
一种是利用超链接标签<a></a>制作锚点链接，主要用于页面内的锚点访问
<a href="#top">点击我链接到TOP</a>
<a href="#content">点击我链接到CONTENT</a>
<a href="#foot">点击我链接到FOOT</a>
另一种方式是直接在页面地址后面加锚点标记，主要用于不同页面之间的锚点访问
假如本页面的地址是http://文件路径/index.html，要访问foot锚点只要访问如下链接即可
http://文件路径/index.html#foot
```



