# packet
哆唻咪-除夕红包活动
问题：在iPhone设备上点击时会出现一个半透明的灰色背景。
解决方法：
html,body{
    -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
-webkit-tap-highlight-color 是 css3 的新属性，这个属性只用于 IOS(iPhone和iPad)。当你点击一个链接或通过 Javascript 定义的可点击元素的时候，它就会出现一个半透明的灰色背景。你可以设置 -webkit-tap-highlight-color 为任何颜色，想要禁用这个背景，设置颜色的透明度设置为0。
