# ife_dilidili
**ife百度前端技术学院**  
前端深入学习，就此开始。  
HTML/CSS任务目标：  
>[任务3](http://monkey65535.github.io/ife_dilidili/task3/task3.html)  
>任务7  
>[任务8](http://monkey65535.github.io/ife_dilidili/task8/task8.html)  
>任务9  
> [任务10](http://monkey65535.github.io/ife_dilidili/task10/task10.html)  

JavaScript学习任务：
>[任务13](http://monkey65535.github.io/ife_dilidili/task13/task13.html)  
>[任务14](http://monkey65535.github.io/ife_dilidili/task14/task14.html)

移动端任务目标：  
>任务11  

任务笔记：  

任务3  
圣杯布局/双飞翼布局：使用了position方法和float方法各完成了一次。  
float方法要求left左浮动，right右浮动，center不进行浮动，使用margin留出左右两侧位置，同时center容器要在left和right容器后面。  
position方法需要使用position:absolute进行定位。  
圣杯布局主要考察了对文档流的掌握。 
>参考资料  
[MDN：position](https://developer.mozilla.org/zh-CN/docs/Web/CSS/position)
[MDN：float](https://developer.mozilla.org/en-US/docs/Web/CSS/float)
[清除浮动（clearfix hack）](http://zh.learnlayout.com/clearfix.html)


任务8 实现一个栅格化系统  

box-sizing属性很重要，目前正在思考如何在col内不放置元素的情况下实现效果。  

>参考资料：[bootstrap中文网:栅格系统](http://v3.bootcss.com/css/#grid)  

任务10 实现flex弹性布局  

>参考资料：  
[Flexbox简介](https://segmentfault.com/a/1190000002910324#articleHeader5)  
[Flexbox——快速布局神器](http://www.w3cplus.com/css3/flexbox-basics.html)

任务13  零基础JavaScript编码（一）  
参考资料：  
>[JavaScript入门篇](http://www.imooc.com/view/36)  
>[MDN JavaScript](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript)   

笔记：最开始只用了最基础的方式，后来review了其他人的代码之后，发现要考虑到交互因素，故做了一次判断。后来听从朋友建议，使用了DOM事件：`addEventListener`进行了优化。  
addEventListener用这个监听click事件，可以监听多次，而直接写click事件，多次进行会覆盖上次的内容。

任务14 零基础JavaScript编码（二）  
参考资料：  
>[JavaScript入门篇](http://www.imooc.com/view/36)
>[MDN JavaScript](https://developer.mozilla.org/zh-CN/docs/Learn/Getting_started_with_the_web/JavaScript_basics)  

笔记：  
javaScript排序函数：`sort()`;  
>语法：arrayObject.sort(sortby)  

参数：`sortby` 可选，规定排序顺序，必须是函数。  
返回值：  对数组的引用。请注意，数组在原数组上进行排序，不生成副本。  
说明：  如果调用该方法时没有使用参数，将按字母顺序对数组中的元素进行排序，说得更精确点，是按照字符编码的顺序进行排序。要实现这一点，首先应把数组的元素都转换成字符串（如有必要），以便进行比较。  

如果想按照其他标准进行排序，就需要提供比较函数，该函数要比较两个值，然后返回一个用于说明这两个值的相对顺序的数字。比较函数应该具有两个参数 a 和 b，其返回值如下：  

 - 若 a 小于 b，在排序后的数组中 a 应该出现在 b 之前，则返回一个小于 0 的值。  
 - 若 a 等于 b，则返回 0。  
 - 若 a 大于 b，则返回一个大于 0 的值。  


 >引用：[JavaScript sort() 方法](http://www.w3school.com.cn/jsref/jsref_sort.asp)

