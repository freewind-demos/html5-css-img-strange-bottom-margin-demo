HTML5 Css "img" Strange Bottom Margin Demo
===========================================

在HTML5中（顶部添加了`<!DOCTYPE HTML>`）之后，img在底部总是有3px的奇怪margin.

大概原因是在html5中，`img`被看作一个字符，它有一个`vertical-align: baseline`的属性，
导致下面会多出一些空白（就像是`y/g`这样的字符下面的尾巴）。

可以使用下面各种方法解决：

- vertical-align: baseline
- display: block
- line-height: 0
- font-size: 0

Use css in html pages.

Open `index.html` in your browser.
