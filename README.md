# html-cheatsheet
```html

1.标题(header)：
<h1>一级标题</h1>
<h2>二级标题</h2>
....
<h6>六级标题</h6>
<h1></h1>最小   <h6>最大</h6>

2.段落：<p>段落内容</p>  

3.链接：<a href="网址">显示文字</a>

4.图像：<img src="绝对url/相对url" />
eg：
绝对url:  src=""http:www.example.com
相对url:  src="/i/image.gif"

5.列表
列表分为无序列表（unorder list）和有序列表(order list)
eg:
无序列表：                  
<ul>                                
<li>Coffee</li>
<li>Milk</li>
</ul>

有序列表：
<ol>
<li>Coffee</li>
<li>Milk</li>
</ol>


6.html注释
注释标签 <!-- 在此处写注释 -->用于在 HTML 插入注释。
在sublime text3中，想要添加注释，选中想要添加注释的内容，按快捷键：Ctrl+？

7.表格（table）
表格由<table>标签来定义，每个表格均有若干行（由<tr>来定义），每行被分为若干单元格（由<td>标签来定义.字母td指表格数据(table data)
数据单元格可以包含文本、图片、列表、段落、表单、水平线、表格等等。
Eg:
<table border="1">
<tr>
<th>Heading</th>
<th>Another Heading</th>
</tr>
<tr>
<td>row 1, cell 1</td>
<td>row 1, cell 2</td>
</tr>
<tr>
<td>row 2, cell 1</td>
<td>row 2, cell 2</td>
</tr>
</table>
 
```

## 表单
```html
1.表单
<form>元素定义html表单,<input>元素是最重要的表单元素。<input> 元素有很多形态，根据不同的 type 属性。
 比如：text,radio,submit
  Eg:
 (1)文本输入：text
 
  <form>
  First name:<br>
  <input type="text" name="firstname">
  </form>
 
 (2)radio单选按钮输入  比 text多了value属性
 
<form>
<input type="radio" name="sex" value="male" checked>Male
<br>
<input type="radio" name="sex" value="female">Female
</form> 
 
 （3）submit
<input type="submit"> 定义用于向表单处理程序（form-handler）提交表单的按钮。
表单处理程序通常是包含用来处理输入数据的脚本的服务器页面。
表单处理程序在表单的 action 属性中指定：
 <from>中的内容由<input type="submit">提交到action="action_page.php"
 
<form action="action_page.php">
First name:<br>
<input type="text" name="firstname" value="Mickey">
<br>
Last name:<br>
<input type="text" name="lastname" value="Mouse">
<br><br>
<input type="submit" value="Submit">
</form> 
  ```

