---
tags: 优化 拉格朗日乘子法 定理
---

在约束条件 $g(x) \leq 0$ 下最小化 $f(x)$ 等价于在如下三个约束下最小化拉格朗日函数 $L(x, \lambda) = f(x) + \lambda g(x)$ ：$$\begin{aligned} g(x) \leq 0\\ \lambda \geq 0\\ \lambda g(x) = 0\end{aligned}$$ 这个式子称为 Karush-Kuhn-Tucker (KKT) 条件。