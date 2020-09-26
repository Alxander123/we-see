## 基础标签

### 基础：

一、

```html
<!--添加注释文字-->
```

   添加注释文字。

二、`base`   必须位`head`标签内部，并尽量靠前。

​	1.`href`  指定该 HTML 文档中所有相对链接的基准 URL。

​	2.`target`   指定在何处打开超链接。

​		`_blank`：在新窗口中打开。

三、`br` 标签用于插入一个简单的换行符。

四、`dir`属性规定元素内容的文本方向。

​	1. `auto` 让浏览器根据内容来判断文本方向。

​	2. `ltr`从左往右的文本方向。/默认

​	3. `rtl`从右往左的文本方向。

五、`hr` 创建一条水平分隔线。

六、`meta`内容不会显示在网页中，但会被机器解析。

​	1.网页尺寸实现自适应。

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

​	2.`http-equiv refresh`以秒为单位，在此时间过去后重新载入当前页面，也可以另行指定一个 URL 。

​	3.`name`

`keywords`当前页的关键词。

`description`当前页的内容描述。

`author`当前页的作者名。

`viewport`网页尺寸自适应。

*例*

```html
<meta charset="UTF-8">
<meta name="keywords" content="HTML5,CSS3,Web编程教学">
<meta name="description" content="案例演示">
<meta name="author" content="小甲鱼">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta http-equiv="refresh" content="5;http://bbs.fishc.com">
```

七、`img`向网页中嵌入一幅图像。

​	1.`alt = "text"`指定图像的替代文本。

​	2.`src = "URL"`指定显示图像的 URL。

​	3.`width = "px %" height = "px %"`设置图像的宽度,图像的高度。

八、`a`定义超链接。

​	1.`download` 指定被下载的超链接目标。

​	2.`herf`指定链接指向页面的 URL。

​	3.`target`

​							`_blank`在新窗口中打开;

​							`_self` 当前窗口打开(默认).

