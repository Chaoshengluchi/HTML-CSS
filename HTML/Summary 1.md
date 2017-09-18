## 初识HTML  
1.什么是HTML？HTML是文本文档
> HTML是一种超文本标记语言  

HTML是由各种基本的元素组成的。什么是元素（element）？
> 指示浏览器中该内容的作用。

2.标签  
定义段落：  
```
<p>这是一个段落</p>
```  

**HTML中的元素要遵循“三明治语法**，p就是上面的面包，/p就是下面的面包，夹在中间的就是你要写的内容。  

定义标题：  
```
<h1>这是一个主标题</h1>
```  
h1到h6字体是依次减小,h1最大，h6最小

定义水平线：  
```
<hr/>
```  
元素里面的单身狗，区别三明治语法  

斜体：  
```
<i>我是斜体</i>
```  

粗体：  
```
<b>我是粗体</b>
``` 

换行：  
```
<br>  
```

下划线：
```
<u>我有下划线</u>
```  

插入图片：  
```
<img src="https://static1.bcjiaoyu.com/cxy/html/8-4.jpg-238x216">
```  
<img>标签的src属性是必需的。它的值是图像文件的URL，也就是引用该图像的文件的的绝对路径或相对路径。  

无序列表：
```
<ul> 
    <li>我是无序列表第1行</li>
    <li>我是无序列表第2行</li>
</ul>
```

有序列表:
```
<ol>
    <li>我是有序列表第1行</li>``  
    <li>我是有序列表第2行</li>``  
</ol>
```

表格:
``` 
<table border= "1">
    <tr>
        <td>这是第一行第一列</td>
        <td>这是第一行第二列</td>
    </tr>
    <tr>
        <td>这是第二行第一列</td>
        <td>这是第二行第二列</td>
    </tr>
</table>
```  
table意味着这是一个表格，tr定义行，td定义列  

插入视频：  
```
<video width="200" height="200" scr="http://resource.haorenao.cn/cxy720-2.mp4" controls></video>
```   
controls属性设置视频底部的控制条

超链接：  
```
<a href= "https://github.com/Chaoshengluchi/HTML-CSS.git">@朝圣路痴</a>
```   
href属性指示链接目标  

3.HTML网页代码结构：

 ```
 <!DOCTYPE html>
 <html>
    <head>
        <meta charset="UTF-8">
        <title>如沐春风</title>
    </head>
    <boby>
        <h1>我的个人网页</h1>
        <hr/>
        <h2>我的个人网页</h2>
        <h3>我的个人网页</h3>
        <hr/>
        <p><i>我有点不淡定了</i></p>
        <p>我是这世界上<i>最美丽</i>的小姑娘</p>
        <p><b>我是粗的</b></p>
        <hr/>
        <img src="https://static1.bcjiaoyu.com/cxy/html/8-4.jpg-238x216">
        <table border ="1">
            <tr>
                <td>这是第一行第一列</td>
                <td>这是第一行第二列</td>
        </tr>
            <tr>
                <td>这是第二行第一列</td>
                <td>这是第二行第二列</td>
        </tr>
        </table>
        <video width="200" height="200" scr="http://resource.haorenao.cn/cxy720-2.mp4" controls></video>

        <a href= "http://weibo.com/haorenao">@朝圣路痴</a>
    </boby>
</html>
```
