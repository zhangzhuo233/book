1. # 标题

   1. &lt;h1&gt;&lt;/h1&gt;

   2. 只有6级,只到&lt;h6&gt;

   ```html
   <h1>welcome this webpage</h1>
   <h6>zhangzhuo is a monky</h6>
   ```

   ![](/assets/6级标题2.PNG)

2. # 段落

   1. &lt;p&gt;&lt;/p&gt;

   ```html
   <p>山不在高，有仙则名。水不在深，有龙则灵。斯是陋室，惟吾德馨。苔痕上阶绿，草色入帘青。谈笑有鸿儒，往来无白丁。可以调素琴，阅金经。无丝竹之乱耳，无案牍之劳形。南阳诸葛庐，西蜀子云亭。孔子云：何陋之有？</p>
   ```
3. # font标签\(不用\)

   1. &lt;font&gt;&lt;/font&gt;

   2. 格式化文本

   ```html
       <!-- size -->
       <font>慕课html</font>
       <!-- face -->
       <font face="Helvetica">html 入门</font>
       <!-- color -->
       <font color="red">多姿多彩的html</font>
       <font color="#d8d8d8">多姿多彩的html</font>
       <font color="rgb(168,178,188)">多姿多彩的html</font>
   ```
4. # 链接

   1. &lt;a&gt;&lt;/a&gt;

   2. 锚点跳转、下载资源

   ```html
   <a id="top">这里是TOP部分</a>
   <a id="content">这里是CONTENT部分</a>
   <a id="foot">这里是FOOT部分</a>

   /*(您可以使用 id 属性来替代 name 属性，命名锚同样有效。[1]  ）
   对于如上锚点的访问有两种方法
   一种是利用超链接标签<a></a>制作锚点链接，主要用于页面内的锚点访问*/

   <a href="#top">点击我链接到TOP</a>
   <a href="#content">点击我链接到CONTENT</a>
   <a href="#foot">点击我链接到FOOT</a>
   /*另一种方式是直接在页面地址后面加锚点标记，主要用于不同页面之间的锚点访问
   假如本页面的地址是http://文件路径/index.html，要访问foot锚点只要访问如下链接即可*/
   http://文件路径/index.html#foot
   ```
5. # 图像

   1. &lt;img/&gt;

   2. ```html
      <style>
      .some-logo {
                  background: url(./img/ooopic_1483355652.ico);
                  width: 256px;
                  height: 256px;
              }
      </style>
      <img src="./img/test.ico" alt="somelogo">
      /*非标签方式*/
      <p class="some-logo"></p>
      ```
6. # 列表

   1. 有序列表

   2. ```html
      <ol>学习过的语言(ol)
              <li>c</li>
              <li>c++</li>
              <li>html</li>
              <li>shell</li>
      </ol>
      ```
   3. 无序列表

      1. ```html
         <ul type="circle">学习过的语言(ul)
                 <li>c</li>
                 <li>c++</li>
                 <li>html</li>
                 <li>shell</li>
         </ul>
         ```

   4. 定义列表

   ```html
   <dl>学习过的语言
           <dt>c</dt>
           <dd>object-oriented programming</dd>
           <dt>c++</dt>
           <dd>Object Oriented Programming</dd>
   </dl>
   ```
7. # div

   1. 无语义万能标签

   2. 布局的块级标签



