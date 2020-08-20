# 【高校数学】今週の積分#84【難易度★★★】

![\begin{eqnarray}
I=\int_\frac{1}{2}^1x\sqrt{\dfrac{1}{x}-1}dx\nonumber
\end{eqnarray}](texclip20200820213739.png)

https://www.youtube.com/watch?v=y3_4L4Hh7bk

----

![\begin{eqnarray}
I&=&\int_\frac{1}{2}^1x\sqrt{\dfrac{1}{x}-1}dx\nonumber\\
&=&\int_\frac{1}{2}^1\sqrt{x-x^2}dx\nonumber\\
&=&\int_\frac{1}{2}^1\sqrt{\dfrac{1}{4}-\left(x-\dfrac{1}{2}\right)^2}dx
\end{eqnarray}](texclip20200820214128.png)

----

【発想】

![\sqrt{a^2-x^2}](texclip20200820214254.png)

を含む形ならば、

![$x=a\sin\theta$](texclip20200820214425.png)

と置換する。

----

ここでは以下の置換を行う。

![\begin{eqnarray}
x-\dfrac{1}{2}=\dfrac{1}{2}\sin\theta\nonumber\\
dx=\dfrac{1}{2}\cos\thetad\theta\nonumber\\
\dfrac{x: \frac{1}{2}\rightarrow{1}}{\theta: 0\rightarrow\frac{\pi}{2}}\nonumber
\end{eqnarray}](texclip20200820214805.png)

(1) を置換すると

![\begin{eqnarray}
I&=&\dfrac{1}{2}\int_0^\frac{\pi}{2}\sqrt{1-\sin^2\theta}\cdot\dfrac{1}{2}\cos\theta dx\nonumber\\
&=&\dfrac{1}{4}\int_0^\frac{\pi}{2}\cos^2\theta d\theta\nonumber\\
&=&\dfrac{1}{4}\int_0^\frac{\pi}{2}\dfrac{1+\cos{2\theta}}{2}d\theta\nonumber\\
&=&\dfrac{1}{4}\left[\dfrac{1}{2}\theta+\dfrac{1}{4}\sin{2\theta}\right]_0^\frac{\pi}{2}\nonumber\\
&=&\dfrac{\pi}{16}\nonumber
\end{eqnarray}](texclip20200820215644.png)

----

【発想2】

![\sqrt{a^2-x^2}](texclip20200820214254.png)

を含む形ならば、円の面積を考える。

----

![\begin{eqnarray}
y=\sqrt{\dfrac{1}{4}-\left(x-\dfrac{1}{2}\right)^2}\nonumber\\
y^2+\left(x-\dfrac{1}{2}\right)^2=\left(\dfrac{1}{2}\right)^2\nonumber\\
(y\ge{0})\nonumber\\
(\frac{1}{2}\le{x}\le{1})\nonumber
\end{eqnarray}](texclip20200820220514.png)

したがって半径が 1/2 の円の 1/4 の面積に等しい。

![\begin{eqnarray}
I&=&\left(\dfrac{1}{2}\right)^2\pi\cdot\dfrac{1}{4}\nonumber\\
&=&\dfrac{\pi}{16}\nonumber
\end{eqnarray}](texclip20200820220813.png)