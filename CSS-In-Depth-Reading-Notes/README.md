# CSS In Depth Reading Notes

## 盒模型的概念

> 引述MDN文档：当对一个文档进行布局(laying out)的时候，浏览器渲染引擎会根据CSS-Box模型（CSS Basic Box model）将所有元素表示为一个矩形盒子（box)。CSS决定这些盒子的大小，位置以及属性（颜色，背景，边框尺寸...).

![box-model](./images/box-model.png)

通过上述引述，我们可以暂时简单地将盒模型理解为在页面上元素的组成。那元素的组成又包含了哪些内容呢？

1. 元素的宽高（width, height), 也就是其内容宽高。
2. 元素的内边距(padding)，边框边(border), 外边距(margin)。
