# 【高校数学】今週の積分#76【難易度★★★】

![\begin{eqnarray}
I=\int(x^2-2x)\cos{2x}dx\nonumber
\end{eqnarray}](texclip20200623222344.png)

https://www.youtube.com/watch?v=QZ-X-_w51IE

----

発想：

（整式）×（三角関数）は部分積分を繰り返す。

整式：微分する側

三角関数：積分する側

----

![\begin{eqnarray}
I&=&\int(x^2-2x)\cos{2x}dx\\
&=&(x^2-2x)\cdot\dfrac{1}{2}\sin{2x}-\int(2x-2)\cdot\dfrac{1}{2}\sin{2x}dx\\
&=&(x^2-2x)\cdot\dfrac{1}{2}\sin{2x}+(2x-2)\cdot\dfrac{1}{4}\cos{2x}-\int{2}\cdot\dfrac{1}{4}\cos{2x}dx\\
&=&(x^2-2x)\cdot\dfrac{1}{2}\sin{2x}+(2x-2)\cdot\dfrac{1}{4}\cos{2x}-\dfrac{1}{2}\cdot\dfrac{1}{2}\sin{2x}dx+C\\
&=&\dfrac{1}{4}\left\{(2x^2-4x-1)\sin{2x}+2(x-1)\cos{2x}\right\}+C
\end{eqnarray}](texclip20200623223551.png)

以上