---
title: IE浏览器登录OA系统未授权
date: 2018-01-29 14:00:51
categories: 办公
tags:
---

## 现象 ##
OA系统只能用IE浏览器正常使用，输入oa.yolo24.com，提示401未授权，无有效凭证
![此处输入图片的描述][1]
<!--more-->
## 原因 ##
蓝灯启动后，自动打开系统代理端口（每个用户端口不同），127.0.0.1:50305 影响OA系统使用。
## 解决方案 ##
退出蓝灯，或者进入“更改系统代理设置”，手动关闭代理端口
![此处输入图片的描述][2]
 


  [1]: http://p3b1ja19n.bkt.clouddn.com/image/png/oa/oa%E6%9C%AA%E6%8E%88%E6%9D%83.png
  [2]: http://p3b1ja19n.bkt.clouddn.com/image/png/oa/%E8%93%9D%E7%81%AF%E8%87%AA%E5%8A%A8%E4%BB%A3%E7%90%86%E7%AB%AF%E5%8F%A3%E5%85%B3%E9%97%AD.png