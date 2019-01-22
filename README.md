# packet
哆唻咪-除夕红包活动
1、问题：在iPhone设备上点击时会出现一个半透明的灰色背景。
解决方法：
html,body{
    -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
-webkit-tap-highlight-color 是 css3 的新属性，这个属性只用于 IOS(iPhone和iPad)。当你点击一个链接或通过 Javascript 定义的可点击元素的时候，它就会出现一个半透明的灰色背景。你可以设置 -webkit-tap-highlight-color 为任何颜色，想要禁用这个背景，设置颜色的透明度设置为0。
2、ios 音频播放延迟只有在第一次播放时会出现
video.play()必须要有时间触发才起作用
在开始的点击事件中
 myAuto.play();
        myAuto.pause();
        可解决

