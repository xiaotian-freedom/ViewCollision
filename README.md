# 图片碰撞效果
此项目是一个图片在屏幕中做自由运动效果的库，该图片View继承与AppCompatImageView，涵盖功能如下：

1. 可加载gif地址，可附带加载停靠屏幕边缘时的静态地址
2. 加载资源成功后可自动在屏幕中做自由匀速运动
3. 可对view添加点击事件，demo中设置为点击图片消失
4. 在view运动时可用手指自由拖动
5. 拖动图片保持静止3秒（时间可根据需求设置），图片可自动向右移动隐藏或停靠屏幕边缘（demo中设置了半停靠在屏幕边缘），停靠后可设置显示为停靠图片（也可以不设置）
6. 与RecycleView联动，监听列表滚动或静止状态，滚动列表时图片从半停靠状态变为全停靠状态，同时图片自动设置为初始gif图或静态图

## 效果如图所示：
![碰撞图](https://github.com/xiaotian-freedom/ViewCollision/blob/main/screenshot/bubble-tick.gif)
