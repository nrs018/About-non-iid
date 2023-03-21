# 关于non-iid的一些思考

## 1. 什么叫模型收敛？

首先，我们给出三种可能的答案，在后续的实验中不断地验证，究竟哪一个更正确些。

> a. $M_{n}$表示第n次更新后的模型。

<p align="center"> $\lim\limits_{n \to \infty} ||M_{n+1}-M_{n}|| = 0$ </p>

这个公式表示模型收敛于某个值/特定模型。

> b. $Loss_{n}$表示第n次更新后的损失函数。

<p align="center"> $\lim\limits_{n \to \infty} ||Loss_{n+1}-Loss_{n}|| = 0$  </p>

这个公式表示 $Loss_{n}$ 收敛于某个值。

> c. $Loss_{n}$表示第n次更新后的损失函数。

<p align="center"> $\lim\limits_{n \to \infty}{Loss_{n}} = 0$   </p>

这个公式表示 $Loss_{n}$ 收敛于0。


## 2. 两个模型的accuracy都在99.99%以上，那么他们会是无限相似吗？


## 3. accuracy >99.999%的模型是唯一的吗？

# 实验设计与描述

## 数据集的设计

$2 \times 2$的矩阵由4个元素组成。这里每个元素对应一个实数值，white表示的值分布在(0, 0.1)，black表示的值分布在(0.9, 1)。

数据集分为三个分类，分别是

A类：【B, W, W, B】
学号|姓名|
:-|:-:|
小明|男|
<table>
  <tr>
    <td style="background-color:#33475b">格</td>
    <td style="background-color: white;">另</td>
  </tr>
  <tr>
    <td style="background-color: #ff0000;">一</td>
    <td style="background-color: #00ff00;">另</td>
  </tr>
</table>

B类：【W, B, W, B】

C类：【W, W, B, B】

<div align="center">
<table>
<tbody>
<td align="center" bg-color="black">

<sub>This is text in the box. Much wow</sub><br>

</td>
</tbody>
</table>
</div>
