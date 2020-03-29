# 【高校数学】今週の積分#14【難易度★★★★★】

<!--
![](https://latex.codecogs.com/gif.latex?I=\int\frac{1}{\sqrt{x^2&plus;6x&plus;13}}dx)
-->
![](0.gif)

https://www.youtube.com/watch?v=26EXOUgtgOg

----

発想：

<!--
![](https://latex.codecogs.com/gif.latex?\sqrt{x^2&plus;1})
-->
![](1.gif)

を含む形のときには、

<!--
![](https://latex.codecogs.com/gif.latex?t=x&plus;\sqrt{x^2&plus;1})
-->
![](2.gif)

と置換する。

双曲線関数でも可。#6 参照。

----

根号の中を平方完成する。

<!--
![](https://latex.codecogs.com/gif.latex?\sqrt{x^2&plus;6x&plus;13}=\sqrt{(x&plus;3)^2&plus;4}=2\sqrt{(\frac{x&plus;3}{2})^2&plus;1})
-->
![](3.gif)



<!--
![](https://latex.codecogs.com/gif.latex?I=\frac{1}{2}\int\frac{1}{\sqrt{(\frac{x&plus;3}{2})^2&plus;1}}dx)
-->
![](4.gif)

ここで、次のようにすれば上の発想の形に変形できる。

----

<!--
![](https://latex.codecogs.com/gif.latex?s=\frac{x&plus;3}{2})
-->
![](5.gif)

<!--
![](https://latex.codecogs.com/gif.latex?dx=2ds)
-->
![](6.gif)

----


<!--
![](https://latex.codecogs.com/gif.latex?I=\int\frac{1}{\sqrt{s^2&plus;1}}dx)
-->
![](7.gif)

ここで発想の置換を行う。

----

<!--
![](https://latex.codecogs.com/gif.latex?t=s&plus;\sqrt{s^2&plus;1})
-->
![](8.gif)

<!--
![](https://latex.codecogs.com/gif.latex?dt=(1&plus;\frac{1}{2}\cdot\frac{2s}{\sqrt{s^2&plus;1}})ds=\frac{s&plus;\sqrt{s^2&plus;1}}{\sqrt{s^2&plus;1}}ds=\frac{t}{\sqrt{s^2&plus;1}}ds)
-->
![](9.gif)

<!--
![](https://latex.codecogs.com/gif.latex?\frac{1}{\sqrt{s^2&plus;1}}ds=\frac{1}{t}dt)
-->
![](10.gif)

----

置換すると、

<!--
![](https://latex.codecogs.com/gif.latex?I=\int\frac{1}{t}dt=\log|t|&plus;C)
-->
![](11.gif)

変形して、

<!--
![](https://latex.codecogs.com/gif.latex?I=\log|s&plus;\sqrt{s^2&plus;1}|&plus;C=\log|\frac{x&plus;3}{2}&plus;\sqrt{(\frac{x&plus;3}{2})^2&plus;1}|&plus;C)
-->
![](12.gif)

定数項を整理して、

<!--
![](https://latex.codecogs.com/gif.latex?I=\log|\frac{x&plus;3&plus;\sqrt{x^2&plus;6s&plus;13}}{2}|&plus;C=\log|x&plus;3&plus;\sqrt{x^2&plus;6s&plus;13}|&plus;C')
-->
![](13.gif)

以上。
