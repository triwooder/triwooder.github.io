# 微积分 Calculus

相对于初等数学来说，微积分更像是一种“动态”的数学。

## 一、极限 Limits

### 1. 什么是极限？

极限是一个很直观的概念，是指一个函数在自变量趋近于某个值时，它的函数值趋近的值。这个趋近的值可能存在，也可能不存在；可能和这个点本身的函数值相等，也可能不相等（这个点也可能没有对应的函数值）。极限的记号为：
$$
\lim_{x\to c} f(x)=L
$$
这个记号有两层含义：

1. $f(x)\ 在\ c\ 处的极限存在$
2. $f(x)\ 在\ c\ 处的极限为\ L$

>- 例 1：函数值不存在，极限存在
>
>$$
>f(x)=\frac{x}{\sqrt{x+1}-1}\\
>\lim_{x\to 0}f(x)=2
>$$
>
>- 例 2：函数值存在，极限存在但与函数值不等
>
>$$
>f(x)=\begin{cases}
>	1,& x\not=2\\
>	0,& x=2
>\end{cases}\\
>\lim_{x\to 2}f(x)=1\not=f(2)
>$$

当然，极限也有形式化的定义：

$假设\ f\ 是定义在\ x=c\ 的邻域上的一段函数，L\ 是实数，那么$
$$
\lim_{x\to c}f(x)=L
$$
$意味着，对于任意小的\ \varepsilon >0，存在一个\ \delta >0，使得所有满足$
$$
0<|x-c|<\delta
$$
$的\ x\ 都满足$
$$
|f(x)=L|<\varepsilon
$$






