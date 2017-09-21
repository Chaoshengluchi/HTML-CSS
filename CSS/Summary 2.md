## 进阶课程

### padding属性：  
跟margin相反，设置内边距,如下代码设置与表格外边框的距离都是30px  
```
<table border="1" style="border-color:blue;">
        <tr>
            <td style="padding:30px;">我的梦想</td>
            <td style="padding:30px;">环游世界</td>
        </tr>
        <tr>
            <td style="padding:30px;">我的爱好</td>
            <td style="padding:30px;">吃喝玩乐</td>
        </tr>
</table>
```
*需要用到居中效果就可以按照上述代码写  

如果不需要每个内边距都相同，可以这么写：  
```
<td style="padding:10px 20px 10px 20 px;">
```
它代表的是上右下左即顺时针的四个方向的内边距  

如果不需要设置四个边的内边距，可以写成padding—top,pading-right,padding-bottom,padding-left：  
```
<td style="padding-left:10px;">
```
上述代码即表示设置左内边距为10px。  

### font-family属性  
设置字体。如：  
```
<p style="font-family:Times New Roman;">I have a dream</p>
<p>You said nothing</p>
```

### text-align属性  
规定元素中的文本的水平对齐方式  
```
<p style="text-align:left;">少年去游荡</p>
<p style="text-align:right;">中年去掘藏</p>
<p style="text-align:center;">老年做和尚</p>
```
### float属性  
```
<p style="float:left;margin-left:30px">首页</p>
<p style="float:left;margin-left:30px">秘密天地</p>
<p style="float:left;margin-left:30px">健脑操</p>
<p style="float:left;margin-left:30px">八卦集</p>
<p style="float:left;">图说天下</p>
```
### position属性  
规定元素的定位类型  
```
<img src="http://i03.pic.sogou.com/7e35a5be5ef96ed5" style="position:absolute;top:100px;left:200px;">
```
position: absolute 是给图片设置为绝对定位。top／right／bottom／left可以设置图片放在任何你想要放的位置
