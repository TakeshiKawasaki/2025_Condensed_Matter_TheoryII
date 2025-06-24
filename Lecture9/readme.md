# 第9回講義資料  
**内容：** 実空間くりこみ群

## Q&A集 
https://irradiated-pot-667.notion.site/II-9-Q-A-21bc4e3a1a4e80528a62f10a077e9be9?pvs=73

## 修正履歴  
6/17 17:15 <br>
p24 本文「このとき，くりこみ群の変換式」以下の式：  
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
6/21 14:25<br>
p18 式(22)最後の式の分母のxが抜けていたので以下のように修正<br>

$$
\frac{(x + y + x y^2 + x^2 y)}{x(1 + y)^2}
$$

p30-32<br>
式(37)-(38)ですが、式(36)に $b=x^{-1/y_x}$ を代入したあとの符号が$x$の指数の符号が逆でしたので修正。βの指数は0なので影響なし。<br>
式(40)-(41)に関しても同様に\epsilonの指数符号ミス。その後の\epsilonの指数は0なので影響なし。<br>
大変失礼しました。

