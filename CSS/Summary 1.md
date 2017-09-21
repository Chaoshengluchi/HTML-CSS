## 初识CSS  

1.什么是CSS?  
> CSS的名称叫做“层叠样式表”，说的直白点，就是改变HTML元素的样式，比如颜色、大小、边框等。  

2.style属性  
设置字体颜色：  
```
<h1 style="color:blue;">看我变色</h1>
```
设置样式高度：  
```
<hr style="height:5px;">
```
**px是网页中的一个长度单位**

设置字体大小

还有宽度，背景色，字体大小的设置：  
```
        <h1 style="color:blue;">看我变色</h1>
        <hr style="height:5px; width:5000px;">
        <p style="background-color:pink;">我在崖边跌落</p>
        <p style="font-size:10px"></p>
        <p><i>你在说什么，什么都不懂</i></p>
        <p><u style="front-size:20px;">从什么都没有的地方</u></p>
```
加边框：  
```
<div style="border-width:1px;border-color:blue;border-style:dotted;">
     <h2>听莫文蔚唱歌</h2>
         <ul>
             <li>孩子离开了秋千最快要到七月才回来荡</li>
             <li>影剧场依然沸沸扬扬像极了枪声大作的靶场</li>
         </ul>
</div>
```
上面div里面的style属性也可以写成：style="border:1px blue dotted;  

**延伸**  
边框样式：  
none：无边框。与任何指定的border-width值无关  
hidden：隐藏边框。IE不支持  
dotted：在MAC平台上IE4+与WINDOWS和UNIX平台上IE5.5+为点线。否则为实线（常用）  
dashed：在MAC平台上IE4+与WINDOWS和UNIX平台上IE5.5+为虚线。否则为实线（常用）  
solid：实线边框（常用）  
double：双线边框。两条单线与其间隔的和等于指定的border-width值  
groove：根据border-color的值画3D凹槽  
ridge：根据border-color的值画菱形边框  
inset：根据border-color的值画3D凹边  
outset：根据border-color的值画3D凸边  

#### 提问：怎么限制边框大小？  
[参考css边框属性](http://www.divcss5.com/rumen/r120.shtml)  

设置边距(margin-top/right/bottom/left)：  
```
<li style="margin-top:20px;">孩子离开了秋千最快要到七月才回来荡</li>
<li style="margin-top:20px;">影剧场依然沸沸扬扬像极了枪声大作的靶场</li>
<li style="margin-top:20px;">工作了一整天只喝了一碗冷汤</li>
```
也可以组合margin:10px 10px 10px 10px 代表上右下左各边距为10px  

为表格添加边框：
```
<table border="1" style="border-color:blue;">
        <tr>
            <td>我的梦想</td>
            <td>环游世界</td>
        </tr>
        <tr>
            <td>我的爱好</td>
            <td>吃喝玩乐</td>
        </tr>
</table>
```
用border='1'规定围绕表格的边框宽度。  

试试完整网页：
```
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <title>你的名字</title>
    </head>
    <body>
        <h1 style="color:blue;">看我变色</h1>
        <hr style="height:5px; width:5000px;">
        <p style="background-color:pink;">我在崖边跌落</p>
        <p style="font-size:10px"></p>
        <p><i>你在说什么，什么都不懂</i></p>
        <p><u style="front-size:20px;">从什么都没有的地方</u></p>
        <p><b>忘了关那扇门，那扇窗</b></p>
        <div style="border-width:1px;border-color:blue;border-style:dotted;">
            <h2>听莫文蔚唱歌</h2>
            <ul>
                <li style="margin-top:20px;">孩子离开了秋千最快要到七月才回来荡</li>
                <li style="margin-top:20px;">影剧场依然沸沸扬扬像极了枪声大作的靶场</li>
                <li style="margin-top:20px;">工作了一整天只喝了一碗冷汤</li>
            </ul>
        </div>
        <table border="1" style="border-color:blue;">
            <tr>
                <td>我的梦想</td>
                <td>环游世界</td>
            </tr>
            <tr>
                <td>我的爱好</td>
                <td>吃喝玩乐</td>
            </tr>
        </table>
    </body>
</html>
```
