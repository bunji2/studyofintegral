# 【高校数学】今週の積分#22【難易度★★★★★】

<!--
![](https://latex.codecogs.com/gif.latex?I=\int\frac{1}{\cos^3\theta}d\theta)
-->
![](0.gif)

https://www.youtube.com/watch?v=bwNJ8mVhlF4

----

発想：三角関数は二乗に強い。

----

とりあえず二乗の形を作ってみる。



<!--
![](https://latex.codecogs.com/gif.latex?I=\int\frac{1}{\cos^2\theta}\cdot\frac{1}{\cos\theta}d\theta)
-->
![](1.gif)

部分積分をして、

<!--
![](https://latex.codecogs.com/gif.latex?I=\int(\tan\theta)'\cdot\frac{1}{\cos\theta}d\theta)
-->
![](2.gif)


<!--
![](https://latex.codecogs.com/gif.latex?=\tan\theta\cdot\frac{1}{\cos\theta}&space;-\int\tan\theta\cdot\frac{\sin\theta}{\cos^2\theta}d\theta)
-->
![](3.gif)

<!--
![](https://latex.codecogs.com/gif.latex?=\frac{\sin\theta}{\cos^2\theta}&space;-\int\frac{\sin^2\theta}{\cos^3\theta}d\theta)
-->
![](4.gif)

<!--
![](https://latex.codecogs.com/gif.latex?=\frac{\sin\theta}{\cos^2\theta}&space;-\int\frac{1-\cos^2\theta}{\cos^3\theta}d\theta)
-->
![](5.gif)

<!--
![](https://latex.codecogs.com/gif.latex?=\frac{\sin\theta}{\cos^2\theta}&space;-\int\frac{1}{\cos^3\theta}d\theta&space;&plus;\int\frac{1}{\cos\theta}d\theta)
-->
![](6.gif)

<!--
![](https://latex.codecogs.com/gif.latex?=\frac{\sin\theta}{\cos^2\theta}-I&plus;\int\frac{1}{\cos\theta}d\theta)
-->
![](7.gif)

同形出現となったので、

<!--
![](https://latex.codecogs.com/gif.latex?2I=\frac{\sin\theta}{\cos^2\theta}&plus;\int\frac{1}{\cos\theta}d\theta)
-->
![](8.gif)

第二項の積分を行うと、

----

<!--
![](https://latex.codecogs.com/gif.latex?\int\frac{1}{\cos\theta}d\theta=\int\frac{\cos\theta}{\cos^2\theta}d\theta=\int\frac{\cos\theta}{1-\sin^2\theta}d\theta)
-->
![](9.gif)

<!--
![](https://latex.codecogs.com/gif.latex?t=\sin\theta)
-->
![](10.gif)

<!--
![](https://latex.codecogs.com/gif.latex?dt=\cos\theta{d\theta})
-->
![](11.gif)

----

置換して、部分分数分解をすると、

<!--
![](https://latex.codecogs.com/gif.latex?\int\frac{\cos\theta}{1-\sin^2\theta}d\theta=\int\frac{1}{1-t^2}dt=\frac{1}{2}\int(\frac{1}{1&plus;t}-\frac{1}{1-t})dt)
-->
![](12.gif)

<!--
![](https://latex.codecogs.com/gif.latex?=\frac{1}{2}(\log|1&plus;t|-\log|1-t|)&plus;C)
-->
![](13.gif)

<!--
![](https://latex.codecogs.com/gif.latex?=\frac{1}{2}(\log|1&plus;\sin\theta|-\log|1-\sin\theta|)&plus;C)
-->
![](14.gif)

<!--
![](https://latex.codecogs.com/gif.latex?=\frac{1}{2}\log|\frac{1&plus;\sin\theta}{1-\sin\theta}|&plus;C)
-->
![](15.gif)

----

従って、

<!--
![](https://latex.codecogs.com/gif.latex?2I=\frac{\sin\theta}{\cos^2\theta}&plus;\frac{1}{2}\log|\frac{1&plus;\sin\theta}{1-\sin\theta}|&plus;C)
-->
![](16.gif)

<!--
![](https://latex.codecogs.com/gif.latex?I=\frac{\sin\theta}{2\cos^2\theta}&plus;\frac{1}{4}\log|\frac{1&plus;\sin\theta}{1-\sin\theta}|&plus;C')
-->
![](17.gif)

以上。
