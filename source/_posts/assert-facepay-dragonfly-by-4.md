title: 人脸支付怎么敢采用后4位手机号
tags: [人脸支付,蜻蜓]
date: 2019-04-23 15:17:24
categories: Other
---
我们的人脸支付产品只需要后4位手机号（用户号码）即可辨识用户，这是比支付宝、微信自助机，蜻蜓优秀的地方（需要11位手机号）。但是今天猛然发现唯一的优势不再。


优势是一种市场说法，对于技术人来讲，原理是少量用户比对。因为注册用户少，用户号码能做到1:1，个别需要1:N(N<=4)。所以目前用户体量下无需担心影响用户体验。而支付宝、微信用户体量那么大，采用11位手机号才能1:1。



支付宝、微信到底如何做到只需后4位用户号码，甚至不需要输入手机号的呢？

支付宝用户超10亿   

去除海外用户  

去除尚未开通刷脸支付用户[后期越来越多]    

剩下的数据依然庞大，还能怎么办呢？

<!--more-->

从人脸对比原理上提高几毫秒在这样的用户体量下九牛一毛都不算。所以是否应该从业务场景下寻找解决方案。



以下观点属于猜想

人脸都是跟着人走的，人的使用习惯，活动轨迹都是有规律的。



我们是否还可以从用户使用城市、地区、甚至是否常在哪个店消费来建立优先比对，或者本地比对等。或许还可以根据性别等先过滤一批。



总之从技术上来讲1:N很可怕，但是从业务上拆分后数据量也没有想象中难以承受。



附录符合猜想的蜻蜓支付视频



异地第一次在某店消费
<video id="video" controls="" preload="none" poster="http://om2bks7xs.bkt.clouddn.com/2017-08-26-Markdown-Advance-Video.jpg">
<source id="mp4" src="/css/images/dragonly_newc.mp4" type="video/mp4">
</video>


本地第三次某店蜻蜓支付
<video id="video" controls="" preload="none" poster="http://om2bks7xs.bkt.clouddn.com/2017-08-26-Markdown-Advance-Video.jpg">
<source id="mp4" src="/css/images/dragonly_frequent_visitor.mp4" type="video/mp4">
</video>


旧文  
[刷脸支付-人脸比对效率](/2018/12/06/face-rec-algorithm/)

---  END  ---
分享程序员所看、所想、所悟、所望