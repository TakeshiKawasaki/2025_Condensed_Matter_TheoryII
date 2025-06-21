# 第9回講義資料  
**内容：** 実空間くりこみ群

## 修正履歴  
6/17 17:15 <br>
p24「このとき，くりこみ群の変換式」以下の式：  
元の式：
$y' = \frac{(1 + y)(x + y)}{1 + x y}$
を次のように修正します：
$y' = \frac{y(x + y)}{1 + x y}$

また、その後の $y'$ の展開式も以下のように修正します：

$$
\begin{aligned}
y' &= \frac{y(x + y)}{1 + x y} \\
   &= \frac{(1 - \epsilon)(x + 1 - \epsilon)}{1 + x(1 - \epsilon)} \\
   &\sim \frac{x + 1 - 2\epsilon}{1 + x} \\
   &= \left( \frac{x + 1}{1 + x} \right) - \frac{2\epsilon}{1 + x} \\
   &= 1 - \frac{2\epsilon}{1 + x} \\
   &\sim 1 - 2\epsilon
\end{aligned}
$$
<br>
6/21 17:15<br>

式(22)最後の式の分母のxが抜けていたので以下のように修正<br>
$$
\frac{(x + y + x y^2 + x^2 y)}{x(1 + y)^2}
$$

