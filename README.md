# loveWebTemplates
搜集了一个哄女朋友开心的网站模板

----------------------------------2023.5.29 500天礼物。

放在TimelineRecords下的index_love.html中--时间线记录。

需要更改的点

1. 网页title
2. 在一起的时间
3. 双方头像
4. 爱情历程体

具体修改代码

```html
<title>title</title>

<span class="wow fadeInUp animated col-xs-12 text-center" data-wow-delay="0.7s" style="color: rgb(239, 106, 138);
         visibility: visible; animation-delay: 0.7s; animation-name: fadeInUp;margin: 15px auto;font-size: 16px">
♥ 时间 ♥</span>

<div class="col-xs-12">
<div class="col-xs-6 text-right" data-anijs="if: click, do: rollOut animated, to: .boy, after: $removeAnim">
<ul class="ch-grid man wow flipInX animated" data-wow-delay="0.5s" style="visibility: visible; animation-delay: 0.5s; animation-name: flipInX;">
<li class="boy">
<img src="images/mmexport1685358347709.png" alt="">
</li>
</ul>
</div>
<div class="and">&</div>
<div class="col-xs-6 text-left" data-anijs="if: click, do: rollIn animated, to: .girl, after: $removeAnim">
<ul class="ch-grid woman wow flipInX animated" data-wow-delay="0.5s" style="visibility: visible; animation-delay: 0.5s; animation-name: flipInX;">
<li class="girl">
<img src="images/QQ图片20230529190807.jpg" alt="">
</li>
</ul>
</div>
</div>

<li class="col-xs-12" data-anijs="if: scroll, on: window, do: slideInLeft   animated, before: $scrollReveal repeat">
<div class="timeline-badge wow fadeInUp animated" data-wow-delay="0.5s" style="visibility: visible; animation-delay: 0.5s; animation-name: fadeInUp;">
<i> ♥ </i>
</div>
<div class="timeline-panel wow fadeInLeft animated" data-wow-delay="0.7s" style="visibility: visible; animation-delay: 0.7s; animation-name: fadeInLeft;">
<div class="" style="padding: 0;width: 102px;position: relative;float: left">
<img src="images/x1.png" alt="" style="width: 102px;height: 102px">
</div>
<div class="" style="padding: 0 15px 0 135px">
<div class="timeline-heading">
<p><br></p>
</div>
<div class="timeline-body">
<div>
<div>
<p class="txtcolor"></p>
</div>
</div>
</div>
<div class="timeline-foot"></div>
</div>
</div>
</li>
```

最终效果如下

![image-20241104162940858](https://raw.githubusercontent.com/Fxk2020/Kmeans/master/img/image-20241104162940858.png)
