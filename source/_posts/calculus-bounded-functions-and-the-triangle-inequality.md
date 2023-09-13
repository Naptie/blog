---
title: 有界函数与三角不等式
date: 2023-09-13 14:32:58
---

### 有界函数（bounded function）

Let $y=f(x)$, $x \in D$, $\exists M > 0$, $\forall x \in D$, we have $|f(x)| \le M$.

Then we say $f(x)$ is a bounded function.



### 三角不等式（the Triangle Inequality）

$\forall a_1, a_2, a_3, \dots, a_n \in \R$, we have

$|a_1 + a_2 + a_3 + \dots + a_n| \le |a_1|, |a_2|, |a_3|, \dots, |a_n|$



#### Prove that $f(x) = \sin^{95}x + 6\cos^{49}2x - 7\sin^75x$ is bounded on $\R$.

Proof:
$$
\because \forall x \in \R, |f(x)| \le |\sin^{95}x| + 6|\cos^{49}2x| + 7|\sin^75x| \le 1 + 6 + 7 = 14
$$

$$
\therefore f(x) \text{ is bounded on } \R
$$

