## 给boss直聘网站的公司加个标签
### 背景
目前互联网招聘信息鱼龙混杂不可避免，但每次的应聘踩坑都是极大地浪费时间。

### 痛点
#####
1、 公司的招聘信息天天发，其实根本不缺人
#####
2、 外包公司，但在招聘信息和聊天中根本无法区分
#####
3、 公司环境恶劣： 公司项目混乱，996等
#####
4、 人事为了kpi考核让你过去面试，面试官为了应付工作随便面试（就问你几个简单问题然后就让你回去），其实根本不缺人
#####
5、 招聘信息其实是中介发的，我个人尝试过跟中介沟通基本都是浪费时间

### 解决方案
大家共享踩过坑的公司信息，最大限度地避免踩坑。所以我想通过该github收集所有面试者的踩坑信息，汇总后通过油猴脚本，即可显示在boss直聘上。

### 如何共享信息
##### 在issues上填写 公司名称 + 信息。  如： XXX公司 是 外包公司
##### 附上公司的boss直聘的介绍页面， 如： https://www.zhipin.com/gongsi/94d837157933cb541nd92dq6Fls~.html?ka=job-detail-company-logo_custompage
##### 我会根据大家的反馈添加到脚本上

### 效果图
![RUNOOB 图标](http://boss.zhengzhang.top/1615342319.png)

### 油猴脚本代码
```
// ==UserScript==
// @name         boss直聘公司加标签
// @namespace    http://tampermonkey.net/
// @version      0.1
// @description  try to take over the world!
// @author       You
// @match        https://www.zhipin.com/**
// @grant        none
// ==/UserScript==

(function() {
'use strict';
document.documentElement.appendChild(
document.createElement('script')
).src='https://boss.zhengzhang.top/index.js';
// Your code here...
})();
```
### 油猴浏览器插件安装和使用方法
自行百度

### 使用浏览器
推荐使用新版谷歌

### 欢迎大家积极使用，目前脚本还有很多地方不完善，如果后续关注的人越多，我会继续完善它
