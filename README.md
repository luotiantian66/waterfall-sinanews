## waterfall-sinanews
预览地址：
## 懒加载原理：先加载一开始要显示在页面的图片，等到其他图片将要出现在窗口时再去加载其他图片的数据。
## 瀑布流原理：根据窗口宽度和列宽确定列数，每次加载图片时选取最小的总列高，排在该列下方。
## 实现原理：先获取部分数据，将数据拼接成一个div，进行瀑布布局。并绑定滚动事件，当数据要出现在窗口中时，获取部分数据，继续拼接。