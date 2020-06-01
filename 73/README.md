# 【高校数学】今週の積分#73【難易度★★★】

![I=\int\dfrac{4(3+3x-x^2)}{(x-1)^2(x+1)}dx](texclip20200601202459.png)

https://www.youtube.com/watch?v=OWNAr-c-pY4

----

発想：分母が素因数分解できる→部分分数分解

分子の次数＞分母の次数の場合は分子の次数を下げてから。

----

![\begin{eqnarray}
\dfrac{4(3+3x-x^2)}{(x-1)^2(x+1)} & = & \dfrac{A}{x-1}+\dfrac{B}{(x-1)^2}+\dfrac{C}{x+1} \\
 & = & \dfrac{A(x-1)(x+1)+B(x+1)+C(x-1)^2}{(x-1)^2(x+1)} \nonumber\\
 & = & \dfrac{(A+C)x^2+(B-2C)x-A+B+C)}{(x-1)^2(x+1)}\nonumber
\end{eqnarray}](texclip20200601211159.png)

より、

![\left\{\begin{array}{l}
A+C = -4 \\
B-2C = 12 \\
-A+B+C = 12
\end{array}
](texclip20200601203808.png)

上を解くと、

![\left\{\begin{array}{l}
A=-3 \\
B=10 \\
C=-1
\end{array}](texclip20200601204210.png)

(1) の部分分数分解を完成させる。

![\dfrac{4(3+3x-x^2)}{(x-1)^2(x+1)} = \dfrac{-3}{x-1}+\dfrac{10}{(x-1)^2}+\dfrac{-1}{x+1} ](texclip20200601204459.png)

以上より、

![\begin{eqnarray}
I & = & \int\dfrac{-3}{x-1}dx+\int\dfrac{10}{(x-1)^2}dx+\int\dfrac{-1}{x+1}dx \nonumber \\
  & = & -3\log{|x-1|}-\dfrac{10}{x-1}-\log{|x+1|} + C \nonumber \\
  & = & \log{\left|\dfrac{1}{(x-1)^3(x+1)}\right|}-\dfrac{10}{x-1} + C \nonumber
\end{eqnarray}](texclip20200601205640.png)

以上

---

(1) で二項目の分子を定数でなく一次式にする、つまり、

![\begin{eqnarray}
\dfrac{4(3+3x-x^2)}{(x-1)^2(x+1)} & = & \dfrac{A}{x-1}+\dfrac{Bx+C}{(x-1)^2}+\dfrac{D}{x+1} \nonumber
\end{eqnarray}](texclip20200601210301.png)

のようにするべきではないかという意見もあるが、

![\setcounter{equation}{1}
\begin{eqnarray}
\dfrac{A}{x-1}+\dfrac{Bx+C}{(x-1)^2} & = & \dfrac{A}{x-1}+\dfrac{B(x-1)-B+C}{(x-1)^2} \nonumber \\
 & = & \dfrac{A}{x-1}+\dfrac{B}{x-1}+\dfrac{-B+C}{(x-1)^2} \nonumber\\
 & = & \dfrac{A+B}{x-1}+\dfrac{-B+C}{(x-1)^2} \nonumber\\
 & = & \dfrac{A'}{x-1}+\dfrac{B'}{(x-1)^2} 
\end{eqnarray}](texclip20200601210816.png)

のように (2) に変形できることから、結果として (1) を解いているのと同じこととなる。
