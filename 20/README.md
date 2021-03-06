# 【高校数学】今週の積分#20【難易度★★★】

<!--
![](https://latex.codecogs.com/gif.latex?I=\int_0^{\sqrt{\frac{\pi}{2}}}x^3\cos{x^2}dx)
-->
![](0.gif)

https://www.youtube.com/watch?v=DK5Y3_VStpM

----

発想：三角関数の引数が複雑な場合は引数を置換する

----

<!--
![](https://latex.codecogs.com/gif.latex?t=x^2)
-->
![](1.gif)

とする。

<!--
![](https://latex.codecogs.com/gif.latex?x:0\rightarrow\sqrt{\frac{\pi}{2}})
-->
![](2.gif)

<!--
![](https://latex.codecogs.com/gif.latex?t:0\rightarrow\frac{\pi}{2})
-->
![](3.gif)

<!--
![](https://latex.codecogs.com/gif.latex?dt=2xdx)
-->
![](4.gif)

----

上記で置換積分を行うと、

<!--
![](https://latex.codecogs.com/gif.latex?I=\frac{1}{2}\int_0^{\sqrt\frac{\pi}{2}}x^2\cos{x^2}\cdot2xdx=\frac{1}{2}\int_0^{\frac{\pi}{2}}t\cos{t}dt)
-->
![](5.gif)


ここで部分積分を行うと、

<!--
![](https://latex.codecogs.com/gif.latex?I=\frac{1}{2}\left(\left[t\sin&space;t&space;\right&space;]_0^{\frac{\pi}{2}}-\int_0^{\frac{\pi}{2}}\sin{t}dt&space;\right)&space;=\frac{1}{2}\left(\frac{\pi}{2}&plus;\left[\cos{t}&space;\right]_0^{\frac{\pi}{2}}\right)&space;=\frac{\pi}{4}-\frac{1}{2})
-->
![](6.gif)

以上。
