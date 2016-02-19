#个人简历
</br>
---


### 联系方式

- 手机：13570489517
- Email：razerdp123@gmail.com或164701463@qq.com
- QQ/微信号：164701463(QQ)/razerdp(WeChat)

---

###个人信息

 - 冯伟超/男/1994-04 
 - 本科/广东工业大学自动化学院物联网工程
 - 工作年限：接近1年
 - 简书：[@羽翼君](http://www.jianshu.com/users/8ff2bb37d791/latest_articles)
 - 技术博客：http://blog.csdn.net/mkfrank
 - GitHub: http://github.com/razerdp

 - 期望职位：Android开发工程师
 - 期望薪资：税前 >6.5K
 - 期望城市：广州

---

### 工作经历


#### 广州多聚信息科技有限公司 （ 2015年8月 ~ 2016年3月 ）

##### 超级俱乐部app 

主要负责UI业务层工作包括：布局和activity层操作，自定义控件的封装。
具体项目业务：
 - v1.8.1 个人资料页开发
 - v1.8.3 问卷调查：通过flowLayout实现标签选择等。
 - v1.8.5 队友圈开发：队友圈整体开发，下拉刷新控件重新封装，针对开发点赞/评论控件，popupWindow等。
 - v1.8.9 相册重构：采取builder模式和接口进行解耦，相片浏览添加评论和点赞，在事件拦截实现单击/双击判定，ExpandableListView实现多选功能。
 - v1.9.0 界面优化：下拉刷新Header的布局层次优化，相册片浏览viewpager添加切换动画，队友圈下拉刷新控件继承PtrFrameLayout库重构，PopupWindow重新封装，实现动画。
 - v2.0 支付操作：UI开发，时间轴LinearLayout实现。
	  
其余版本都有涉及，以重构为主。
在项目中遇到的难点：
 1.  队友圈listview的adapter解耦实现，点赞控件的行数限定以及评论展示控件的事件分发。
 2.  PopupWindow的封装。
 3.  viewpager事件拦截。

解决方案：
 1. adapter重新封装，采取反射方式替换旧有操作（inflate view + viewholder），使不同类型对应到不同的类。点赞行数通过不断的使用staticLayout测量当前文字的行数进而进行对应操作，评论控件事件分发则是取巧，因为ClickableSpan比textview的点击优先，采取设定标志位的方式来使点击span时外部textview的点击无效化。
 2. 抽象出一个顶级父类，使继承该类可以方便的实现出popupWindow
 3. 在onInterceptTouchEvent的onclick事件通过线程（post/remove）方式判断一定时间内是否产生了两次的点击事件。

个人觉得在这半年的实习工作里，最自豪的是注重代码质量，注意类之间的耦合。


---

### 开源项目

 - [BasePopupWindow](https://github.com/razerdp/BasePopup) :抽象出一个顶级父类，使继承该类可以方便的实现出popupWindow，start/fork:90/25
 - [UnderLineLinearLayout](https://github.com/razerdp/UnderLineLinearLayout) :实现时间轴的线性布局，start/fork:74/24
 - [FriendCircle](https://github.com/razerdp/FriendCircle):对个人综合实力的一个总结和回顾，意在实现一个微信朋友圈，目前仍然在继续中。start/fork:19/9

### 技术文章
简书文集：
- [一起撸个朋友圈吧](http://www.jianshu.com/notebooks/3224048/latest)
- [Volley的封装](http://www.jianshu.com/p/95f5590b1203) 

CSDN:
- [打造通用的PopupWindow](http://blog.csdn.net/mkfrank/article/details/50522666)

---
### 技能清单
以下均为我目前拥有的技能

程序方向：
- Android(java)：熟练
- 后端：spring mvc （初学）
- C++：学校基础课程
- IDEA：AndroidStudio （熟练）
- 数据库相关：MySQL （初学）
- 版本管理：Svn/Git

视觉方向：
- 视频/图像后期：Adobe AfterEffects：熟练（目前为AE吧小吧主）
- 文档语言：MarkDown：常用

---

###个人评价、个人爱好
一个文艺的程序猿，爱好和平，喜欢（纯）音乐，作为一枚码农同时兼职着文艺青年，在撸代码的空闲时间经营着一个[LOFTER](http://razerdp.lofter.com/)博客，经营三年拥有粉丝5000，爱好分享，喜欢研究新的框架如Rx系列，有着一颗封装的心，新建一个类想到的是其他人怎样才能方便使用。能写代码也能写文章，能做出app也下得了厨房，每天最大的希望是能够学到新鲜的东西，最终的愿望是实现世界和平←_←。

---
### 致谢
感谢您花时间阅读我的简历，期待能有机会来到贵公司面试。
