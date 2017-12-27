# itxzytask6
bootstrap有大量可用的现成样式 http://how2j.cn/k/boostrap/boostrap-setup/539.html 。 
button之间会默认有一个间隔需要改写代码换行方式，就可以去除 http://www.zhangxinxu.com/wordpress/2012/04/inline-block-space-remove-%E5%8E%BB%E9%99%A4%E9%97%B4%E8%B7%9D/ 。
栅格系统
.col-xs- 超小屏幕 手机 (<768px)
.col-sm- 小屏幕 平板 (≥768px)
.col-md- 中等屏幕 桌面显示器 (≥992px)
.col-lg- 大屏幕 大桌面显示器 (≥1200px)
总数为12。
组合式按钮可用单独设置border-top/bottom-left-radius做出单边的圆角，另一边的按钮通过负margin来靠近之前一半。
下拉菜单需设置width：100%;min-width: 0使其不超出范围.
网页主体不要使用margin来设置fixed的距离，这样会让body整体下移，所以应使用padding.
垂直方向的图片+文字可用flex布局中的flex-warp来实现。http://www.ruanyifeng.com/blog/2015/07/flex-grammar.html
