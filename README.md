# 预览效果

#  https://newway7.github.io/Don-t-tread-on-white-cubes-/index.html
 
# 思路：
    放一个4*4的格子在页面中

    每行中随机选择一个作为黑块
    
     给这个盒子添加动画效果，删除移动到最低端隐藏不见的行；在行上面添加新的行。

# js达成的效果：
     踩到白块结束游戏
     
     最底端的那一行即将隐藏并删除时，如果没有点击黑块，游戏结束；
     
     漏点黑块时(比如先点击第1个黑块，接下来点击第3个黑块，遗漏了第2个)，结束游戏
     
     随着时间的推移，动画速度越来越快；
     
     游戏结束后，再次点击黑白块，弹窗提示'游戏已结束'。
