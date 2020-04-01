# 【高校数学】今週の積分#28【難易度★★★★★】

<!--
![](https://latex.codecogs.com/gif.latex?I=\int_0^1\frac{1}{x^3&plus;1}dx)
-->
![](0.gif)

https://www.youtube.com/watch?v=YkbuXTr4w_Y

----

発想：

分母が因数分解できる場合は部分分数分解を行う。

----

与式を部分分数分解する。

<!--
![](https://latex.codecogs.com/gif.latex?I=\frac{1}{3}\int_0^1\frac{1}{x&plus;1}dx-\frac{1}{3}\int_0^1\frac{x-2}{x^2-x&plus;1}dx)
-->
![](1.gif)

積分すると、

<!--
![](https://latex.codecogs.com/gif.latex?I=\frac{1}{3}[\log|x&plus;1|]_0^1-\frac{1}{6}\int_0^1\frac{(x^2-x&plus;1)'-3}{x^2-x&plus;1}dx)
-->
![](2.gif)

<!--
![](https://latex.codecogs.com/gif.latex?=\frac{1}{3}\log2-\frac{1}{6}[\log|x^2-x&plus;1|]_0^1&plus;\frac{1}{2}\int_0^1\frac{1}{x^2-x&plus;1}dx)
-->
![](3.gif)

<!--
![](https://latex.codecogs.com/gif.latex?=\frac{1}{3}\log2&plus;\frac{1}{2}\int_0^1\frac{1}{x^2-x&plus;1}dx)
-->
![](4.gif)

<!--
![](https://latex.codecogs.com/gif.latex?=\frac{1}{3}\log2&plus;\frac{1}{2}\int_0^1\frac{1}{(x-\frac{1}{2})^2&plus;(\frac{\sqrt{3}}{2})^2}dx)
-->
![](5.gif)

<!--
![](https://latex.codecogs.com/gif.latex?=\frac{1}{3}\log2&plus;\frac{2}{3}\int_0^1\frac{1}{(\frac{2}{\sqrt{3}}x-\frac{1}{\sqrt{3}})^2&plus;1}dx)
-->
![](6.gif)

----

ここで以下の置換を行う。

<!--
![](https://latex.codecogs.com/gif.latex?\frac{2}{\sqrt{3}}x-\frac{1}{\sqrt{3}}=\tan\theta)
-->
![](7.gif)

<!--
![](https://latex.codecogs.com/gif.latex?dx=\frac{\sqrt{3}}{2}\frac{1}{\cos^2\theta}d\theta)
-->
![](8.gif)

<!--
![](https://latex.codecogs.com/gif.latex?x:0\rightarrow1)
-->
![](9.gif)

<!--
![](https://latex.codecogs.com/gif.latex?\theta:-\frac{\pi}{6}\rightarrow\frac{\pi}{6})
-->
![](10.gif)

----

置換を行うと、

<!--
![](https://latex.codecogs.com/gif.latex?I=\frac{1}{3}\log2&plus;\frac{2}{3}\int_{-\frac{\pi}{6}}^\frac{\pi}{6}\frac{1}{\tan^2\theta&plus;1}\cdot\frac{\sqrt{3}}{2}\frac{1}{\cos^2\theta}d\theta)
-->
![](11.gif)

<!--
![](https://latex.codecogs.com/gif.latex?=\frac{1}{3}\log2&plus;\frac{1}{\sqrt{3}}\int_{-\frac{\pi}{6}}^\frac{\pi}{6}d\theta)
-->
![](12.gif)

<!--
![](https://latex.codecogs.com/gif.latex?=\frac{1}{3}\log2&plus;\frac{\sqrt{3}}{9}\pi)
-->
![](13.gif)

以上。
