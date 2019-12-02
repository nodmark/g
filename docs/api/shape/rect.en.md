---
title: Rect
order: 8
---

# 属性

- 详见 [图形属性](en/docs/api/shape/api#属性)；

## attrs 绘图属性

> 通用的 [绘图属性](/en/docs/api/shape/attrs)

### x

- 起始点 x 坐标；

### y

- 起始点 y 坐标；

### width

- 宽度；

### height

- 高度；

### radius

- 圆角，支持整数或数组形式， 分别对应左上、右上、右下、左下角的半径。支持的形式有:
  - `1`: 相当于 [ 1, 1, 1, 1 ]
  - `[ 1 ]`: 相当于 [ 1, 1, 1, 1 ]
  - `[ 1, 2 ]`: 相当于 [ 1, 2, 1, 2 ]
  - `[ 1, 2, 3 ]`: 相当于 [ 1, 2, 3, 2 ]
  - `[ 1, 2, 3, 4 ]`