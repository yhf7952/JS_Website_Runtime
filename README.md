# JS_Website_Runtime

显示网站运行时间的JS脚本

# 使用方法

引用源码中加入runTime方法,并调用，如：

<pre>
runTime(2017,12,20,8,05,20);
</pre>

详情查看：https://y2z.top/blog/322/

# 实现原理

<ol>
<li>根据参数输入的起始时间，自动计算起始时间至今的天、时、分、秒</li>
<li>输出span显示计算结果，如已存在span则更新结果</li>
<li>每秒钟运行程序，计算最新结果以实现动态显示</li>
</ol>