# 【高校数学】今週の積分#3【難易度★★★★】

<!--
![](https://latex.codecogs.com/gif.latex?I=\int_0^1\sqrt\frac{1-x}{1&plus;x}dx)
-->
![](0.gif)

https://www.youtube.com/watch?v=GJKxttevVWg

----

発想：

<!--
![](https://latex.codecogs.com/gif.latex?\sqrt\frac{ax&plus;b}{cx&plus;d})
-->
![](1.gif)

の場合は

<!--
![](https://latex.codecogs.com/gif.latex?t=\sqrt\frac{ax&plus;b}{cx&plus;d})
-->
![](2.gif)

と置換すると t だけの式となる。

----

<!--
![](https://latex.codecogs.com/gif.latex?t=\sqrt\frac{1-x}{1&plus;x})
-->
![](3.gif)

とすると、積分範囲は次のようになる。

<!--
![](https://latex.codecogs.com/gif.latex?x:0\rightarrow1)
-->
![](4.gif)

<!--
![](https://latex.codecogs.com/gif.latex?t:1\rightarrow0)
-->
![](5.gif)

そして

<!--
![](https://latex.codecogs.com/gif.latex?t^2=\frac{1-x}{1&plus;x})
-->
![](6.gif)

より

<!--
![](https://latex.codecogs.com/gif.latex?x=\frac{1-t^2}{1&plus;t^2})
-->
![](7.gif)

<!--
![](https://latex.codecogs.com/gif.latex?\frac{dx}{dt}=\frac{-2t(1&plus;t^2)-2t(1-t^2)}{(1&plus;t^2)^2}=\frac{-4t}{(1&plus;t^2)^2})
-->
![](8.gif)

<!--
![](https://latex.codecogs.com/gif.latex?dx=-\frac{4t}{(1&plus;t^2)^2}dt)
-->
![](9.gif)

----

以上を用いて置換積分すると次のようになる。

<!--
![](https://latex.codecogs.com/gif.latex?I=\int_1^0&space;t\cdot\left(-\frac{4t}{(1&plus;t^2)^2}\right)dt=4\int_0^1\frac{t^2}{(1&plus;t^2)^2}dt)
-->
![](10.gif)

ここでさらに置換積分をする。

----

<!--
![](https://latex.codecogs.com/gif.latex?t=\tan\theta)
-->
![](11.gif)

とすると、積分範囲は次のようになる。

<!--
![](https://latex.codecogs.com/gif.latex?t:0\rightarrow1)
-->
![](12.gif)

<!--
![](https://latex.codecogs.com/gif.latex?x:0\rightarrow\frac{\pi}{4})
-->
![](13.gif)

そして

<!--
![](https://latex.codecogs.com/gif.latex?dt=\frac{1}{\cos^2\theta}d\theta)
-->
![](14.gif)

----

以上を用いて置換積分すると次のようになる。

<!--
![](https://latex.codecogs.com/gif.latex?I=4\int_0^\frac{\pi}{4}\tan^2\theta\cdot\cos^4\theta\cdot\frac{1}{\cos^2\theta}d\theta=4\int_0^\frac{\pi}{4}\sin^2\theta&space;d\theta)
-->
![](15.gif)

半角の公式を使って次数をさげると、

<!--
![](https://latex.codecogs.com/gif.latex?I=4\int_0^\frac{\pi}{4}\left(\frac{1-\cos2\theta}{2}\right)d\theta=2\int_0^\frac{\pi}{4}\left(1-\cos2\theta\right)d\theta)
-->
![](16.gif)

定積分を計算すると次のようになる。

<!--
![](https://latex.codecogs.com/gif.latex?I=2\left[\theta-\frac{1}{2}\sin2\theta\right&space;]_0^\frac{\pi}{4}=2\left(\frac{\pi}{4}-\frac{1}{2}\right)=\frac{\pi}{2}-1)
-->
![](17.gif)

以上。
