# copyDemo
IOS默认全选复制的三种方案
类似于textField，长按就会默认跳出复制的选项，但是默认选中的就是你手指点击的那个文字，想全选的话必须手动选择全选才可以，而最近碰到一个需求就是要点击文字，默认就是选中所有的文字，比如游戏中的邀请码，应用中的推广码等，所以默认全选复制肯定比再点击全选便捷，一般就是默认选择或者弹出提醒。这个就是这篇文章的使用意义

## 方案思路

一般显示文字的地方一般就是Label，textField，textView，Button这几种地方，所以要想默认全选复制文字，也就这几个控件，所以就从这里入手，所以三种方案分别是，从上到下，简单到麻烦

* textView加手势

* Label加手势（button按钮和这个是一个原理，所以不再写button的了）

* textField

## demo详细说明

**《[IOS默认全选复制的三种方案](http://www.hudongdong.com/ios/358.html)》**

## 效果图

![image](http://cdn.hudongdong.com/2016-09-14%2014_42_05.gif)
