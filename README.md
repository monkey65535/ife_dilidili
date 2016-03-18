# ife_dilidili
**ife百度前端技术学院**  
前端深入学习，就此开始。  
HTML/CSS任务目标：   
>任务7  
>[任务8](http://monkey65535.github.io/ife_dilidili/task8/task8.html)  
>任务9  
> [任务10](http://monkey65535.github.io/ife_dilidili/task10/task10.html)  

移动端任务目标：  
>任务11  

任务笔记：  
任务8 实现一个栅格化系统  
>box-sizing属性很重要，目前正在思考如何在col内不放置元素的情况下实现效果。 

>参考资料：[bootstrap中文网:栅格系统](http://v3.bootcss.com/css/#grid)  

任务10 实现flex弹性布局  
笔记：  
flexbox的出现是为了解决复杂的web布局，因为这种布局方式很灵活。容器的子元素可以任意方向进行排列。
属性： 
1.将容器转换为flex布局  

```
display: flex | inline-flex
```
2.创建主轴，同时定义主轴的伸缩方向 
```
flex-direction: row | row-reverse | column | column-reverse
```
![主轴方向](http://img.blog.csdn.net/20150616140933077)  
 
- row:主轴从左到右伸缩  
- row-reverse:与row伸缩方向相反  
- column：主轴从上到下进行伸缩  
- column-reverse：与column伸缩方向相反  

3.order可以改变伸缩项目在他们伸缩容器中出现的顺序。  

```
order: <integer> 
```

![order](http://img.blog.csdn.net/20150616144249372)  

4.flex-wrap用来定义伸缩容器里是单行还是多行显示，侧轴的方向决定了新行堆放的方向。 

```
flex-wrap: nowrap | wrap | wrap-reverse 
```
 
- nowarp  伸缩容器单行显示，“ltr”排版下，伸缩项目从左到右排列；“rtl”排版上伸缩项目从右向左排列。  
- wrap：伸缩容器多行显示，“ltr”排版下，伸缩项目从左到右排列；“rtl”排版上伸缩项目从右向左排列。  
- wrap-reverse：伸缩容器多行显示，“ltr”排版下，伸缩项目从右向左排列；“rtl”排版下，伸缩项目从左到右排列。（和wrap相反）  
![flex-warp](http://img.blog.csdn.net/20150616144822191)  

5.flex-flow：这个是flex-direction和flex-warp的和写，默认属性为row || nowrap  

```
flex-flow: <‘flex-direction’> || <‘flex-wrap’>  
```  

6.justify-content:这个是用来定义伸缩项目沿着主轴线的对齐方式。  

```
justify-content: flex-start | flex-end | center | space-between | space-around;  
```  
当一行上的所有伸缩项目都不能伸缩或可伸缩但是已经达到其最大长度时，这一属性才会对多余的空间进行分配。当项目溢出某一行时，这一属性也会在项目的对齐上施加一些控制。 
- flex-start(默认值)：伸缩项目向一行的起始位置靠齐。
- flex-end：伸缩项目向一行的结束位置靠齐。  
- center：伸缩项目向一行的中间位置靠齐。  
- space-between：伸缩项目会平均地分布在行里。第一个伸缩项目一行中的最开始位置，最后一个伸缩项目在一行中最终点位置。  
- space-around：伸缩项目会平均地分布在行里，两端保留一半的空间。  
![justify-content](http://img.blog.csdn.net/20150616151746589)  





>参考资料：  
[Flexbox简介](https://segmentfault.com/a/1190000002910324#articleHeader5)  
[Flexbox——快速布局神器](http://www.w3cplus.com/css3/flexbox-basics.html)

