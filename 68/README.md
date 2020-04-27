# 【高校数学】今週の積分#68【難易度★★★】

<!--
![](https://latex.codecogs.com/gif.latex?I=\int_0^2\frac{e^x}{e^x&plus;e^{2-x}}dx)
-->
![](0.gif)

https://www.youtube.com/watch?v=kBJAtB31Jcw

----

発想：微分形の接触を作る

----

![](0.gif)

<!--
![](https://latex.codecogs.com/gif.latex?=\int_0^2\frac{e^{2x}}{e^{2x}&plus;e^{2}}dx)
-->
![](1.gif)

<!--
![](https://latex.codecogs.com/gif.latex?=\frac{1}{2}\int_0^2\frac{(e^{2x}&plus;e^{2})'}{e^{2x}&plus;e^{2}}dx)
-->
![](2.gif)

<!--
![](https://latex.codecogs.com/gif.latex?=\frac{1}{2}\left[e^{2x}&plus;e^{2}\right]_0^2)
-->
![](3.gif)

<!--
![](https://latex.codecogs.com/gif.latex?=\frac{1}{2}\left[e^{2x}&plus;e^{2}\right]_0^2)
-->
![](4.gif)

<!--
![](https://latex.codecogs.com/gif.latex?=\frac{1}{2}\log\frac{e^4&plus;e^2}{1&plus;e^2})
-->
![](5.gif)

<!--
![](https://latex.codecogs.com/gif.latex?=1)
-->
![](6.gif)

----

King Property を使って解く。

<!--
![](https://latex.codecogs.com/gif.latex?f(x)=\frac{e^x}{e^x&plus;e^{2-x}})
-->
![](7.gif)

<!--
![](https://latex.codecogs.com/gif.latex?2I=\int_a^b\{f(x)&plus;f(a&plus;b-x)\}dx)
-->
![](8.gif)

この積分の場合、
<!--
![](https://latex.codecogs.com/gif.latex?f(x)&plus;f(a&plus;b-x))
-->
![](9.gif)

が簡単に積分できるので King Property の適用は有効である。

<!--
![](https://latex.codecogs.com/gif.latex?2I=\int_0^2\{\frac{e^x}{e^x&plus;e^{2-x}}&plus;\frac{e^{2-x}}{e^{2-x}&plus;e^{2-(2-x)}}\}dx)
-->
![](10.gif)


<!--
![](https://latex.codecogs.com/gif.latex?=\int_0^21dx)
-->
![](11.gif)

<!--
![](https://latex.codecogs.com/gif.latex?=2)
-->
![](12.gif)

<!--
![](https://latex.codecogs.com/gif.latex?\therefore{I=1})
-->
![](13.gif)

以上。