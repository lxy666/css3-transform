# css3-transform

transform: none|transform-functions;


| 值 | 描述 |
| --- | --- |
| none  | 不进行转换 |
| matrix(n,n,n,n,n,n)  | 2D 转换，使用六个值的矩阵 |
| matrix3d(n,n,n,n,n,n,n,n,n,n,n,n,n,n,n,n)  | 3D 转换，使用 16 个值的 4x4 矩阵 |
| translate(x,y)  | 2D 转换 |
| translate3d(x,y,z） | 3D 转换 |
| translateX(x)  | 转换，只是用 X 轴的值 |
| translateY(y)  | 转换，只是用 Y 轴的值 |
| translateZ(z)  | 3D 转换，只是用 Z 轴的值 |
| scale(x,y)  | 2D 缩放转换 |
| scale3d(x,y,z)  | 3D 缩放转换 |
| scaleX(x)  | 通过设置 X 轴的值来定义缩放转换 |
| scaleY(y)  | 通过设置 Y 轴的值来定义缩放转换 |
| scaleZ(z)  | 通过设置 Z 轴的值来定义 3D 缩放转换 |
| rotate(angle)  |  2D 旋转，在参数中规定角度 |
| rotate3d(x,y,z,angle） | 3D 旋转 |
| rotateX(angle） | X 轴的 3D 旋转 |
| rotateY(angle)  | Y 轴的 3D 旋转 |
| rotateZ(angle） | Z 轴的 3D 旋转|
| perspective(n)  | 为 3D 转换元素定义透视视图 |


# css3-animation


| 值 | 描述 |
| --- | --- |
|animation|简写|
|animation-name	|规定需要绑定到选择器的 keyframe 名称。|
|animation-duration	|规定完成动画所花费的时间，以秒或毫秒计。|
|animation-timing-function	|规定动画的速度曲线。|
|animation-delay|	规定在动画开始之前的延迟。|
|animation-iteration-count	|规定动画应该播放的次数。|
|animation-direction	|规定是否应该轮流反向播放动画。|

animation-timing-function 使用名为三次贝塞尔（Cubic Bezier）函数的数学函数，来生成速度曲线。您能够在该函数中使用自己的值，也可以预定义的值：

|值| 描述|
|---|---|
|linear |动画从头到尾的速度是相同的。 |
|ease |默认。动画以低速开始，然后加快，在结束前变慢。 |
|ease-in |动画以低速开始。 |
|ease-out |动画以低速结束。 |
|ease-in-out |动画以低速开始和结束。 |
|cubic-bezier(n,n,n,n) |在 cubic-bezier 函数中自己的值。可能的值是从 0 到 1 的数值。 |
