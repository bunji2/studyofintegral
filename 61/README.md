# 【高校数学】今週の積分 #61 【難易度★★】

<!--
![今週のお題](https://latex.codecogs.com/gif.latex?I=\int\frac{1}{x\sqrt{1-x^2}}dx)
-->
![](0.gif)

https://www.youtube.com/watch?v=KJNePK-t--E

----

根号があると、積分はやりにくい。というわけで、

発想：根号は基本的に外す。

実は [#60](60.md) と根号の中の符号が異なるだけなのだが、積分の結果は違う形になる。

----

<!--
![](https://latex.codecogs.com/gif.latex?t=\sqrt{1-x^2})
-->
![](1.gif)

 とおくと 

<!--
![](https://latex.codecogs.com/gif.latex?x^2=1-t^2)
-->
![](2.gif)

 となるので、

----

<!--
![](https://latex.codecogs.com/gif.latex?dt=-\frac{x}{\sqrt{1-x^2}}dx)
-->
![](3.gif)

----

ゆえに置換積分すると次のようになる。

<!--
![](https://latex.codecogs.com/gif.latex?I=\int\frac{1}{x\sqrt{1-x^2}}dx=\int-\frac{1}{x^2}dt=\int\frac{1}{t^2-1}dt)
-->
![](4.gif)

ここで部分分数分解をすれば、

<!--
![](https://latex.codecogs.com/gif.latex?I=\int\frac{1}{t^2-1}dt=\int\frac{1}{(t-1)(t&plus;1)}dt=\frac{1}{2}\int\left(\frac{1}{t-1}-\frac{1}{t&plus;1}\right)dt)
-->
![](5.gif)

従って、

<!--
![](https://latex.codecogs.com/gif.latex?I=\frac{1}{2}\int\left(\frac{1}{t-1}-\frac{1}{t&plus;1}\right)dt=\frac{1}{2}\left(\log|t-1|-\log|t&plus;1|\right)&plus;C)
-->
![](6.gif)

そして 

<!--
![](https://latex.codecogs.com/gif.latex?t=\sqrt{1-x^2})
-->
![](7.gif)

 なので、

<!--
![](https://latex.codecogs.com/gif.latex?I=\frac{1}{2}\left(\log|\sqrt{1-x^2}-1|-\log|\sqrt{1-x^2}&plus;1|\right)&plus;C)
-->
![](8.gif)

以上。
