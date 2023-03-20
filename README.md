# 关于non-iid的一些思考

## 1. 什么叫模型收敛？

首先，我们给出三种可能的答案，在后续的实验中不断地验证，究竟哪一个更正确些。

> a. $M_{n}$表示第n次更新后的模型。

<p align="center"> $\lim\limits_{n \to \infty} ||M_{n+1}-M_{n}|| = 0$ </p>

这个公式表示模型收敛于某个值/特定模型。

> b. $Loss_{n}$表示第n次更新后的损失函数。

<p align="center"> $\lim\limits_{n \to \infty} ||Loss_{n+1}-Loss_{n}|| = 0$  </p>

这个公式表示$Loss_{n}$收敛于某个值。

> c. $Loss_{n}$表示第n次更新后的损失函数。

<p align="center"> $\lim\limits_{n \to \infty}{Loss_{n}} = 0$   </p>

这个公式表示 $Loss_{n}$ 收敛于0。


## 2. 两个模型的accuracy都在99.99%以上，那么他们会是无限相似吗？


## 3. accuracy >99.999%的模型是唯一的吗？
