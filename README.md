
# 
Investment

## 3. 风险与收益


### 为什么？？

为什么会有(公式3-22)：

<img src="https://latex.codecogs.com/gif.latex?1&plus;E\left&space;(&space;r&space;\right&space;)=&space;e^&space;{E\left&space;(&space;r_{cc}&space;\right&space;)}&space;=&space;e^m" title="1+E\left ( r \right )= e^ {E\left ( r_{cc} \right )} = e^m" />

### 前提

a.连续复利：复利时时刻刻都在计算, 且服从正态分布。

b.一年分为无数个持有期（持有期数<a href="https://www.codecogs.com/eqnedit.php?latex=n&space;\to&space;&plus;\infty" target="_blank"><img src="https://latex.codecogs.com/gif.latex?n&space;\to&space;&plus;\infty" title="n \to +\infty" /></a>, 每个持有期长度<a href="https://www.codecogs.com/eqnedit.php?latex=t&space;\to&space;0" target="_blank"><img src="https://latex.codecogs.com/gif.latex?t&space;\to&space;0" title="t \to 0" /></a>）

c.年度复利变量<a href="https://www.codecogs.com/eqnedit.php?latex=r_{cc}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?r_{cc}" title="r_{cc}" /></a>服从正态分布，在第i个持有期内的利率为<a href="https://www.codecogs.com/eqnedit.php?latex=t\cdot&space;r_{cc_{i}}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?t\cdot&space;r_{cc_{i}}" title="t\cdot r_{cc_{i}}" /></a>

d.当<a href="https://www.codecogs.com/eqnedit.php?latex=t&space;\to&space;0" target="_blank"><img src="https://latex.codecogs.com/gif.latex?t&space;\to&space;0" title="t \to 0" /></a>时，
<a href="https://www.codecogs.com/eqnedit.php?latex=\ln&space;\left&space;(&space;1&plus;r&space;\right&space;)&space;=&space;r" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\ln&space;\left&space;(&space;1&plus;r&space;\right&space;)&space;=&space;r" title="\ln \left ( 1+r \right ) = r" /></a>


### 证明

<a href="https://www.codecogs.com/eqnedit.php?latex=1&plus;E\left&space;(&space;r&space;\right&space;)&space;=&space;\lim_{t&space;\to&space;0}&space;\left&space;\lfloor&space;\left&space;(&space;1&plus;t\cdot&space;r_{cc_{1}}&space;\right&space;)\cdots&space;\left&space;(&space;1&plus;t\cdot&space;r_{cc_{n}}&space;\right&space;)&space;\right&space;\rfloor" target="_blank"><img src="https://latex.codecogs.com/gif.latex?1&plus;E\left&space;(&space;r&space;\right&space;)&space;=&space;\lim_{t&space;\to&space;0}&space;\left&space;\lfloor&space;\left&space;(&space;1&plus;t\cdot&space;r_{cc_{1}}&space;\right&space;)\cdots&space;\left&space;(&space;1&plus;t\cdot&space;r_{cc_{n}}&space;\right&space;)&space;\right&space;\rfloor" title="1+E\left ( r \right ) = \lim_{t \to 0} \left \lfloor \left ( 1+t\cdot r_{cc_{1}} \right )\cdots \left ( 1+t\cdot r_{cc_{n}} \right ) \right \rfloor" /></a>

<a href="https://www.codecogs.com/eqnedit.php?latex==&space;\lim_{t&space;\to&space;0}&space;e^&space;\ln&space;\left&space;(&space;1&plus;t\cdot&space;r_{cc_{1}}&space;\right&space;)&space;&plus;\cdots&space;&plus;&space;\ln&space;\left&space;(&space;1&plus;t\cdot&space;r_{cc_{n}}&space;\right&space;)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?=&space;\lim_{t&space;\to&space;0}&space;e^&space;\ln&space;\left&space;(&space;1&plus;t\cdot&space;r_{cc_{1}}&space;\right&space;)&space;&plus;\cdots&space;&plus;&space;\ln&space;\left&space;(&space;1&plus;t\cdot&space;r_{cc_{n}}&space;\right&space;)" title="= \lim_{t \to 0} e^ \ln \left ( 1+t\cdot r_{cc_{1}} \right ) +\cdots + \ln \left ( 1+t\cdot r_{cc_{n}} \right )" /></a>

<a href="https://www.codecogs.com/eqnedit.php?latex==&space;\lim_{t&space;\to&space;0}&space;e^{t\cdot&space;r_{cc_{1}}&space;&plus;&space;\cdots&space;&plus;&space;t\cdot&space;r_{cc_{n}}}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?=&space;\lim_{t&space;\to&space;0}&space;e^{t\cdot&space;r_{cc_{1}}&space;&plus;&space;\cdots&space;&plus;&space;t\cdot&space;r_{cc_{n}}}" title="= \lim_{t \to 0} e^{t\cdot r_{cc_{1}} + \cdots + t\cdot r_{cc_{n}}}" /></a>

<a href="https://www.codecogs.com/eqnedit.php?latex==&space;e^&space;{E\left&space;(&space;r_{cc}&space;\right&space;)}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?=&space;e^&space;{E\left&space;(&space;r_{cc}&space;\right&space;)}" title="= e^ {E\left ( r_{cc} \right )}" /></a>

### 实际意义

在不足一年的短期内，年度连续复利的算数平均数表示年化百分利率。

也就是可以认为每时每刻的复利利率为定值，这个值为算术平均数，得出的有效年利率相同(结合公式3-9)。

### FAQ

1. 这里的1+E(r)=exp(m), 为什么不根据期望公式E(X)=exp(u+1/2sigma^2)而得出 1+E(r) = exp (m+1/2sigma^2) ?

   这是因为1+E(r)服从对数正态分布，它的函数表达式为exp(m). 1+E(r)整体对应为变量X，其为变量而不是期望。

   因此应是1+E(r)的期望即E(1+E(r)) = exp(u+1/2sigma^2).

