```html
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>语义化标签</title>
	<!-- 为webpage添加icon -->
	<link rel="webicon" type="ico" href="img/ooopic_1483355563.ico">
	<!-- 取消段落不必要的间隔 -->
	<style>
		p {
			margin: 0;
			padding: 0;
		}
		h1 {
			margin: 0;
			padding: 0;
		}
		/*h6 {
			margin: 0;
			padding: 0;
		}*/
		.some-logo {
			background: url(./img/ooopic_1483355652.ico);
			width: 256px;
			height: 256px;
		}
	</style>

</head>
<body>
	<a id="anchor">这里是anchor部分</a>
	<!-- 标题 -->
	<h1>welcome this webpage</h1>
	<h6>zhangzhuo is a monky</h6>
	<!-- 段落 -->
	<p>山不在高，有仙则名。水不在深，有龙则灵。斯是陋室，惟吾德馨。苔痕上阶绿，草色入帘青。谈笑有鸿儒，往来无白丁。可以调素琴，阅金经。无丝竹之乱耳，无案牍之劳形。南阳诸葛庐，西蜀子云亭。孔子云：何陋之有？</p>
	<font face="Helvetica" color="red">文章结束</font>
	<br>
	<!-- 链接 -->
	<a href="https://www.imooc.com/" target="_blank">这是monky学习的教程</a>
	<br>
	<a href="https://www.imooc.com/" target="_self">这是monky学习的教程</a>
	<br>
	<!-- 死链 -->
	<a href="javascript:;">点不动的哦</a>
	<br>
	<!-- 锚点 -->
	<a href="#anchor">点我链接到anchor</a>
	<br>
	<!-- 图像 -->
	<img src="./img/test.ico" alt="somelogo">
	<p class="some-logo"></p>
	<!-- 有序列表 -->
	<ol>学习过的语言(ol)
		<li>c</li>
		<li>c++</li>
		<li>html</li>
		<li>shell</li>
	</ol>
	<!-- 无序列表 -->
	<!-- type="square"实心方/"disc"实心圆/"circle"空心圆 -->
	<ul type="circle">学习过的语言(ul)
		<li>c</li>
		<li>c++</li>
		<li>html</li>
		<li>shell</li>
	</ul>
	<!-- 定义列表 -->
	<dl>学习过的语言
		<dt>c</dt>
		<dd>object-oriented programming</dd>
		<dt>c++</dt>
		<dd>Object Oriented Programming</dd>
	</dl>

</body>
</html>
```



