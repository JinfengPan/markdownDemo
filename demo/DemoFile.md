一级标题
===
二级标题
---


#一级标题
##二级标题
###三级标题
####四级标题


可以直接写HTML标签：
<button>按钮</button>

水平线：

---
***
___

空行可以形成段落，段落内换行需要使用两个或更多空格加上回车或换行符  
空行可以形成段落
空行可以形成段落
空行可以形成段落

空行可以形成段落
空行可以形成段落
空行可以形成段落
空行可以形成段落




*斜体*
_斜体_

**粗体**
__粗体__


有序列表：

1. 权利的游戏
2. 豪斯医生
3. 无耻之徒

转义：

1\. 权利的游戏
2\. 豪斯医生
3\. 无耻之徒

无序列表：

- 愤怒的小鸟
- 疯狂麦克斯

* 愤怒的小鸟
* 疯狂麦克斯

+ 愤怒的小鸟
+ 疯狂麦克斯


block quote

>现在想想，如果说我还有哪一点像个儿童，那就是兜里依然没有零花钱。
>>--沃兹基硕德

图片和链接都有两种写法：inline 或者 reference

inline:

[markdown Demo on GitHub](https://github.com/patrickfly/markdownDemo "Title: This is a demo")

![Jennifer](http://ask.rednet.cn/uploads/answer/20130621/b21973973c6baa27659855804bc56dbe.jpg "Jennifer the girl")

by reference:

[markdown Demo on GitHub][Link1]
![Jennifer][Image1]

a Tag

Image source: <http://ask.rednet.cn/uploads/answer/20130621/b21973973c6baa27659855804bc56dbe.jpg>




[Link1]: https://github.com/patrickfly/markdownDemo "Title: This is a demo"
[Image1]: http://ask.rednet.cn/uploads/answer/20130621/b21973973c6baa27659855804bc56dbe.jpg "Jennifer the girl"


Table

Desserts | Calories
---------|-----------
Brownie  | 230
Cookie   | 210
PB Cup   | 700

Fenced Code

```
var count = 5;
var price = 10;
var totl = count * price;
```