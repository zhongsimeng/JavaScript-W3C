# JavaScript-W3C

##JavaScript 简介
javaScript 是世界上最流行的编程语言。
  
这门语言可用于HTML和web，更可广泛用于服务器、PC、笔记本电脑、平板电脑和智能手机登设备。
  
###JavaScript 是脚本语言
JavaScript是一种轻量级的编程语言。
  
JavaScript是可插入HTML页面的编程代码。
  
JavaScript插入HTML页面后，可由所有的现代浏览器执行。
  
JavaScript很容易学习。
  
###JavaScript：写入HTML输出
实例：
  
    document.write("<h1>This is a heading</h1>");
    document.write("<p>This is a paragraph</p>");
  
>提示：你智能在HTML输出中使用`document.write`。如果你在文档加载后使用该方法，会覆盖整个文档。
  
###JavaScript：对事件作出反应
实例：

    <button type="button" onclick="alert('Welcome!')">点击这里</button>
    
>alert()函数在JavaScript中并不常用，但它对于代码测试非常方便。
>onclick事件，JavaScript众多事件之一。

###JavaScript：改变HTML内容
使用JavaScript来处理HTML内容是非常强大的功能。

实例：

    x=document.getELementById("demo")//查找元素
    x.innerHTML="Hello JavaScript";//改变内容
    
>你会经常看到`document.getElementById("some id")`.这个方法是HTML DOM中定义的。
>DOM（文档对象模型）是用以访问HTML元素的正式W3C标准。

###JavaScript: 改变HTML图像
本例会动态地改变 HTML <image> 的来源 (src)：

The Light bulb

点击灯泡就可以打开或关闭这盏灯

    <!DOCTYPE html>
    <html>
    <body>
    <script>
    function changeImage()
    {
    element=document.getElementById('myimage')
    if (element.src.match("bulbon"))
      {
      element.src="/i/eg_bulboff.gif";
      }
    else
      {
      element.src="/i/eg_bulbon.gif";
      }
    }
    </script>

    <img id="myimage" onclick="changeImage()" src="/i/eg_bulboff.gif">

    <p>点击灯泡来点亮或熄灭这盏灯</p>

    </body>
    </html>
    
>JavaScript 能够改变任意 HTML 元素的大多数属性，而不仅仅是图片。

###JavaScript: 改变HTML样式
改变HTML元素的样式，属于改变HTML属性的变种。

实例：

    x=document.getElementById("demo")//找到元素
    x.style.color="#fff";//改变样式
    
###JavaScript：验证输入
JavaScript常用于验证用户的输入。

实例：

    if isNaN(x){alert("Not Numeric")};
    
    
###你知道吗？
提示：JavaScript 与 Java 是两种完全不同的语言，无论在概念还是设计上。

Java（由 Sun 发明）是更复杂的编程语言。

ECMA-262 是 JavaScript 标准的官方名称。

JavaScript 由 Brendan Eich 发明。它于 1995 年出现在 Netscape 中（该浏览器已停止更新），并于 1997 年被 ECMA（一个标准协会）采纳。
