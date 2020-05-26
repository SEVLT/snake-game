# 贪吃蛇游戏

[效果预览](https://sevlt.github.io/Snake/index.html)

### 移动方式

-   侦听键盘键码来改变以移动方向，需要注意蛇身长度为 1 时候可改变四个防线，不为 1 时可改变两个方向

### 生成食物块

-   通过 Math.random() 函数实现，要同时考虑地大小、食物块大小，以食物块大小为基本单位，避免边界穿过食物块

### 重构蛇身

-   通过 arrX 数组与 arrY 数组记录蛇身坐标（left、top），吃到新的食物块，原蛇头移动到食物块位置，除蛇头部分全部前移一格

### 游戏结束

-   撞击边界游戏结束
-   撞击蛇身游戏结束
