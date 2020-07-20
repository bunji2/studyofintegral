# 【高校数学】今週の積分#80【難易度★★】


![\begin{eqnarray}
I=\int_0^{\pi}e^{2x}\sin{x}dx\nonumber
\end{eqnarray}](texclip20200720231409.png)

https://www.youtube.com/watch?v=maurknIPZzc

----

発想：積分対象が（指数関数）×（三角関数）のときは、部分積分して同形出現させる。

----

![\begin{eqnarray}
I&=&\int_0^{\pi}e^{2x}\sin{x}dx\nonumber\\
 &=&\left[\dfrac{1}{2}e^{2x}\sin{x}\right]_0^{\pi}-\dfrac{1}{2}\int_0^{\pi}e^{2x}\cos{x}dx\nonumber\\
 &=&-\dfrac{1}{2}\left\{\left[\dfrac{1}{2}e^{2x}\cos{x}\right]_0^{\pi}+\dfrac{1}{2}\int_0^{\pi}e^{2x}\sin{x}dx\right\}\nonumber\\
 &=&-\dfrac{1}{4}\left\{-e^{2\pi}-1+I\right\}\nonumber
 \end{eqnarray}](texclip20200720232232.png)

同形出現を確認した。ゆえに、

![\begin{eqnarray}
\dfrac{5}{4}I&=&\dfrac{1}{4}(e^{2\pi}+1)\nonumber\\
\therefore{I}&=&\dfrac{1}{5}(e^{2\pi}+1)\nonumber
\end{eqnarray}](texclip20200720232557.png)

以上。