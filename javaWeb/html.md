### 介绍
HTML: 超文本标记语言（Hyper Text Markup Language）, 文件名必须是"htm"或"html"。

### 开发工具
WebStorm, Sublime Text...

### 网页结构
```html
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
</head>
<body text="red">
    Content
</body>
</html>
```
1. `<html>`HTML页面的根元素。
2. `<head>`文档的元（meta）数据，不会显示。
3. `<title>`为`<head>`的子标签。
4. `<body>`页面内容。
5. "text"为`<body>`标签的属性，用于设置文字颜色。
6. 标签要有**开始与结束**，例`<body>...</body>`。
7. HTML本身***不区分大小写***。

### 常用标签及属性
```html
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>HTML学习</title>
</head>
<body text="red" bgcolor="#f5f5dc">
<!--我是注释哈-->
第一行
<br/>
第二行
<p align="center">居中段落...</p>

蓝色居左水平线
<hr color="blue"/>

宽度为200尺寸为10的绿色居中水平线
<hr align="center" color="green" width="200" size="10"/>
<div style="width: 200px;height: 200px; border: 1px solid blue;">
    块级别元素
</div>
<span style="border: 1px solid blue;">内联元素</span><span>内联元素2</span>

<font color="black" face="楷书" size="2">字体</font>
</body>
</html>
```
#### 文本标签
* `<html>` HTML页面的根元素<br/>
* `<head>`文档的元（meta）数据，不会显示。子标签如下:
     - `<title>`定义文档标题
* `<body>`页面内容，属性如下：
    - text：文字颜色
    - bgcolor: 页面背景色
    - backgroud：页面的背景图片
    
   
#### 排版标签
##### 1. 注释标签
* `<!--......-->` 注释，页面不显示。
##### 2. 换行标签
* `<br/>`
##### 3. 段落标签
* `<p>` 会在开始与结束之间产生一个空白行，且会自动换行。常用属性：
    * align: 设置段落内容的对齐方式，取值：left｜right｜center
##### 4. 水平线标签
* `<hr/>`常用属性：
    - align：水平线位置，取值：left｜right｜center
    - size：粗细
    - width：宽度
    - color：颜色

##### 5. 区块标签
* `<div>`
    - 块级元素，可用于组合其他 HTML 元素的容器，在浏览器显示时通常会以新行开始（结束）。
    - 与CSS一同使用，可用于对大的内容块设置样式属性。
    - 用于文档布局，取代使用表哥定义格局的老式方法。
* `<span>`
    - 内联元素，可用作文本的容器，在显示时通常不会以新行开始。
    - 与CSS一同使用，可用于为部分文本设置样式属性


##### 6. 字体标签
* `<font>`设置字体，字的大小及颜色，常用属性:
    - face：设置字体，例如 宋体 隶书 楷体
    - size：用于设置字的大小(大小默认设置1-7，7最大，想更大，见css)
    - color：设置字的颜色
        - 使用十六进制方式，取值范围 #000000 ~ #FFFFFF (黑色到白色)，例：`<font color="#666">`。
        - RGB颜色表示法:RGB(x,y,z)。x、y、z是0 ~ 255之间的整数，例：`<font color="rgb(11,11,11)">`。

#### 
    
111. `<h1>` ~ `</h?>``<a>``<font>`
   

